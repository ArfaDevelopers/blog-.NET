# Blog
Blog is a self-hosted open source publishing platform written in ASP.NET and Blazor WebAssembly. It can be used to quickly and easily set up a lightweight, but fully functional personal or group blog.


# Installation
Download .NET 7.0 SDK. Choose to install the system version on your host. Download Nodejs 14 and above and install it on your host. For linux you can use the package management tool

Navigate to the project root directory, run ./publish.cmd on the command line in widnows, run sh ./publish.sh on the command line in linux.

When the command execution is complete and there are no errors, you will see the dist folder in the project root directory, which is the application after publishing. You can copy it to run anywhere.

Then you can open localhost:5000 with your browser

Done, enjoy.

# Docker build
First of all, please make sure that docker, docker-compose has been installed in your host.

Navigate to the project root directory Run the docker-compose up -d  command, wait a while ...

Then you can open localhost:8080 with your browser

Done, enjoy.

# Versions before 3.0
Steps to install compiled application on the server for a self-hosting:

.NET Core Runtime (currently 7.0) must be installed on your host server.

Download the latest release.

Unzip and copy to your host server.

Restart your website.

Open your website and only the first time you'll be redirected to the register page.

example.com/admin/register/

Register, and then log in.

example.com/admin/login/

Done, enjoy.

# Development
If you want to customize the Blog, or contribute:

Download and Install .NET SDK.

Download and Install NodeJs.

Download, fork, or clone the repository.

Open the project with your favorite IDE (VS Code, Visual Studio, Atom, etc).

Run the app with your IDE

Then you can open localhost:5000 with your browser
