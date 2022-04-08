# angular-bank-app

After doing research from other sources I managed to assemble every piece of information that might me of aid to the project
With banking web applications, funds easily get transacted.

# creating a module

When the program is done, two or three orders are lined up with the precise structure.
To utilize the rakish order line interface (CLI). yet, first we want to set up a climate that is reasonable for the structure. Prior to everything, introduce nodejs by going to the node js official website/download. After which open the order brief/terminal in your pc or visual studio code or compiler and run the accompanying orders,

# installing angular
npm install @ angular/cli -g (there is no space between “@” and “angular,”)

This is to install the angular cli. The command will only work when node js and npm are already installed. A times the installation takes a while.
After the installation is done, upgrade or update your angular frame-work.

# creating a new app
To create a new app, a command is assigned to the angular framework. Here is the command;
ng new[my-project]
The order line interface (CLI) will currently feel free to make the catalog. It will likewise introduce every single required reliance, however it will take some time.
We can likewise utilize the order
ng new
To create a new project.
Though you might want to skip the installation of external dependencies automatically. For this write;

ng new example --skip-install

Sadly, you'll need to introduce them later on in time physically by utilizing the npm introduction order.
Css can be utilized close by with angular js, all things considered Sass as I have utilized in the task. The order line interface (CLI), makes a typical css record for each part naturally. To transform them physically, you can utilize the - style scss choice to tell the order line interface (CLI) that you need to utilize Sass. for example the order is composed as;


ng new example - - style scss

Other components can also be generated from the command, for example, the command,

ng generate component [app]

Can be used to create a working application. It generates the files that can be used to create a new component. 
Whenever we are finished making and fostering our angular application, we will likewise run and test it. The angular command line connection point will begin running once the accompanying order is composed;
# to run
ng serve

This is to begin our application being developed mode.if it recognizes a change, it will recompile the application (mostly) and naturally update the application in the program.
To get the records that are expected for transferring the web application to the server, we utilize the order;

ng build

The ng assemble order will cause the order line interface(CLI) to fabricate your application and spots the result in an index called "dist"

A few orders impair the CLI for your task and make for you a webpack setup record. Here is the order

ng eject


 
