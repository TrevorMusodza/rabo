# rabo
Slides and example code on the training Angular Fundamentals, Oct. 2021 

## Links
- Repository with general example code: https://github.com/PeterKassenaar/voorbeeldenAngular2
- TodoMVC - examples of building the same app (a todo-application) in multiple frameworks. You can look at the source code and study the differences between frameworks. https://todomvc.com/
- "Angular vs React vs Vue: Which Framework to Choose in 2021". A comprehensive blog post describing the features of the three major frontend frameworks: https://www.codeinwp.com/blog/angular-vs-vue-vs-react/
- Codelyzer to analyse your project to see if the Styleguide rules are met: https://www.npmjs.com/package/codelyzer and http://codelyzer.com/.
- Deployment proces: `ng build --[options]`. A `dist` directory is created, containing the static files that can be deployed. See for possible options https://angular.io/cli/build.
  - So the general process in building applications is:
    1. `ng new <name>`
    2. `ng serve` cycle add/update/test/ components, services, and so on
    3. `ng build` and deploy the `dist` folder to production server

