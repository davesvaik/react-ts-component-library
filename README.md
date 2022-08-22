### component library tutorial

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
