# NewsletterSubscription
ASP MVC newsletter application which allows an user to register with the email address, ask how he did meet you and the reason why is subscribing. All this info it's saved on a DB.

Also has some AJAX code to check wheter email is already registered or not; shows succes, info or error messages, and some frontend / backend validation.


## **How to use it?**
You'll just need to check you have installed SQL Server in your computer, check Web.config file, and DB will be created automatically based upon the model when you run the application.


### Issue when compiling?
If you're getting error "could not find \bin\roslyn\csc.exe", please check this:
https://blogs.msdn.microsoft.com/jpsanders/2018/02/22/error-could-not-find-a-part-of-the-path-esitesroot0binroslyncsc-exe/

Basically, this is a problem with recent versions of .NET compiler. You just need to reinstall latest stable version (1.0.8) of Microsoft.CodeDom.Providers.DotNetCompilerPlatform  at NuGet packages, and application will compile as it should :)
