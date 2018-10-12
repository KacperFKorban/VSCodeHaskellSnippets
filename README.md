# VSCodeHaskellSnippets
A Few useful VS Code snippets for Haskell.


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
			"\t${3:_} -> ${4:_}"
		],
		"description": "Create case statement"
	},

