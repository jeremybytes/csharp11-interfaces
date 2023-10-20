Catching up with C# Interfaces
-------------------
C# 8 brought new features to interfaces, including default implementation, access modifiers, and static members. Then in C# 11, we got static abstract members. We'll look at these features, and see where they are useful and where they should be avoided. The world of interfaces has changed; the line between interfaces and abstract classes has blurred; and C# now has multiple inheritance (sort of). With some practical tips, "gotchas", and plenty of examples, we'll see how to use these features effectively (and safely) in our code.

This repository contains slides and code samples for a live presentation. Details of the various topics can be found in the accompanying articles.  

**Articles:**  
* [Abstract Classes vs. Interfaces in C# - What You Know is Probably Wrong](https://jeremybytes.blogspot.com/2020/10/abstract-classes-vs-interfaces-in-c.html)  
* [A Closer Look at C# 8 Interfaces](https://jeremybytes.blogspot.com/2019/09/a-closer-look-at-c-8-interfaces.html)  
* [Properties and Default Implementation](https://jeremybytes.blogspot.com/2019/09/c-8-interfaces-properties-and-default.html)  
* [Dangerous Assumptions in Default Implementation](https://jeremybytes.blogspot.com/2019/09/c-8-interfaces-dangerous-assumptions-in.html)  
* ["dynamic" and Default Implementation](https://jeremybytes.blogspot.com/2019/09/c-8-interfaces-dynamic-and-default.html)  
* [Unit Testing Default Implementation](https://jeremybytes.blogspot.com/2019/09/c-8-interfaces-unit-testing-default.html)  
* [Public, Private, and Protected Members](https://jeremybytes.blogspot.com/2019/11/c-8-interfaces-public-private-and.html)  
* [Static Members](https://jeremybytes.blogspot.com/2019/12/c-8-interfaces-static-members.html)  
* [Static Main -- Why Not?](https://jeremybytes.blogspot.com/2019/12/c-8-interfaces-static-main-why-not.html)  

**Microsoft Docs Samples**
* [Tutorial: Update interfaces with default interface methods in C# 8.0](https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/default-interface-methods-versions)
* [Tutorial: Mix functionality in when creating classes using interfaces with default interface methods](https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/mixins-with-default-interface-methods)  

**Additional Topics**  
* [IEnumerable, ISaveable, IDontGetIt: Understanding C# Interfaces](http://www.jeremybytes.com/Demos.aspx#INT)  
* [Explicit Interface Implementation](https://jeremybytes.blogspot.com/2012/03/explicit-interface-implementation.html)  
* [Updating an Interface Implementation](https://jeremybytes.blogspot.com/2012/03/updating-interface-implementation.html) (prior to C# 8)  
* [Misusing C#: Multiple Main() Methods](https://jeremybytes.blogspot.com/2020/06/misusing-c-multiple-main-methods.html)  
* [-main (C# Compiler Options)](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/compiler-options/main-compiler-option) (how to specify the entry point if you have multiple "static Main()" methods in an application)
