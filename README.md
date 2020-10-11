# lightweight-css
Lightweight CSS 

This is a very simple lightweight css helper that helps you avoid creating multiple custom classes for styles that are used way too often in Web Design.

## How to install
`npm install lightweight-css`

You can choose to import it straight <br/>
`<link rel="stylesheet" href="./node_modules/lightweight-css/lightweight-css.css"/>`

or if you're using Webpack to compile and bundle your CSS you can simply use:<br/>
`import "lightweight-css";`

## Basic Usage

Simply use the classes below to achieve the appropriate styles

| Class | style |
| ----- | ----- |
| block        | display: block         |
| inline-block | display: inline-block  |
| hidden       | display: none          |
| center-text  | text-align: center     |
| right-text   | text-align: right      |
| no-decor     | text-decoration: none  |
| no-select    | user-select: none      |
| pointer      | cursor: pointer        |
| pos-rel      | position: relative     |
| pos-abs      | position: absolute     |
| pos-fix      | position: fixed        |
| flex         | display: flex          |
| flex-row     | flex-flow: row         |
| flex-col     | flex-flow: col         |
| flex-wrap    | flex-wrap: wrap        |
| just-start   | justify-content: flex-start    |
| just-between | justify-content: space-between |
| just-end     | justify-content: flex-end      |
| items-start  | align-items: flex-start        |
| items-center | align-items: center            |
| items-end    | align-items: flex-end          |

Hope this utility helps you!

## Contribution
Since this project is still quite small, feel free to create a PR to add improvements and more features!(as long as it's still lightweight)