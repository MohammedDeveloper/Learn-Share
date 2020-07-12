# .Net programming - Useful Links

- CLR, CTS, CLS:
    - https://www.c-sharpcorner.com/blogs/what-are-cts-and-cls-in-net#:~:text=NET%20each%20language%20is%20converted,is%20language%20specification%20of%20CLR.&text=Common%20Type%20System%20(CTS)%20describes,and%20managed%20in%20the%20runtime.
    - System.Object - base class for all classes

- .Net runtime
    - https://stackoverflow.com/questions/47733014/whats-the-difference-between-sdk-and-runtime-in-net-core

-   Process ==> Thread ==> AppDomain ==> Assemblies
    - https://stackoverflow.com/questions/733868/difference-between-appdomain-assembly-process-and-a-thread#:~:text=A%20process%20is%20created%20by,The%20application's%20executing%20assembly%20(the%20.

- Remoting or Web Services
    - https://stackoverflow.com/questions/1426249/what-is-the-difference-between-web-service-and-remoting#:~:text=Web%20services%20work%20in%20a,same%20client%20and%20support%20callbacks.

- Reflection:
    - § https://www.tutorialspoint.com/csharp/csharp_reflection.htm

- .Net Architecture
    - https://www.google.com/search?q=.net+architecture&rlz=1C1GCEU_enUS891US891&tbm=isch&source=iu&ictx=1&fir=2mpdx9j6Rl0YCM%253A%252CJE3ymWbHY6zSvM%252C_&vet=1&usg=AI4_-kR_zlubI_dTsfJ7kzK76Ip0WC5dMA&sa=X&ved=2ahUKEwjita-Oo5PqAhUkU98KHe9KBssQ_h0wAHoECAQQBA&biw=1920&bih=969#imgrc=2mpdx9j6Rl0YCM:
		
- .Net Compilation: C# ==> MSIL (dll/exe) ==> JIT ==> Machine Code
    - https://www.google.com/search?q=.net+compilation&rlz=1C1GCEU_enUS891US891&oq=.net+compilation&aqs=chrome..69i57j0l7.4552j0j7&sourceid=chrome&ie=UTF-8#kpvalbx=_s4PvXqyUN4Ss_QbAo6bYDg38

- Diff b/w mutable (String) and immutable (StringBuilder)
    - https://www.c-sharpcorner.com/article/mutable-and-immutable-class-in-c-sharp/
    - Append, AppendFormat, Remove, Insert, Replace

- Abstract vs Interface
    - https://www.geeksforgeeks.org/difference-between-abstract-class-and-interface-in-c-sharp/

- Base C# - super
    - https://www.tutorialspoint.com/equivalent-of-java-super-keyword-in-chash

- Static usage
    - https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/static-classes-and-static-class-members

- Access Modifiers
    - https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers

- Struct (value type). Class is reference type
    - https://www.c-sharpcorner.com/blogs/difference-between-struct-and-class-in-c-sharp#:~:text=C%23%20struct%20vs%20class.&text=Structs%20are%20value%20types%20while,the%20base%20of%20a%20class.

- Sealed, Concrete
    - https://www.c-sharpcorner.com/article/sealed-class-in-C-Sharp/

- Readonly vs const vs Static readonly
    - https://stackoverflow.com/questions/55984/what-is-the-difference-between-const-and-readonly-in-c

- enum 
    - https://www.tutorialsteacher.com/csharp/csharp-enum

- Extension Methods
    - https://www.tutorialspoint.com/extension-methods-in-chash#:~:text=Extension%20methods%20are%20static%20methods,extension%20method%20we%20have%20created.

- Nullable
    - https://www.tutorialsteacher.com/csharp/csharp-nullable-types

- Primitive datatypes
    - https://medium.com/omarelgabrys-blog/primitive-data-types-in-c-vs-java-5b8a597eef05#:~:text=In%20C%23%2C,to%20build%20other%20data%20types.
    - Value typed
    - Reference types - dynamic, object, string, delegates
        - https://www.tutorialsteacher.com/csharp/csharp-value-type-and-reference-type
		- http://net-informations.com/faq/qk/dynamic.htm
		- http://net-informations.com/faq/general/valuetype-referencetype.htm
		- https://www.c-sharpcorner.com/article/what-does-var-mean-in-c-sharp/
				
    - Boxing and unboxing    
        - https://techdifferences.com/difference-between-boxing-and-unboxing-in-c-sharp.html

- Generics (reusability)
	- https://www.tutorialsteacher.com/csharp/csharp-generics
    - https://www.tutorialsteacher.com/csharp/constraints-in-generic-csharp

- Anonymous methods
	- https://www.tutorialsteacher.com/csharp/csharp-anonymous-method
    - https://www.tutorialsteacher.com/linq/linq-lambda-expression

- Delegates
    - https://www.tutorialsteacher.com/csharp/csharp-delegates
    - https://www.codeproject.com/Articles/772792/Delegates-and-Types-of-Delegates-in-Csharp#Func

- Finalize vs Dispose vs Destructor
	- https://stackoverflow.com/questions/13988334/difference-between-destructor-dispose-and-finalize-method#:~:text=Destructor%20implicitly%20calls%20the%20Finalize,that%20implement%20the%20IDisposable%20interface.&text=The%20destructor%20implicitly%20calls%20Finalize%20on%20the%20base%20class%20of%20the%20object.
    - https://social.msdn.microsoft.com/Forums/vstudio/en-US/34d2416b-abb1-4351-a797-33cda12d7b8b/destructor-vs-dispose-vs-finalize?forum=csharpgeneral

- Exception handling - Try, catch, finally (will not have return statement)
    - https://www.tutorialsteacher.com/csharp/csharp-exception

- [Serializable] keyword
    - https://stackoverflow.com/questions/5877808/what-is-serializable-and-when-should-i-use-it

- Task, Async, Await
    - https://stackoverflow.com/questions/13429129/task-vs-thread-differences
    - https://codewithshadman.com/csharp-task/#csharp-task-example
	- https://www.dotnetperls.com/task
	- ContinueWith, TaskContinuationOptions
	- Run
	- Thread.Sleep vs Task.Delay
	- Cancel - CancellationTokenSource
	    - IsCancellationRequested
	- await Task.WhenAll(abcTask, efgTask);	var abc = abcTask.GetAwaiter().GetResult().Result; var efg = efgTask.GetAwaiter().GetResult().Result;

- Create Custom Exception:
    - https://www.tutorialsteacher.com/csharp/custom-exception-csharp#:~:text=Custom%20Exception%20Type%20in%20C%23&text=However%2C%20you%20often%20like%20to,framework%20includes%20ApplicationException%20class%20since%20.
		
- Cookie
    - HttpOnly
    - Domain
    - Secure 
    - Expires
    - HttpCookie
    - HttpContext.Current.Response/Request.Cookies.Add/Remove
	- https://www.c-sharpcorner.com/uploadfile/annathurai/cookies-in-Asp-Net/
    - https://www.ryadel.com/en/asp-net-cookie-read-write-delete-c-sharp-tutorial-guide-how-to/


- Logging:
	- https://stackify.com/log4net-guide-dotnet-logging/ | https://www.c-sharpcorner.com/UploadFile/858292/exception-logging-in-mvc-using-elmah/
	- https://www.c-sharpcorner.com/article/introduction-to-elmah-in-mvc/
	- New Relic - NewRelicAgent.Api
	
- Caching
    - OutputCache
	- https://docs.microsoft.com/en-us/aspnet/mvc/overview/older-versions-1/controllers-and-routing/improving-performance-with-output-caching-cs
    - StackExchange.Redis
    - HSTS - setting response headers to prevent iframe attacks

- Unit/Integration Testing
    - Moq. Act and Assert









