### Installing Grunt
- install Node (nodejs.org)
- type in your command line **npm install -g grunt-cli**  
   **npm** Node Package Manager, installed with Node;  
   **-g** flag to indicate that we want to install package "globally";  
   **grunt-cli** the name of the Package
- add list of dependencies to package.json file  

Example of package.json

<pre>
{
    "name": "project name",
    "version": "project version",
    "devDependencies": {
    "grunt": "~0.0.1",
    "grunt-contrib-concat": "~0.3.0",
    "grunt-contrib-jshint": "~0.6.3"
    }
}
</pre>
- run **npm install** from the project's root directory
