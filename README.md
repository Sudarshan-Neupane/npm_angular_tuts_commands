## ~~~ Tutorial NPM NG ~~~~
##NPM commands and getting started:

	- npm install(5.6/6.5.0  mine latest)
	- npm start
	
	- npm install -g typescript
	
### Angular CLI

	- Install Angular
			> $ npm install -g @angular/cli
			> $ ng --version
	    If you are running in OSX
			- you need to install watchman.(you might receive this line in the output)
				#could not start watchman; falling back to NodeWatcher for file system events.
			$brew install watchman
	
### Create Example Project

		> $ ng new angular-hello-world
		
**index.html**
```

	 <!doctype html>
	 <html lang="en">
	 <head>
	<meta charset="utf-8">
	 <title>AngularHelloWorld</title>
	<base href="/">
	
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="icon" type="image/x-icon" href="favicon.ico">
	 </head>
	<body>
	<app-root></app-root>
	</body>
    </html>
```

**_<app-root> </app-root>_**
*The app-root tag is where our application will be rendered*
*But what is the app-root tag and where does it come from? **app-root is a component that is defined by our Angular application**. In Angular we can define our own HTML tags and give them custom functionality. The app-root tag will be the “entry point” for our application on the page.*

**Running the application**
 > cd angular_hello_world
 > ng serve( npm start)





#Repository link command 
…or create a new repository on the command line
echo "# npm_angular_tuts_commands" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Sudarshan-Neupane/npm_angular_tuts_commands.git
git push -u origin master
…or push an existing repository from the command line
git remote add origin https://github.com/Sudarshan-Neupane/npm_angular_tuts_commands.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
