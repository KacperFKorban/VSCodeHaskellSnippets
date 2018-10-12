# VSCodeHaskellSnippets
A Few useful VS Code snippets for Haskell.

## Installation
1. Install `Haskell Syntax Highlighting` Extension
2. Open `Command Palette` type `snippets`, select `Preferences: Configure User Snippets` and confirm. Then type `Haskell` and press `Enter`.
3. Copy the snippets below, paste them inside the curly brackets and save the file.

## Snippets

```json
"Typeclass declaration": {
	"prefix": "class",
	"body": [
		"class ${1:TypeclassName} ${2:a} where",
		"\t$3"
	],
	"description": "Create new typeclass"
},

"Typeclass instance declaration": {
	"prefix": "instance",
	"body": [
		"instance ${1:TypeclassName} ${2:Type} where",
		"\t${3:function} = ${4:undefined}"
	],
	"description": "Create typeclass instance"
},

"Case statement": {
	"prefix": "case",
	"body": [
		"case ${1:value} of",
		"\t${2:_} -> ${3:_}"
	],
	"description": "Create case statement"
},
```
