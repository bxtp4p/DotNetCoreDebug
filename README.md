# DotNetCoreDebug
Example for remote debugging .NET Core app running in a Docker container.

Using SSH to remote debug an ASP.NET core app. See the [Dockerfile-remotedebug](https://github.com/bxtp4p/DotNetCoreDebug/blob/master/DotNetCoreDebug/Dockerfile-remotedebug).


The key piece is to install SSH server. Then you can use Visual Studio's "Debug > Attach to Process" and select "SSH" to debug.


Also using Supervisor to run SSH as well as the .NET core app in the background together in the container.
