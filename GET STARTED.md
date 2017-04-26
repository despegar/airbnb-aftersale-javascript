Welcome to the airbnb-aftersale-javascript wiki!

## Install

* [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb)

* [eslint-config-airbnb-base](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base)

### React

* `npm i eslint-plugin-react --save-dev`

## JetBrains (Idea, Webstorm) settings

File > Settings > Plugins > Browse repositories... > Search: eslint > Install > Restart IntelliJ

File > Settings > Languages & Frameworks > JavaScript > Code Quality Tools > ESLint

![](https://i.stack.imgur.com/Dr8EW.png)

After that it should work like this:

![](https://i.stack.imgur.com/IvIZt.png)

## ESLint config

ESLint doesn't come with a config. You have to create your own or use a preset:

* `npm install --save-dev eslint-config-airbnb eslint`

Then in your .eslintrc

`
{
  "extends": "airbnb"
}
`

[See more](http://stackoverflow.com/questions/34700062/intellij-plugin-airbnb-eslint-w-react)




