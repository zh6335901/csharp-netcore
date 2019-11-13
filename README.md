# OpenTracing instrumentation for .NET
This repository fork from [opentracing-contrib/csharp-netcore](https://github.com/opentracing-contrib/csharp-netcore)

And I just do two things for extend purpose:
1. Change the project type to .netstandard2.0
2. Make DiagnosticObserverListener public, In order to someone can easily extend this library.

Install from nuget: `dotnet add package OpenTracing.Contrib.Unofficial.NetCore`

# Why doesn't the original repository author do above?
You can see the issues:
1. [Unable to install into .netstandard 2.0 library](https://github.com/opentracing-contrib/csharp-netcore/issues/12)
2. [How to extend based on OpenTracing.Contrib.NetCore?](https://github.com/opentracing-contrib/csharp-netcore/issues/13)
