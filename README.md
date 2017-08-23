This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Groove API SDK for CSharp
Integrate the [Groove API](https://docs.microsoft.com/en-us/groove/api-overview) into your C# project!

The Groove API SDK is built as a Portable Class Library and targets the following frameworks:
* .NET 4.5
* .NET for Windows Store apps
* Windows Phone 8.1 and higher

## Running the sample application
You will need to associate the application with your Microsoft Developer Center account.
Go to the [Microsoft Developer Center](https://developer.microsoft.com/en-us/dashboard/apps/) and create a new application if you don't already have one. The name you choose will be reserved for your application during development.

Then, copy the Package.appxmanifest file (under /samples) at the root of the GrooveApiUniversalSamples project (/samples/UniversalApplication) 

Finally, in Visual Studio 2015/2017, you will need to associate your application to the one reserved on the Microsoft Developer Center. To do that, simply right-click on your project and select "Store -> Associate App with the Store...", select your application in the drop-down and follow the steps.