# pm-<Lang-here>

## Project Structure

### pm-example 
### -h | —help
	print signature ex:pm-example [params] command [command-params]  
	commands 

### init <name> - creates package.json with name property

### search - gets list of packages

This address returns package information (such as package name & version)
https://www.npmjs.com/search/suggestions?q=<package-name-here>


### pm-example install				 			Adds package to dependencies
### pm-example install —save-dev 			Adds package to devDependencies

install - Adds package name to JSON packages array
{
	“name”: “pm-<Lang-here>”,
	"dependencies": {
	    "express": "~4.0.0",
	},
	"devDependencies": {
	    "express-validator": "~6.12.1",
	}
}