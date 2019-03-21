# A Comparison Matrix of MVVM Frameworks for Xamarin

|Feature|MVVMCross|FreshMVVM|Prism|MVVMLight|
|---------|---------|---------|-----|---------|
|Supports Xamarin Forms|:white_check_mark:|:white_check_mark:|:white_check_mark:|:white_check_mark:|
|Supports Xamarin Native|:white_check_mark:|:no_entry:|:no_entry:|:white_check_mark:|
|Active Development|:white_check_mark:|:no_entry:|:no_entry:|:no_entry:|
|Up to date Samples|:white_check_mark:|:white_check_mark:|:white_check_mark:|:no_entry:|
|.NET Foundation|:white_check_mark:|:no_entry:|:white_check_mark:|:no_entry:|
|.NET Standard Support|:white_check_mark:|:no_entry:|:no_entry:|:no_entry:|
|Up to date documentation|:white_check_mark:|:white_check_mark:|:no_entry:|:no_entry:|
|Built in IOC Container|:white_check_mark:|:white_check_mark:|:white_check_mark:|:white_check_mark:|
|Fast IOC Container|:white_check_mark:|:white_check_mark:|:no_entry:|:white_check_mark:|
|View-to-ViewModel auto wiring|:white_check_mark:|:white_check_mark:|:white_check_mark:|:no_entry:|
|Navigation Service|:white_check_mark:|:white_check_mark:|:white_check_mark:|:white_check_mark:|
|ViewModel-to-ViewModel Navigation|:white_check_mark:|:no_entry:|:no_entry:|:no_entry:|
|ViewModel Parameters|:white_check_mark:|:white_check_mark:|:white_check_mark:|:white_check_mark:|
|View Lifecycle|:white_check_mark:|:white_check_mark:|:no_entry:|:no_entry:|
|Event Aggregator|:white_check_mark:|:no_entry:|:white_check_mark:|:no_entry:|


## Summary

MVVMCross is the most feature complete and suitable for most applications. It has a very large community support base from a contributions and troubleshooting point of view. 

Prism is suitable for large applications, but has some limitations, one of which being containers that are slow and the use of magic strings for Navigations

MVVMLight and Caliburn Micro only have 1 contributor and sutable for light applications. Documenation is not that good or up to date and doesn't appear to support .NET Standard. 




## Resources

### Framework Comparisons
- [Adam Pedley on Xamarin Help](https://xamarinhelp.com/use-xamarin-forms-mvvm-framework/)

### IOC Container Performance Comparisons

- [Daniel Palme on GitHub](https://github.com/danielpalme/IocPerformance)
- [Adam Pedley on Xamarin Help](https://xamarinhelp.com/ioc-container-performance/)

### Documentation

- [MVVMCross](https://www.mvvmcross.com/documentation/)
- [FreshMVVM](https://github.com/rid00z/FreshMvvm)
- [Prism](http://prismlibrary.github.io/docs/)
- [MVVMLight](https://galasoft.ch/posts/2014/07/using-xamarin-forms-with-mvvmlight)

### Samples

- MVVMCross
  - [Playground](https://github.com/MvvmCross/MvvmCross/tree/develop/Projects/Playground)
  - [Samples](https://github.com/MvvmCross/MvvmCross-Samples)
- [FreshMVVM](https://github.com/rid00z/FreshMvvm/tree/master/samples)
- [Prism](https://github.com/PrismLibrary/Prism-Samples-Forms.git)
- [MVVMLight](https://github.com/lbugnion/sample-crossplatform-flowers.git)


