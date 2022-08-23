### component library tutorial

## creating a npm library

1. make a directory and run npm init with all default values
2. make a directory for src/components/Button
3. create Button.tsx file and create a ts react Button component
4. npm install react typescript @types/react --save-dev
5. include index files to make importing easier for the users of the library
6. npx tsc --init, add cofig params in tsconfig.json
7. npm install rollup @rollup/plugin-node-resolve @rollup/plugin-commonjs @rollup/plugin-typescript rollup-plugin-dts --save-dev
8. settup rollup.config.js file with installed plugins
9. add npm i -D tslib since it was required
10. run rollup to generate dist folder
11. push to github
12. add publishConfig and registry to pakcage.json
13. create .npmrc in root directory of the user and github personal access tokens
14. connect to npm by adduser or login
15. npm publish!

## bundle CSS with npm library

1. create a CSS file for the button
2. include bundling syntax for rollup
3. add import postcss from 'rollup-plugin-postcss' in rollup config and install the library as dev
4. add postcss plugin and external
5. update version, run rollup and publish gain
6. update the npm pakcage version in the projects that are using them

## testing components with jest and RTL

1. install @testing-library/react jest @types/jest jest-environment-jsdom
2. create test file for the component and add a test
3. create jest config file
4. need to isntall babel for jsx to js. install @babel/core @babel/preset-env @babel/preset-react @babel/preset-typescript babel-jest
5. configure babel
6. need help to link css files for jest, install identity-obj-proxy --save-dev and add to jest config
7. run tests

## storybook to visualize components under development

1. npx sb init
2. creaete a story for thr component
3. npm install for the storybook dependencies
4. npm run storybook
