# FiddlerToJmeter-Net-Core
Create Fiddler Extension Using .NET Core (Visual Studio)


To create a project called JMeterExporterExtension we can run the following commands (.NET Core has to be installed):


1. mkdir JMeterExporterExtension
2. cd JMeterExporterExtension
3. dotnet new sln
4. dotnet new classlib -o JMeterExporterExtension
5. dotnet sln add JMeterExporterExtension

Post this copy the class files in the "JMeterExporterExtension" folder and edit your .csproj file with the uploaded .csproj file and then execute this command - 

6. dotnet build

Now run the tool fiddler and see the extension loaded. The extension gets copied to Documents\Fiddler2\Scripts\ folder.
