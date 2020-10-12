Visual Studio Magazine
======================
https://visualstudiomagazine.com/home.aspx

Micosoft Documentation
======================
https://docs.microsoft.com/en-us/
	AZURE

	.NET
	https://dotnet.microsoft.com/
		https://dotnet.microsoft.com/learn
			https://dotnet.microsoft.com/learn/videos

	.NET Architecture Guides
	https://dotnet.microsoft.com/learn/dotnet/architecture-

	Visual Studio product family
	https://docs.microsoft.com/en-us/visualstudio/?view=vs-2019

		Visual Studio Subscriptions
		https://docs.microsoft.com/en-us/visualstudio/subscriptions/

		Visual Studio App Center
		https://docs.microsoft.com/en-us/appcenter/
		https://docs.microsoft.com/en-us/appcenter/build/troubleshooting/code-repos

			Building
			https://docs.microsoft.com/en-us/appcenter/build/
				https://docs.microsoft.com/en-us/appcenter/build/troubleshooting/
					https://docs.microsoft.com/en-us/appcenter/build/troubleshooting/build-failed

		Visual Studio
		https://docs.microsoft.com/en-us/visualstudio/windows/?view=vs-2019&preserve-view=true

			Templates & Extensions
			https://docs.microsoft.com/en-us/visualstudio/ide/finding-and-using-visual-studio-extensions?view=vs-2019
			https://docs.microsoft.com/en-us/visualstudio/ide/how-to-locate-and-organize-project-and-item-templates?view=vs-2019
			%USERPROFILE%\Documents\Visual Studio 2019\Templates\ProjectTemplates
			%USERPROFILE%\Documents\Visual Studio 2019\Templates\ItemTemplates
			https://docs.microsoft.com/en-us/visualstudio/ide/creating-project-and-item-templates?view=vs-2019
			https://docs.microsoft.com/en-us/visualstudio/ide/how-to-create-project-templates?view=vs-2019
			https://docs.microsoft.com/en-us/visualstudio/ide/how-to-create-item-templates?view=vs-2019

		Visual Studio Code
		https://code.visualstudio.com/docs
		https://www.c-sharpcorner.com/article/running-a-visual-studio-2019-solution-in-visual-studio-code/

		Visual Studio Codespaces
		https://docs.microsoft.com/en-us/visualstudio/codespaces/overview/what-is-vsonline

			How-to guides
			https://docs.microsoft.com/en-us/visualstudio/codespaces/how-to/vscode
			https://docs.microsoft.com/en-us/visualstudio/codespaces/how-to/browser

Architecture
============
	Architecting Modern Web Applications with ASP.NET Core and Microsoft Azure e-book
	(using eShopOnWeb)
	https://ardalis.com/architecture-ebook/
	https://dotnet.microsoft.com/download/e-book/aspnet/pdf

Clean Architecture
==================
https://devintxcontent.blob.core.windows.net/showcontent/Speaker%20Presentations%20Fall%202017/Clean%20Architecture%20with%20ASP.NET%20Core.pdf
	
	Source
	https://github.com/ardalis/CleanArchitecture

Microservices
=============
https://dotnet.microsoft.com/download/e-book/microservices-architecture/pdf

Desktop Docker
==============
https://hub.docker.com/editions/community/docker-ce-desktop-windows

Error: Visual Studio Container Tools requires Docker to be running
https://aka.ms/DockerToolsTroubleshooting

Hardware assisted virtualization and data execution protection must be enabled in the BIOS
https://dotnetthoughts.net/hardware-assisted-virtualization-and-data-execution-protection-must-be-enabled/

	>dism.exe /Online /Enable-Feature:Microsoft-Hyper-V /All
	>bcdedit /set hypervisorlaunchtype auto

Docker support in Visual Studio
https://docs.microsoft.com/en-us/visualstudio/containers/overview?view=vs-2019

Hyper-V
=======
https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v
	
GIT
===
Introduction - Hello Worl 
https://guides.github.com/activities/hello-world/

	https://yourbrainoncomputers.com/getting-started-with-git-and-13-essential-things-to-know/
	Connecting a local repo to a remote repo (original or other one (yours) when copying 

	- create local repo from sourec remote one via url
	- open cmd line & cd to local repo
		>git remote add origin https://github.com/steven-p-sutton/eShopOnContainers.git
		>git branch -M main  
	- now you can sync your local repo to your new remote one and not use the orginal source repo
		>git push -u origin master  

	https://www.toolsqa.com/git/local-repository-remote-repository/

How to create new repo & populate with new Visual Studio project
https://yourbrainoncomputers.com/using-git-with-visual-studio-2019-the-ultimate-guide/#Create_New_Git_Repository

	- Open VS & with Open page select "continue with code" option beneath main option panels
	- File-> New-> Repository
	- File-> New-> Project
-	- Team Explorer-> Changes-> Stage
	- Team Explorer-> Changes-> Commit Staged
	- Team Explorer-> Sync-> Publish To GitHub -> Publish

GitHub Onboarding and Introduction
https://gist.github.com/jbjonesjr/d4854be10e2df5e2f91c4b4928d8ec68
https://user-images.githubusercontent.com/16810959/33858575-27f42030-de9e-11e7-96ac-9fbaf24a142b.png

How I Organize my GitHub Repositories
https://andreicioara.com/how-i-organize-my-github-repositories-ce877db2e8b6

Managing Teams and Organizations in GitHub
https://stackify.com/managing-teams-github/
	
eShopOnWeb
==========
	Characteristics of Modern Web Applications
	(eShopOnWeb) - Simple using desktop containers
	https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/modern-web-applications-characteristics
	
	Architecting Modern Web Applications with ASP.NET Core and Microsoft Azure e-book
	https://ardalis.com/architecture-ebook/
	https://dotnet.microsoft.com/download/e-book/aspnet/pdf
	
	Source
	https://github.com/dotnet-architecture/eShopOnWeb
	
	Desktop Docker
	https://hub.docker.com/editions/community/docker-ce-desktop-windows

eShopOnContainers
=================
	Introducing eShopOnContainers reference app
	(eShopOnContainers) - Full Azure containers 
	https://docs.microsoft.com/en-us/dotnet/architecture/cloud-native/introduce-eshoponcontainers-reference-app

	.NET Microservices: Architecture for Containerized .NET Applications
	https://dotnet.microsoft.com/download/e-book/microservices-architecture/pdf

	Source
	https://github.com/dotnet-architecture/eShopOnContainers

	Microservices architecture e-book
	https://dotnet.microsoft.com/download/e-book/microservices-architecture/pdf
















