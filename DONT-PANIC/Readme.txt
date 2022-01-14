Scratch Pad
===========

Python
======
	W3
		https://www.w3schools.com/python/python_examples.asp

	Build a “Smart Blockchain” with Python [DIY]
		https://hackernoon.com/build-a-smart-blockchain-with-python-diy-0qbm3243

		What is Smart Blockchain?
			https://hackernoon.com/what-is-smart-blockchain-4b134275e90f

			The elimination of miners and block producers by using smart contracts
				https://medium.com/swlh/the-elimination-of-miners-and-block-producers-by-using-smart-contracts-58b20e317e9b

			Bitcoin mining; Big little lies
				https://medium.com/swlh/bitcoin-mining-big-little-lies-c6911435aa77

			Smart Blockchain; The rescue of Bitcoin and saving electricity more than 50TWh per year
				https://medium.com/swlh/smart-blockchain-the-rescue-of-bitcoin-and-saving-electricity-more-than-50twh-per-year-c17606976fce

			Smart Blockchain Technology
				https://www.newchains.info/?ref=hackernoon.com	

		Learn Blockchains by Building One
			https://hackernoon.com/learn-blockchains-by-building-one-117428612f46

			What Are Hash Functions
				https://privacycanada.net/hash-functions/what-are-hash-functions/?ref=hackernoon.com

	GIT - https://github.com/SomayyehGholami/Implementing-Smart-Blockchain

	bpsc101.py
	----------
		http://127.0.0.1:5000/chain
		{
			"chain": [
				{
				"index": 1, 
				"previous_hash": "1", 
				"timestamp": 1642118992.0252523, 
				"transactions": []
				}
			], 
			"length": 1
		}

		http://127.0.0.1:5000/mine
		{
			"index": 2, 
			"message": "New Block Forged", 
			"previous_hash": "9d7676f99ca436bcf36f990f6fab5d64fe8667ce9b148bf997b7486d5d9915a0", 
			"transactions": []
		}

		http://127.0.0.1:5000/transactions/new



Flask
	DOCUMENTATION - https://riptutorial.com/Download/flask.pdf
	GIT - https://github.com/pallets/flask

	https://github.com/microsoft/python-sample-vscode-flask-tutorial

	https://code.visualstudio.com/docs/python/tutorial-flask
	- Create new Python Environment
		py -3 -m venv .venv

	- Open VSC & open new env folder

	- Select Python interpreter in new env

	- Update pip in new env
		python -m pip install --upgrade pip

	- Install Flask in new env
		python -m pip install flask

	- Create and edit code to use Flask
		from flask import Flask
		app = Flask(__name__)

		@app.route("/")
		def home():
			return "Hello, Flask!"

	- Run Code to start server in terminal

	- Crl-Click the output url in the trminal window () to open the Flask reponse page showing "Hello, flask!"
		Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

		http://127.0.0.1:5000/Hello/Steve

	- Create dependencies file for exclusion of non-application files in GIT
		pip freeze > requirements.txt

Jinja
	https://jinja.palletsprojects.com/en/3.0.x/

Visual Studio Code
------------------
Install python component 
	Setup VSC to run python with python.exe specified as 'C:\Users\steve\AppData\Local\Programs\Python\Python310'

Install Flask using pip
	python -m pip install --upgrade pip
	python -m pip install flask

Visual Studio
-------------
using Visual Studio Installer

Resources
=========
	RIP (Search by topic)
		https://riptutorial.com/

		Angular
			https://riptutorial.com/angular2
		MOC
			https://riptutorial.com/mockito/topic/4573/mock

	Tutorials Point
		https://www.tutorialspoint.com/csharp/csharp_overview.htm

	InfoWorld
		https://www.infoworld.com/uk/

		Software Developement
			https://www.infoworld.com/uk/category/application-development/

Visual Studio Magazine
======================
https://visualstudiomagazine.com/home.aspx

VS Code
=======
	https://code.visualstudio.com/docs/languages/overview

	Languages
	https://code.visualstudio.com/docs/nodejs/working-with-javascript
	https://code.visualstudio.com/docs/typescript/typescript-tutorial
	https://code.visualstudio.com/docs/nodejs/reactjs-tutorial
	https://code.visualstudio.com/docs/python/python-tutorial

	Debugging
	https://code.visualstudio.com/docs/editor/debugging

	Containers
	https://code.visualstudio.com/docs/containers/overview
	https://code.visualstudio.com/docs/containers/quickstart-aspnet-core

	Azure
	https://code.visualstudio.com/docs/remote/remote-overview
	https://code.visualstudio.com/docs/azure/deployment
	https://code.visualstudio.com/docs/containers/overview
	https://code.visualstudio.com/tryappservice/

Examples
========
	https://docs.microsoft.com/en-us/samples/microsoftdocs/mslearn-azure-sql-fundamentals/update-this-to-unique-url-stub/
	https://github.com/microsoft/vscode
	https://github.com/microsoft/PowerToys
	https://github.com/microsoft/vscode-deploy-azure
	https://github.com/microsoft/vscode-mssql
	https://github.com/microsoft/vscode-npm-scripts
	https://github.com/microsoft/Windows-universal-samples
	https://github.com/microsoft/sql-server-samples
	https://github.com/microsoft/azure-docs

	https://developer.microsoft.com/en-us/windows/samples/

	BuildCast
		Showcases the Microsoft Fluent Design System and UWP capabilities, including ink notes, bookmarks and remote playback.
		https://github.com/Microsoft/BuildCast
	Lunch Scheduler
		See integration with services like Facebook, Microsoft Graph, Bing maps, and Yelp
		https://github.com/Microsoft/Windows-appsample-lunch-scheduler
	Coloring Book
		Demonstrates the versatility of Windows Ink and radial controller features
		https://github.com/Microsoft/Windows-appsample-coloringbook

	UWP Customer Order Database sample
		Demonstrates a working database hosted on Azure, implemented in C# and XAML
		https://github.com/Microsoft/Windows-appsample-customers-orders-database

	Universal Windows Platform (UWP) app samples
		https://github.com/microsoft/Windows-universal-samples

Visual Studio Blend
===================
	https://docs.microsoft.com/en-us/visualstudio/designers/creating-a-ui-by-using-blend-for-visual-studio?view=vs-2015&redirectedfrom=MSDN#:~:text=Blend%20for%20Visual%20Studio%20overview%201%20Tools%20panel.,Objects%20and%20Timeline%20window.%20...%204%20See%20also

.NET 5 (Evolution of .NET Core)
===============================
	https://docs.microsoft.com/en-us/dotnet/core/dotnet-five
	https://devblogs.microsoft.com/dotnet/introducing-net-5/

	Download SDK
	https://dotnet.microsoft.com/download/dotnet/5.0

================================================================================
================================= Documentation ================================ 
================================================================================

Microsoft GitHub Repositories
============================
https://github.com/microsoft

	PhotoLab
	https://github.com/Microsoft/Windows-appsample-photo-lab

	XMAL Controls
	https://github.com/Microsoft/Xaml-Controls-Gallery

	TutorialPoint
	https://www.tutorialspoint.com/tutorialslibrary.htm

	C#
	https://www.tutorialspoint.com/csharp/index.htm

Microsoft Code Samples
======================
	https://docs.microsoft.com/en-us/samples/browse/

Micosoft Documentation
======================
	Top Level
		https://docs.microsoft.com/en-us/
	Technical documentation
		https://docs.microsoft.com/en-us/documentation/
	Learn
		https://docs.microsoft.com/en-us/learn/
	Q&A
		https://docs.microsoft.com/en-us/answers/index.html
	Code Samples
		https://docs.microsoft.com/en-us/samples/browse/
ANGULAR
-------
	Top Level
		https://angular.io/
	Documents
		https://angular.io/docs
	Understanding Angular
		https://angular.io/guide/component-overview
	Developer Guides
		https://angular.io/guide/router
	Tutorials
		https://angular.io/tutorial
	Best Practices
		https://angular.io/guide/security

	Components
		https://angular.io/guide/component-overview
	Services
		https://angular.io/guide/service-worker-intro
	Templates
		https://angular.io/guide/glossary#template

	Node Package Manager (npm)
		https://nodejs.org/en/download/
		$ npm -v

	Node.js
		$ node -v

	CLI Tool
		https://angular.io/cli
		$ npm install -g @angular/cli

	Create new app
		$ ng new my-app

	Git Clone
		(need to install node modules)
		https://www.pluralsight.com/guides/set-up-a-github-project-with-node_module
		$ npm install

	Build & Run (CLI)
		$ cd my-app
		$ ng serve --open
		http://localhost:4200/.

	Build & Run (VS Code)

		Node.JS Cmd
			ng serve 
		VS Code
			Open folder to see project
				ASPCoreAngular -> <AppRoot>\ClientApp
				Node.JS		   -> <AppRoot>
			Check node_modules folder present
			Create launch.json using button on 1st run
				http://localhost:4200/
			Run in Chrome brower button -> click
				http://localhost:4200/
			
	Build & Run (VS 2019)	
		https://www.c-sharpcorner.com/article/creating-an-angular-app-in-visual-studio-2019/

		\Properties\launchSettings.json (IIEXpress)
		   "applicationUrl": "http://localhost:44397;",
		Don't need to start an external CLI
		May take a while fist time running (Chrome)
			TECHNOLOGY
				https://localhost:44397/
			HELLOWORLD
				https://localhost:44316/
			NEWPROJECT
				https://localhost:44321/

	Components
		https://vegibit.com/how-to-create-new-components-in-angular-using-the-cli/
		https://stackoverflow.com/questions/46174863/error-more-than-one-module-matches-use-skip-import-option-to-skip-importing-th
		$ ng g component <name> --module <main>
		$ ng g c Pages --module app

	Services
		$ ng g service <name>
		$ ng g service Page
			
	Tour Of Heroes
		https://angular.io/tutorial#:~:text=This%20Tour%20of%20Heroes%20tutorial%20shows%20you%20how,selected%20hero%27s%20detail%2C%20and%20navigates%20among%20different%20
		
		Run node.js cmd prompt (start menu)

		Create new app
		$ ng new angular-tour-of-heroes

		Build & Run
		$ C:\Users\steve\Documents\Visual Studio Work\TECHNOLOGY\ANGULAR
		$ ng new angular-tour-of-heroes
		$ ng serve --open
		( http://localhost:4200/.)

	Visual Studio Code
		How to create, run and debug Angular app using Visual Studio Code
			https://codeolives.com/2020/02/18/how-to-create-a-new-angular-application-using-angular-cli/
		How To Debug Angular CLI Applications in Visual Studio Code
			https://www.digitalocean.com/community/tutorials/how-to-debug-angular-cli-applications-in-visual-studio-code
		Setting up Visual Studio Code for Angular Development
			https://medium.com/@mandeep1012/setting-up-visual-studio-code-for-angular-development-f8d45c6ae45b
			
			package.json - dependencies
			launch.json - run properties for Chrome browser
			    "url": "http://localhost:4200"

			Debugger for Chrome
			Prettier � Code Formatter
			Angular Language Service
			TS Lint {for typescript} *What is a Linter?*

			Node.JS 
				cms shell started
					$ ng serve

			VS Code Run/Debug
				Add launch.json
					run properties for Chrome browser
					"url": "http://localhost:4200"				

	Visual Studio 2019
		Creating an Angular App in Visual Studio 2019
			https://www.c-sharpcorner.com/article/creating-an-angular-app-in-visual-studio-2019/

			New Project
				Web Core Angular project
			VS Build 
			Node.JS Start Cmd prompt
				cd <root>\TECHNOLOGY\ANGULAR-my-app\ClientApp
				$ ng serve
			VS Debug 

AZURE
-----
	Common Data Model (CDM)
		https://docs.microsoft.com/en-us/common-data-model/
	Data Lake
		https://docs.microsoft.com/en-us/common-data-model/data-lake
	Data Studio (SSMS Alternative)
		https://docs.microsoft.com/en-us/sql/azure-data-studio/what-is-azure-data-studio?view=sql-server-ver15
		https://docs.microsoft.com/en-us/sql/azure-data-studio/insight-widgets?view=sql-server-ver15	
	Graph API
		https://docs.microsoft.com/en-us/azure/active-directory/develop/microsoft-graph-intro
	Identity
		https://docs.microsoft.com/en-us/azure/active-directory/develop/
		https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-overview#:~:text=Microsoft%20identity%20platform%20%28v2.0%29%20overview%201%20Getting%20started.,local%20identities%2C%20see%20the%20Azure%20AD%20B2C%20overview.
	Indight Widgets (Azure Data Studio)
			https://docs.microsoft.com/en-us/sql/azure-data-studio/insight-widgets?view=sql-server-ver15
	Quantum SDK
		https://azure.microsoft.com/en-us/services/quantum/
.NET
----
	https://dotnet.microsoft.com/
		https://dotnet.microsoft.com/learn
			https://dotnet.microsoft.com/learn/video
C#
--
	https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/
	https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/types/
	https://docs.microsoft.com/en-us/dotnet/csharp/walkthroughs

	Abstract (not just classes)
		https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/abstract
	Access Modifiers
		https://dotnettutorials.net/lesson/access-modifiers-interview-questions-answers-csharp/#:~:text=What%20are%20Access%20Modifiers%20in%20C%23%3F%201%20Public%3A,or%20in%20a%20derived%20class.%20More%20items...%20
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers
	Arrays
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/
	Assert
		https://docs.microsoft.com/en-us/dotnet/api/system.diagnostics.debug.assert?view=net-5.0
		https://www.educba.com/assert-in-c-sharp/
	Async / Await (see Task)
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/
	Class
		https://www.tutlane.com/tutorial/csharp/csharp-classes-and-objects-with-examples
		https://stackoverflow.com/questions/16363753/get-instance-name-c-sharp
		https://www.tutorialspoint.com/what-is-the-difference-between-virtual-and-abstract-functions-in-chash

		Abstract - no implementation, derrivable to be sub-classed
			https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/abstract
		Sealed
		Interface - no implemtation, only derrived from, multiple inheritence in derrived class
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/interfaces/
		Override
			https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/override
		Partial
			https://www.tutorialsteacher.com/csharp/csharp-partial-class
		Protected
			https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/protected
		Virtual / Override - implementation that can be overriden if needed
			https://exceptionnotfound.net/csharp-in-simple-terms-10-interfaces-and-abstract-classes/
	Csv
		https://thecodebuzz.com/read-csv-file-in-net-core/
		https://thecodebuzz.com/read-csv-file-in-net-core-textfieldparser/
	Collections
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/collections
	Configuration Files
		https://search.yahoo.com/search?fr=mcafee&type=E211US714G91370&p=Microsoft.Extensions.Configuration%3B
	Console
		https://docs.microsoft.com/en-us/dotnet/api/system.console.out?view=net-5.0
	Constructors
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/how-to-initialize-objects-by-using-an-object-initializer
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/using-constructors
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/constructors#:~:text=%20Constructors%20%28C%23%20Programming%20Guide%29%20%201%20Parameterless,object.%205%20In%20This%20Section.%20%20More%20
	DataTable
		https://docs.microsoft.com/en-us/dotnet/api/system.data.datatable?view=net-5.0
	Dates
		https://www.c-sharpcorner.com/UploadFile/manas1/string-to-datetime-conversion-in-C-Sharp/
	DateTime
		https://www.dotnetperls.com/datetime-now
	Dialog Boxes
		https://prod.liveshare.vsengsaas.visualstudio.com/join?F2151E126AE030174AC02156F688EF381B3B
	Dictionary
		https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.dictionary-2?view=netcore-3.1
	Dynamic
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/types/using-type-dynamic
	Enumerations
		https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/enum
	Exceptions
		https://docs.microsoft.com/en-us/dotnet/standard/exceptions/
		https://docs.microsoft.com/en-us/dotnet/standard/exceptions/best-practices-for-exceptions
		https://docs.microsoft.com/en-us/dotnet/standard/exceptions/how-to-create-user-defined-exceptions
		https://www.telerik.com/blogs/custom-exceptions-in-c#:~:text=Custom%20Exceptions%20in%20C%23%201%20Exception%20Classes%20in,Custom%20Exception.%20...%203%20Using%20Custom%20Exception.%20
		https://stackoverflow.com/questions/3007608/resuming-execution-of-code-after-exception-is-thrown-and-caught
	Expression
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/expression-trees/how-to-execute-expression-trees
	Extension Methods
		https://www.tutorialsteacher.com/csharp/csharp-extension-method
	Files
		FileStream
			https://www.guru99.com/c-sharp-stream.html
			http://zetcode.com/csharp/filestream/#:~:text=The%20FileStream%27s%20Read%20%28%29%20method%20reads%20a%20block,in%20the%20specified%20byte%20array%20into%20a%20string.
		TextStream
		https://csharp.hotexamples.com/examples/-/TextStream/-/php-textstream-class-examples.html
	Generics <T>
		https://www.tutorialspoint.com/csharp/csharp_generics.htm
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/generics/
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/generics/generic-classes
		https://www.tutorialsteacher.com/csharp/csharp-generics
	Integer
		https://www.tutorialsteacher.com/articles/convert-string-to-int
	Interface
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/interfaces/
	#if
		https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/preprocessor-directives/
	IEnumerable
		https://stackoverflow.com/questions/6573069/initializing-ienumerablestring-in-c-sharp
		https://www.dotnetperls.com/ienumerable
	JSON
		https://www.newtonsoft.com/json
		https://www.newtonsoft.com/json/help/html/JsonSchemaParse.htm
		https://www.json.org/example.html
		https://stackoverflow.com/questions/45095063/how-to-deserialize-json-property-to-class-property
		https://stackoverflow.com/questions/59914611/attribute-jsonproperty-works-incorrect-with-net-core-3-1-when-i-use-underscore
	LINQ
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/walkthrough-writing-queries-linq
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/expression-trees/how-to-execute-expression-trees
	Loops
		https://www.w3schools.com/cs/cs_for_loop.asp
		https://csharp.net-tutorials.com/control-structures/loops/
	MOQ
		https://www.codeproject.com/articles/991028/using-moq-for-unit-testing
		https://www.c-sharpcorner.com/article/moq-mocking-framework-with-xunit-net-testing-fr/
		https://medium.com/@aymanabaid7/beginners-guide-to-unit-testing-using-xunit-net-core-and-visual-studio-2019-e2d53ae873e5
	Override
		https://www.bing.com/search?pc=CBHS&ptag=N12017D111320A6577FFFB8D&form=CONBDF&conlogo=CT3210127&q=c%23+override
	#Preprocessor Directives
		https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/preprocessor-directives/
	Properties
		https://www.tutorialspoint.com/csharp/csharp_properties.htm
	Reference Parameters
		https://www.tutorialspoint.com/csharp/csharp_reference_parameters.htm#:~:text=C%23%20-%20Passing%20Parameters%20by%20Reference.%20A%20reference,storage%20location%20is%20not%20created%20for%20these%20parameters.
	Using
		https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/using-statement
	Serialization
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/serialization/
	Stream
		https://www.tutorialsteacher.com/csharp/csharp-stream-io#:~:text=C%23%20-%20Stream.%20C%23%20includes%20following%20standard%20IO,transfer%20bytes%20%28read%2C%20write%2C%20etc.%29%20to%20the%20source.
		https://www.c-sharpcorner.com/uploadfile/prvn_131971/system-io-and-streams-in-C-Sharp/
	String
		https://docs.microsoft.com/en-us/dotnet/api/system.string.format?view=netcore-3.1
		https://developerpublish.com/c-tips-and-tricks-19-repeat-a-character-n-times/
	Task (see Aswait / Async)
		Task-based asynchronous pattern
			https://docs.microsoft.com/en-us/dotnet/standard/asynchronous-programming-patterns/task-based-asynchronous-pattern-tap
		Task asynchronous programming model
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/task-asynchronous-programming-model
		Task<TResult> return type
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/async-return-types
		Cancel a list of tasks
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/cancel-an-async-task-or-a-list-of-tasks
		Process asynchronous tasks as they complete
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/start-multiple-async-tasks-and-process-them-as-they-complete
		Asynchronous file access
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/using-async-for-file-access
		Example - Breakfast (TASK-Breakfast)
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/
		Example - TASK-MulitTask-Output (Steve Own)
	Templates<T>
		https://www.tutorialspoint.com/csharp/csharp_generics.htm
	TextFieldParser
		https://thecodebuzz.com/read-csv-file-in-net-core/
		https://thecodebuzz.com/read-csv-file-in-net-core-textfieldparser/
	Try / Catch
		Sync
		https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/try-catch
		Async
		https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/try-catch#async-method-example
	WriteLine
		https://docs.microsoft.com/en-us/dotnet/api/system.console.writeline?view=net-5.0

	LINQ
	----
		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/

		https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/walkthrough-writing-queries-linq

		Introduction to LINQ Queries 
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/introduction-to-linq-queries
		LINQ and Generic Types
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/linq-and-generic-types
		Basic LINQ Query Operations
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/basic-linq-query-operations
		Data Transformations with LINQ
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/data-transformations-with-linq
		Type Relationships in LINQ Query Operations
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/type-relationships-in-linq-query-operations
		Query Syntax and Method Syntax in LINQ
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/query-syntax-and-method-syntax-in-linq
		C# Features That Support LINQ
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/features-that-support-linq
		Walkthrough: Writing Queries in C#
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/walkthrough-writing-queries-linq
		Standard Query Operators Overview
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/standard-query-operators-overview
		LINQ to Objects
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/linq-to-objects
		LINQ to ADO.NET (Portal Page)
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/linq-to-adonet-portal-page
		Enabling a Data Source for LINQ Querying
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/enabling-a-data-source-for-linq-querying1
		Visual Studio IDE and Tools Support for LINQ
			https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/visual-studio-ide-and-tools-support-for-linq
		Work with Language-Integrated Query (LINQ)
			https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/working-with-linq

	MOQ
	---
		https://www.codeproject.com/articles/991028/using-moq-for-unit-testing
		https://www.c-sharpcorner.com/article/moq-mocking-framework-with-xunit-net-testing-fr/

	PYTHON
	------
		https://www.w3schools.com/python/default.asp

		Pip
			https://www.w3schools.com/python/python_pip.asp
	
	PL-SQL
	------

	T-SQL
	-----
		https://www.tutorialspoint.com/t_sql/t_sql_quick_guide.htm
		https://www.tutorialspoint.com/t_sql/t_sql_insert_statement.htm
		https://docs.microsoft.com/en-us/sql/t-sql/data-types/decimal-and-numeric-transact-sql?view=sql-server-ver15
		https://stackoverflow.com/questions/17274276/how-to-generate-and-manually-insert-a-uniqueidentifier-in-sql-server
		https://stackoverflow.com/questions/12957635/sql-query-to-insert-datetime-in-sql-server
		https://docs.microsoft.com/en-us/sql/t-sql/functions/getdate-transact-sql?view=sql-server-ver15
		https://www.tutorialspoint.com/t_sql/t_sql_stored_procedures.htm
		https://docs.microsoft.com/en-us/sql/relational-databases/stored-procedures/create-a-stored-procedure?view=sql-server-ver15
		https://docs.microsoft.com/en-us/sql/relational-databases/tables/create-foreign-key-relationships?view=sql-server-ver15
		https://docs.microsoft.com/en-us/sql/t-sql/functions/isnull-transact-sql?view=sql-server-ver15
		https://social.msdn.microsoft.com/forums/sqlserver/en-US/99cba7cf-f095-4a77-95d2-8480c8da17c6/nulls-in-a-uniqueidentifier-column
		https://www.sqlteam.com/articles/writing-outer-joins-in-t-sql#:~:text=Writing%20Outer%20Joins%20in%20T-SQL%201%20Outer%20Join,query%2C%20things%20get%20a%20bit%20more%20complicated.%20
		https://stackoverflow.com/questions/44299292/best-way-to-convert-string-to-datetimeoffset
		https://stackoverflow.com/questions/12957635/sql-query-to-insert-datetime-in-sql-server
		https://docs.microsoft.com/en-us/sql/t-sql/statements/alter-login-transact-sql?view=sql-server-ver15
		https://docs.microsoft.com/en-us/sql/t-sql/statements/create-login-transact-sql?view=sql-server-ver15
		https://docs.microsoft.com/en-us/sql/relational-databases/security/authentication-access/getting-started-with-database-engine-permissions?view=sql-server-ver15
		https://docs.microsoft.com/en-us/sql/relational-databases/security/authentication-access/create-a-login?view=sql-server-ver15
		https://docs.microsoft.com/en-us/dotnet/framework/data/adonet/connection-string-syntax
	TypeScript
	----------
		https://javascript.info/
		https://www.w3schools.com/js/DEFAULT.asp
		array
			https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/of
		boolean
			https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Equality
		class

		export
			https://javascript.info/import-export
		for
			https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of
		import
			https://javascript.info/import-export
			https://appdividend.com/2019/01/23/javascript-import-statement-tutorial-with-example/
		initializer
			https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer
		string
			https://www.tutorialsteacher.com/typescript/typescript-string
	MS SQL (SSMS)
	-------------
		https://docs.microsoft.com/en-us/sql/sql-server/tutorials-for-sql-server-2016?view=sql-server-ver15
		https://support.esri.com/en/technical-article/000009958
	Azure Data Studio (SSMS Alternative)
	------------------------------------
		https://docs.microsoft.com/en-us/sql/azure-data-studio/what-is-azure-data-studio?view=sql-server-ver15
		https://docs.microsoft.com/en-us/sql/azure-data-studio/insight-widgets?view=sql-server-ver15
	Q#
	---
		User Guide
			https://docs.microsoft.com/en-us/quantum/user-guide/

	.NET Architecture Guides
	------------------------
		https://dotnet.microsoft.com/learn/dotnet/architecture

	Platforms
		https://docs.microsoft.com/en-us/windows/apps/desktop/choose-your-platform

	Get started with Windows 10 apps
		https://docs.microsoft.com/en-us/windows/uwp/get-started/

	Fluent Design
		https://docs.microsoft.com/en-us/windows/uwp/design/

	MSIX
		https://docs.microsoft.com/en-us/windows/msix/

	XMAL Designer
		https://docs.microsoft.com/en-us/visualstudio/xaml-tools/?view=vs-2019
		https://docs.microsoft.com/en-us/visualstudio/xaml-tools/creating-a-ui-by-using-xaml-designer-in-visual-studio?view=vs-2019

	XUnit
		https://xunit.net/docs/getting-started/netfx/visual-studio
		https://medium.com/@aymanabaid7/beginners-guide-to-unit-testing-using-xunit-net-core-and-visual-studio-2019-e2d53ae873e5
		https://www.c-sharpcorner.com/article/moq-mocking-framework-with-xunit-net-testing-fr/
		https://hamidmosalla.com/2017/02/25/xunit-theory-working-with-inlinedata-memberdata-classdata/
		https://peterdaugaardrasmussen.com/2020/09/09/xunit-assert-that-a-call-throws-an-exception/
		https://hadihariri.com/2008/10/17/testing-exceptions-with-xunit/

	UWP (Windows 10 Apps)
	https://docs.microsoft.com/en-us/windows/uwp/get-started/

		https://docs.microsoft.com/en-us/windows/uwp/
		https://docs.microsoft.com/en-us/windows/uwp/get-started/universal-application-platform-guide
		https://docs.microsoft.com/en-us/windows/uwp/get-started/get-app-samples

		Develop UWP Apps
			https://docs.microsoft.com/en-us/windows/uwp/develop/
		Design basics for Windows apps
			https://docs.microsoft.com/en-us/windows/uwp/design/basics/
		Universal Windows Platform (UWP) app samples
			https://github.com/microsoft/Windows-universal-samples
		HelloWorld 1
			https://docs.microsoft.com/en-us/visualstudio/get-started/csharp/tutorial-uwp?view=vs-2019
			https://stackoverflow.com/questions/34743817/the-button-is-not-visible
		HelloWorld 2
			https://docs.microsoft.com/en-us/windows/uwp/get-started/create-a-hello-world-app-xaml-universal
		BuildCast
			Showcases the Microsoft Fluent Design System and UWP capabilities, including ink notes, bookmarks and remote playback.
			https://github.com/Microsoft/BuildCast
		Lunch Scheduler
			See integration with services like Facebook, Microsoft Graph, Bing maps, and Yelp
			https://github.com/Microsoft/Windows-appsample-lunch-scheduler
		Coloring Book
			Demonstrates the versatility of Windows Ink and radial controller features
			https://github.com/Microsoft/Windows-appsample-coloringbook
		UWP Customer Order Database sample
			Demonstrates a working database hosted on Azure, implemented in C# and XAML
			https://github.com/Microsoft/Windows-appsample-customers-orders-database
		PhotoLab 
			PhotoLab is the example used in the bigger respouce for UWP with the starting point here:
				https://docs.microsoft.com/en-us/windows/uwp/design/

			Tutorial: Create a user interface - PhotoLab 
				https://docs.microsoft.com/en-us/windows/uwp/design/basics/xaml-basics-ui

				Part 0: Get the starter code from GitHub
					https://github.com/Microsoft/Windows-appsample-photo-lab
				Part 1: Add a TextBlock control by using XAML Designer
				Part 2: Add a GridView control by using the XAML editor
					https://docs.microsoft.com/en-us/uwp/api/windows.ui.xaml.controls.relativepanel?view=winrt-19041
				Part 3: Add a DataTemplate object to display your data
					https://docs.microsoft.com/en-us/uwp/api/windows.ui.xaml.datatemplate?view=winrt-19041
					https://docs.microsoft.com/en-us/windows/uwp/design/controls-and-patterns/item-containers-templates
					https://docs.microsoft.com/en-us/uwp/api/microsoft.ui.xaml.controls.ratingcontrol?view=winui-2.4
				Part 4: Modify the item container style
				Part 5: Apply some final adjustments to the layout
					https://docs.microsoft.com/en-us/windows/uwp/design/layout/alignment-margin-padding

			Tutorial: Create data bindings - PhotoLab 
				https://docs.microsoft.com/en-us/windows/uwp/data-binding/xaml-basics-data-binding

				Part 1: Replace the placeholders
					- Replace the placeholders with one-time bindings  
				Part 2: Use binding to connect the gallery UI to the images
					- Bind the main GridView control to the Images collection
					- Add a delete button
				Part 3: Set up the zoom slider
					- Bind the image data template to the zoom slider
				Part 4: Improve the zoom experience
					- Create the ItemSize property so that it updates the UI
					- Update the ItemSize property value
				Part 5: Enable user edits
					- Attach the DetailPage
					- Make the editing controls interactive
				Part 6: Format values through function binding
					- Bind the effect-slider labels and format the values for display
			
			Tutorial: Create adaptive layouts - PhotoLab 
				https://docs.microsoft.com/en-us/windows/uwp/design/basics/xaml-basics-adaptive-layout

				Part 1: Define window breakpoints
					- Add window breakpoints
					https://docs.microsoft.com/en-us/windows/uwp/design/layout/screen-sizes-and-breakpoints-for-responsive-design
				Part 2: Add a data template for small window sizes
					- Create a new DataTemplate
					- Add metadata to a tooltip
				Part 3: Define visual states
					https://docs.microsoft.com/en-us/windows/uwp/design/layout/layouts-with-xaml
					https://docs.microsoft.com/en-us/windows/uwp/design/layout/layouts-with-xaml#adaptive-layouts-with-visual-states-and-state-triggers
					https://docs.microsoft.com/en-us/windows/uwp/design/layout/layouts-with-xaml#tailored-layouts
					- Add a VisualStateManager
					https://docs.microsoft.com/en-us/uwp/api/windows.ui.xaml.visualstatemanager?view=winrt-19041
					https://docs.microsoft.com/en-us/uwp/api/windows.ui.xaml.visualstate?view=winrt-19041
					- Create StateTriggers to apply the visual state
					- Set properties for each visual state

			Tutorial: Create custom styles - PhotoLab 
				https://docs.microsoft.com/en-us/windows/uwp/design/basics/xaml-basics-style

				Part 1: Create a fancy slider control
					- Customize a slider control
					https://docs.microsoft.com/en-us/uwp/api/Windows.UI.Xaml.Shapes?view=winrt-19041
					https://docs.microsoft.com/en-us/windows/uwp/design/controls-and-patterns/shapes
    
				Part 2: Create basic styles
					https://docs.microsoft.com/en-us/uwp/api/Windows.UI.Xaml.Style?view=winrt-19041
					https://docs.microsoft.com/en-us/uwp/api/windows.ui.xaml.frameworkelement.Resources?view=winrt-19041
					- Create a value text block style

				Part 3: Use a control template to make a fancy slider
					https://docs.microsoft.com/en-us/windows/uwp/design/basics/xaml-basics-style#prerequisite
	WEB

	WPF
		https://docs.microsoft.com/en-us/visualstudio/get-started/csharp/tutorial-wpf?view=vs-2019Tutorial
	C++
		HelloWorld
			https://docs.microsoft.com/en-us/windows/uwp/get-started/create-a-basic-windows-10-app-in-cppwinrt

	Microsoft Identity Platform
	===========================
		https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-overview#:~:text=Microsoft%20identity%20platform%20%28v2.0%29%20overview%201%20Getting%20started.,local%20identities%2C%20see%20the%20Azure%20AD%20B2C%20overview.
   
        Tutorial: Call the Microsoft Graph API from a Universal Windows Platform (UWP) application
            https://docs.microsoft.com/en-us/azure/active-directory/develop/tutorial-v2-windows-uwp

	Microsoft Entity Framework
	==========================
		https://docs.microsoft.com/en-us/ef/

		Entity Framework 6
		==================
			https://docs.microsoft.com/en-us/ef/ef6/

			Get started with Entity Framework 6
				https://docs.microsoft.com/en-us/ef/ef6/get-started
			Fundimentals
				Get Entity Framework
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/install
				Working with DbContext
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/working-with-dbcontext
				Relationships, navigation properties, and foreign keys
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/relationships
				Async query and save
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/async
				Configuration
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/configuring/code-based
				Connection management
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/connection-management
				Connection resiliency and retry logic
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/connection-resiliency/retry-logic
				Databinding with WinForms
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/databinding/winforms
				Working with disconnected entities
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/disconnected-entities/
				Logging and intercepting database operations
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/logging-and-interception
				Performance considerations for EF 4, 5, and 6
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/performance/perf-whitepaper
				Entity Framework 6 Providers
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/providers/
				Working with proxies
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/proxies
				Testing with a mocking framework
					https://docs.microsoft.com/en-us/ef/ef6/fundamentals/testing/mocking
				Creating a Model
					https://docs.microsoft.com/en-us/ef/ef6/modeling/
				Querying and Finding Entities
					https://docs.microsoft.com/en-us/ef/ef6/querying/
				Saving Data with Entity Framework 6
					https://docs.microsoft.com/en-us/ef/ef6/saving/

				School Sample Database (used in various samples)
					https://docs.microsoft.com/en-us/ef/ef6/resources/school-database

			Code First Data Annotations
				https://docs.microsoft.com/en-us/ef/ef6/modeling/code-first/data-annotations

		Entity Framework Core
		=====================
			https://docs.microsoft.com/en-us/ef/core/

			Getting Started with EF Core
				https://docs.microsoft.com/en-us/ef/core/get-started/overview/first-app?tabs=netcore-cli
			Migrations 
				https://docs.microsoft.com/en-us/ef/core/managing-schemas/migrations/?tabs=dotnet-core-cli

		References
		==========
			'Code First' to a New Database
			https://docs.microsoft.com/en-us/ef/ef6/modeling/code-first/workflows/new-database
			MS SQL Express (LocalDb)
			https://www.sqlshack.com/how-to-connect-and-use-microsoft-sql-server-express-localdb/
			Try connection to a database
				https://www.c-sharpcorner.com/blogs/access-sql-server-database-in-net-core-console-application
		
			NUGet 
				  Microsoft.Extensions.Configuration
				  Microsoft.Extensions.Configuration.FileExtensions
				  Microsoft.Extensions.Configuration.Json
				  System.Data.SqlClient
		
			appsetings.json
				  {
					  "ConnectionStrings": {
						  "Default": "Server=YOUR_SERVER;Database=mydatabase;User  Id=YOUR_USER;Password=YOUR_PASSWORD;MultipleActiveResultSets=true"
					  }
				  }
		
			ConnectionStrings
				https://docs.microsoft.com/en-us/dotnet/framework/data/adonet/connection-string-syntax
				https://docs.microsoft.com/en-us/aspnet/mvc/overview/getting-started/introduction/creating-a-connection-string

				https://sqlundercover.com/2020/11/30/sql-server-login-default-database-and-failed-logins/

							  
			      https://csharp.hotexamples.com/examples/-/SqlConnection/-/php-sqlconnection-class-examples.html
				  https://www.connectionstrings.com/sql-server/
				  https://stackoverflow.com/questions/15631602/how-to-set-sql-server-connection-string

				//.NET DataProvider -- Standard Connection with username and password
				//
				//using System.Data.SqlClient;
				/*
				SqlConnection conn = new SqlConnection();
				conn.ConnectionString =
				  "Data Source=ServerName;" +
				  "Initial Catalog=DataBaseName;" +
				 "User id=UserName;" +
				  "Password=Secret;";
				conn.Open();
				*/

				//.NET DataProvider -- Trusted Connection
				//
				/*
				SqlConnection conn = new SqlConnection();
				conn.ConnectionString =
				  "Data Source=ServerName;" +
				  "Initial Catalog=DataBaseName;" +
				  "Integrated Security=SSPI;";
				conn.Open();
				*/

			ASP.NET Data Access Options
				https://docs.microsoft.com/en-us/previous-versions/aspnet/ms178359(v=vs.110)
			SQL Server Connection Strings for ASP.NET Web Applications
				https://docs.microsoft.com/en-us/previous-versions/aspnet/jj653752(v=vs.110)?redirectedfrom=MSDN#sqlserver
			SQL Server 2012 Express LocalDB
				https://docs.microsoft.com/en-us/previous-versions/sql/sql-server-2012/hh510202(v=sql.110)?redirectedfrom=MSDN
			Connection strings and models (EntityFramework)
				https://docs.microsoft.com/en-us/ef/ef6/fundamentals/configuring/connection-strings?redirectedfrom=MSDN

	Visual Studio product family
	============================
		https://docs.microsoft.com/en-us/visualstudio/?view=vs-2019

		Samples
			https://developer.microsoft.com/en-us/windows/samples/

	Visual Studio Subscriptions
	===========================
		https://docs.microsoft.com/en-us/visualstudio/subscriptions/

	Visual Studio App Center
	========================
		https://docs.microsoft.com/en-us/appcenter/
		https://docs.microsoft.com/en-us/appcenter/build/troubleshooting/code-repos

		Building
			https://docs.microsoft.com/en-us/appcenter/build/
				https://docs.microsoft.com/en-us/appcenter/build/troubleshooting/
					https://docs.microsoft.com/en-us/appcenter/build/troubleshooting/build-failed
		Install
			https://blogs.windows.com/windowsdeveloper/2016/04/13/windows-app-studio-update-installer-companion-app/
			Installer App On Miccrosoft Store
			https://www.microsoft.com/en-gb/p/windows-app-studio-installer/9nblggh4qtfx?rtc=1&activetab=pivot:overviewtab
			Videos
			https://video.search.yahoo.com/search/video?fr=mcafee&p=App-studio+build+ouput+%26+installation+on+local+PC#id=2&vid=24ce53dabf9c96a09d7e2c33c03647be&action=click
			***********************************************************
			Extract contents of build.zip into folder
			Check that app not already installed before running build. 
			Use "Add or Remove Programs" 
			Run install.ps using Powershell
			***********************************************************

	Visual Studio 2019
	==================
		https://docs.microsoft.com/en-us/visualstudio/windows/?view=vs-2019&preserve-view=true

		How to Create and use a Database in Visual Studio 2019
			https://social.msdn.microsoft.com/Forums/en-US/1be96e52-8f8b-443a-96d7-99688bd56470/how-to-create-and-use-a-database-in-visual-studio-2019

		Project Types
			https://docs.microsoft.com/en-us/visualstudio/extensibility/internals/project-type-essentials?view=vs-2019

			Database
				https://www.mssqltips.com/sqlservertip/2971/creating-a-visual-studio-database-project-for-an-existing-sql-server-database/
				https://www.c-sharpcorner.com/article/create-sql-server-database-project-with-visual-studio/
			Shared Projects
				https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/shared-projects?tabs=windows
				GIT - mobile-samples/Tasky/
					https://github.com/xamarin/mobile-samples/tree/master/Tasky
				Portable Class Libraries (PCL)
					https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/pcl?tabs=windows
				Sharing code overview
					https://docs.microsoft.com/en-us/xamarin/cross-platform/app-fundamentals/code-sharing
			SQL Data Tools In C# - Database Creation, Management, and Deployment in Visual Studio
				https://video.search.yahoo.com/search/video?fr=mcafee&p=Using+Visual+Studio+Database+Project+to+create+%26+manage+an+SQL+database#id=1&vid=f66723ddb2b4db1473e72f35882493be&action=click

		Templates & Extensions
			https://docs.microsoft.com/en-us/visualstudio/ide/finding-and-using-visual-studio-extensions?view=vs-2019
			https://docs.microsoft.com/en-us/visualstudio/ide/how-to-locate-and-organize-project-and-item-templates?view=vs-2019
			%USERPROFILE%\Documents\Visual Studio 2019\Templates\ProjectTemplates
			%USERPROFILE%\Documents\Visual Studio 2019\Templates\ItemTemplates
			https://docs.microsoft.com/en-us/visualstudio/ide/creating-project-and-item-templates?view=vs-2019
			https://docs.microsoft.com/en-us/visualstudio/ide/how-to-create-project-templates?view=vs-2019
			https://docs.microsoft.com/en-us/visualstudio/ide/how-to-create-item-templates?view=vs-2019

			Downloads and tools for Windows 10
				https://developer.microsoft.com/en-us/windows/downloads/
				#
                Windows Template Studio (Visual Studio Extension)
                    https://github.com/microsoft/WindowsTemplateStudio/blob/dev/docs/concepts.md
                    https://github.com/microsoft/WindowsTemplateStudio/blob/dev/docs/getting-started-extension.md
                    https://github.com/Microsoft/WindowsTemplateStudio
                Windows Community Toolkit
                    https://docs.microsoft.com/en-us/windows/communitytoolkit/
                Microsoft Web Template Studio
                    https://github.com/Microsoft/WebTemplateStudio/
                Design toolkits for Windows apps
                    https://docs.microsoft.com/en-us/windows/uwp/design/downloads/

				GitHub Extension for Visual Studio
				SQLite for Universal Windows Platform
				PowerShell Tools for Visual Studio
				C++/CLR Windows Forms for Visual Studio 2019
				Windows Event Log Browser
				Visual Studio IntelliCode

			Installed Extensions
				
			Interesting Extensions

			Tutorials (Console/UWP/WPF/WinForms/WEB/ASP/Core)
				https://docs.microsoft.com/en-us/visualstudio/get-started/csharp/?view=vs-2019

		Intellisense
			AI Based (new)
			https://docs.microsoft.com/en-us/visualstudio/intellicode/not-in-toc/autotraining_faq

	Visual Studio Code
	==================
		https://code.visualstudio.com/docs

		User Guide
			https://code.visualstudio.com/docs/editor/codebasics
			Snippets
				https://code.visualstudio.com/docs/editor/userdefinedsnippets
			Languages
				https://code.visualstudio.com/docs/languages/overview
				https://code.visualstudio.com/docs/nodejs/working-with-javascript
				https://code.visualstudio.com/docs/nodejs/reactjs-tutorial
				https://code.visualstudio.com/docs/typescript/typescript-tutorial
				https://code.visualstudio.com/docs/python/python-tutorial

			VS-2019 Soliutions
				https://www.c-sharpcorner.com/article/running-a-visual-studio-2019-solution-in-visual-studio-code/

	Visual Studio Codespaces
	========================
		https://docs.microsoft.com/en-us/visualstudio/codespaces/overview/what-is-vsonline

		How-to guides
			https://docs.microsoft.com/en-us/visualstudio/codespaces/how-to/vscode
			https://docs.microsoft.com/en-us/visualstudio/codespaces/how-to/browser

	Visual Studio Blend
	===================
	(XMAL editor shared with Visual Studio)
		https://docs.microsoft.com/en-us/visualstudio/designers/creating-a-ui-by-using-blend-for-visual-studio?view=vs-2015&redirectedfrom=MSDN#:~:text=Blend%20for%20Visual%20Studio%20overview%201%20Tools%20panel.,Objects%20and%20Timeline%20window.%20...%204%20See%20also

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
	MD - Mark Down files
		https://guides.github.com/features/mastering-markdown/

	Introduction - Hello World
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
		- Team Explorer-> Changes-> Stage
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

Postaman
========
	Download
		https://www.postman.com/downloads/
	Web Tool
		
	Desktop Tool

		














