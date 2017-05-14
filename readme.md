# Angular Js
  AngularJs is a javascript framework for we applications

## Need 
HTML is a great declarative language for STATIC docuemntsbut it fails 
to serve our purpose when there come a need to create a dynamic views in webapps. and is solved with 1) a library: JQuery 2) Frameworks: AngularJs

AngularJs extends the HTMl by adding built-in attributes ad components and also provides a an ability to create custom atttributes using simple JavaScript.

# Directives
Directives are markers on a DOM element that tell AngularJs to attach a specified behaviour to that DOM element or even transform the DOM element and its children.

| Directive  |  Description 
| --- | --- 
| ng-app | Auto bootstap AngJs Application 
| ng-init | initiates variables 
| ng-model | Binds HTML control's value to a property on the $scope object
| ng-controller | attaches a controller of MVC to view 
| ng-bind | replaces the value of HTML control with the value of specified Angjs expresion 
| ng-repeat | Loops through the table to HTML template 
| ng-show | Display HTML element based on the value of the specified expression 
| ng-readonly | Makes HTML element read-only based on the value of the specied expression 
| ng-disabled | sets the disable attribute on the HTML element if specified expression evalutates to true 
| ng-if | removes or creates HTML element based on an expression 
| ng-click | specifes custom behaviour when a element is clicked 
| bg-blur | tells AngJs what to do when an HTML loses focus


`ng-app` directive is a starting point of AngJs , it initializes the framework automatically

**note:** ng-app directive can be placed to any of the DOM element. it is preferable to place  ng-app at the root i.e. <html> or <body> . so, it the control the entire DOM hirerchy

`ng-model` directive is used to  two way data binding. It binds <input ,<select>>  or <text area> elements to specified property on $scope object 