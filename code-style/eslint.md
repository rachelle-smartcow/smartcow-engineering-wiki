---
description: Configuration
---

# 🖨 ESLint

```
{
	"env": {
		"browser": true,
		"es2021": true
	},
	"extends": [
		"airbnb",
		"eslint:recommended",
		"plugin:@typescript-eslint/recommended",
		"plugin:react/recommended",
		"plugin:prettier/recommended"
	],
	"parser": "@typescript-eslint/parser",
	"parserOptions": {
		"ecmaFeatures": {
			"jsx": true
		},
		"ecmaVersion": "latest",
		"sourceType": "module"
	},
	"settings": {
		"react": {
			"version": "detect"
		},
		"import/resolver": {
			"node": {
				"paths": ["src"],
				"extensions": [".js", ".jsx", ".ts", ".tsx"]
			}
		}
	},
	"plugins": ["react", "react-hooks", "@typescript-eslint"],
	"rules": {
		"import/extensions": [
			"error",
			"ignorePackages",
			{
				"js": "never",
				"jsx": "never",
				"ts": "never",
				"tsx": "never"
			}
		],
		// "indent": ["error", "tab"],
		"@typescript-eslint/consistent-type-definitions": "off",
		"@typescript-eslint/no-unused-vars": "error",
		"no-use-before-define": 0,
		"no-plusplus": 0,
		"consistent-return": 0,
		"no-underscore-dangle": 0,
		"no-param-reassign": 0,
		"no-unused-vars": ["error", { "vars": "all", "args": "after-used" }],
		"no-unneeded-ternary": 1,
		"no-nested-ternary": 0,
		"react/prop-types": 0,
		"react/sort-comp": 0,
		"noImplicitAny": 0,
		"react-hooks/rules-of-hooks": "error",
		"react-hooks/exhaustive-deps": "warn",
		"prettier/prettier": "off",
		"react/function-component-definition": [
			"error",
			{
				"namedComponents": "arrow-function",
				"unnamedComponents": "arrow-function",
				"statelessComponents": "arrow-function"
			}
		],
		"react/jsx-props-no-spreading": [
			"error",
			{
				"html": "ignore",
				"custom": "ignore",
				"explicitSpread": "ignore",
				"exceptions": [""]
			}
		],
		"react/jsx-filename-extension": [
			1,
			{ "extensions": [".tsx", ".stories.js"] }
		],
		"react/destructuring-assignment": 0,
		"@typescript-eslint/no-explicit-any": 0,
		"@typescript-eslint/array-type": 1,
		"@typescript-eslint/no-use-before-define": 0,
		"@typescript-eslint/explicit-function-return-type": "off",
		"@typescript-eslint/no-non-null-assertion": "off",
		"@typescript-eslint/interface-name-prefix": 0,
		"@typescript-eslint/ban-ts-ignore": 0,
		"@typescript-eslint/no-inferrable-types": 1,
		"@typescript-eslint/consistent-type-assertions": 1,
		"import/prefer-default-export": "off",
		"import/no-extraneous-dependencies": ["error", { "devDependencies": true }],
		"import/no-useless-path-segments": "off",
		"react/no-array-index-key": 1,
		"skipLibCheck": 0,
		// a11y
		"jsx-a11y/anchor-is-valid": 0,
		"jsx-a11y/no-static-element-interactions": 0,
		"jsx-a11y/click-events-have-key-events": 0,
		"jsx-a11y/no-noninteractive-element-interactions": 0,
		"object-curly-spacing": [2, "always"],
		"semi-style": 1
	}
}

```
