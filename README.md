# Modern CSS

This repo covers the two main ways to style react components with scoped classes
Purpose: helpful in larger projects (team projects) where more developers can name a class in the same way, resulting in properties being applied unexpectedly on more components
Solution: Classes that are scoped to certain components

## Solution no. 1: STYLED COMPONENTS

Create Styled Components in JS

### See the examples in:

- src/components/UI/Button/Button.js
- src/components/CourseGoals/CourseInput/CourseInput.js

### Add to package.json

`npm install --save styled-components`

## Solution no. 2: CSS MODULES

Works in create-react-app dev environment

### How to use CSS Modules?

For each component, build a Component.module.css file and in the Component.js file import:
`import styles from './Component.module.css'`
@styles - object that has the classes as properties

E.g of use in JSX:
`<div className={styles.class}>This div has a class from a CSS module</div>`

### See the examples in:

- src/components/CourseGoals/CourseInput/CourseInput.js

## References

[Demo Project](https://modern-css-applications.netlify.app/)
[Styled Components](https://styled-components.com/)
[CSS Modules](https://github.com/css-modules/css-modules)
