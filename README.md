# eslint-plugin-rinsuki

some good rules for me

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-rinsuki`:

```
$ npm install eslint-plugin-rinsuki --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-rinsuki` globally.

## Usage

Add `rinsuki` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "rinsuki"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "rinsuki/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





