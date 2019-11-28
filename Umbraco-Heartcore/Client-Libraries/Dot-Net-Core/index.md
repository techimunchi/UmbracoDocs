---
versionFrom: 8.0.0
---

# .NET Core Client library

In this article you can learn more about the .NET Core client library that you can clone and use with your Umbraco Heartcore projects.

It is a library for .NET Core and is based on NetStandard 2.0. This means that it can be used on the most .Net frameworks. A few examples could be UWP, Xamarin.Android, Xamarin.Mac, Desktop .Net 4.6.1 and .NET Core.

## Download and install

The .NET Core library can be found on GitHub: [.NET Core client library for Umbraco Heartcore](https://github.com/umbraco/Umbraco.Headless.Client.Net). 

You can also install it through NuGet:

```
> Install-Package Umbraco.Headless.Client.Net
```

:::note
Please be aware that the minimum NuGet client version requirement has been updated to 2.12 in order to support multiple .NET Standard targets in the NuGet package.
:::

You will get a Visual Studio solution file which references the client library itself (Umbraco.Headless.Client.Net) as well as a test project (Umbraco.Headless.Client.Net.Tests) which uses xUnit for unit and integration tests.

Along with the client library you will also find two samples using the library. We have built an MVC sample and a console sample. Below you will find instructions on how to clone these down and set them up for testing with your own Heartcore project.



## Console Sample
