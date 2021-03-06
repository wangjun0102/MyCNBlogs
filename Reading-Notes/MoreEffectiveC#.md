<h2>《More Effective C#》 :books: </h2> 

> [美] Bill Wagner 著    人民邮电出版社

```C#
1.使用 1.x 框架 API 的泛型版本。

2.恰当好处地定义约束。
 ① 搜索集合中第一个满足指定条件的对象。
 public static T FirstOrDefault<T> (this IEnumerable<T> sequence, Predicate<T> test)
 {
    foreach (T value in sequence)
       if (test(value))
           return value;
    return default(T);
 }

3.运行时检查泛型参数的类型并提供特定的算法。
 ① 设计一个将序列中的元素反序的类。
 private class ReverseStringEnumerator : IEnumerator<char> 
 {
    private string sourceSequence;
    private int currentIndex;
    public ReverseStringEnumerator (string source)
    {
       sourceSequence = source;
       currentIndex = source.Length;
    }
    #region IEnumerator<char> Members
    public char Current
    {
       get { return sourceSequence[currentIndex];  }
    }
    #endregion
    #region IDisposable Members
    public void Dispose() 
    {  
        // 无需实现 
    }
    #endregion
    #region IEnumerator Members
    object System.Collections.IEnumerator.Current 
    {
        get { return sourceSequence[currentIndex];  }
    }
    public bool MoveNext() 
    {
       return --currentIndex >= 0;
    }
    public void Reset() { currentIndex = sourceSequence.Length;  }
    #endregion
 }
 // ReverseEnumerable<T>.GetEnumerator() 需要检查参数的类型，并创建合适的枚举器类型。
 public IEnumerator<T> GetEnumerator()
 {
    // string 是个特例
    if (sourceSequence is string)
    {
       // 注意该转换，因为 T 在编译期可能不是 char
       return new ReverseStringEnumerator(sourceSequence as string) as IEnumerator<T>;
    }
    // 创建原有序列的副本，以便反序操作
    if (orginalSequence == null) 
    {
        if (sourceSequence is ICollection<T>)
        {
           ICollection<T> source = sourceSequence as ICollection<T>;
           orginalSequence = new List<T>(source.Count);
        }
        else
           orginalSequence = new List<T>();
        foreach (T item in sourceSequence)
           orginalSequence.Add(item);
    }
    return new ReverseEnumerator(orginalSequence);
 }

4.使用泛型强制编译期类型推断。

5.确保泛型类型支持可销毁对象。
```
