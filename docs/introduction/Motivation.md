# Motivation

IEnumerable is a library that allow you to create **deeply immutable** collections and query them with a Linq syntax. IEnumerable infact, is born from the idea to bring [Linq](https://msdn.microsoft.com/en-us/library/bb397926.aspx) in JavaScript environment. Linq is a fantastic technique to **query data** and JavaScript cannot haven't it. In addition, we want to maintain the advantages of [immutable Js](https://facebook.github.io/immutable-js/) and improve them. In IEnumerable, not only the collection is immutable but also it's content. Every method will return a new Enumerable a new copy of it's content.
IEnumerable should not be confused with [Rx](http://reactivex.io/) due to its syntax, IEnumerable and Rx are two different things that achieve different purposes. [Here](http://stackoverflow.com/questions/17082255/when-to-use-ienumerable-vs-iobservable) is a interesting question about that.