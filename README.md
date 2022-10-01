# pm-\<Lang-here\>

<div style="display:flex; justify-content:center; apgn-content: center; flex-direction:column;">
    <p style="font-weight: bold;">Python</p>
    <p style="font-weight: bold;">Go</p>
    <p style="font-weight: bold;">Rust</p>
</div>

## Project Structure

### pm-example 
### -h | —help
```
	print signature ex:pm-example [params] command [command-params]  
	commands 
```

### init <name> - creates package.json with name property

### search - gets list of packages

> This address returns package information (such as package name & version)
> https://www.npmjs.com/search/suggestions?q=\<package-name-here\>

### Adds package to dependencies
```pm-example install```

### Adds package to devDependencies
```pm-example install —save-dev```

install - Adds package name to JSON packages array
```
{
	“name”: “pm-<Lang-here>”,
	"dependencies": {
		"express": "~4.0.0",
	},
	"devDependencies": {
		"express-validator": "~6.12.1",
	}
}
```