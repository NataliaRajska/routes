# routes

## Using Angular routes in a single-page application
This tutorial describes how you can build a single-page application, SPA that uses multiple Angular routes.

In an SPA, all of your application's functions exist in a single HTML page. As users access your application's features, the browser needs to render only the parts that matter to the user, instead of loading a new page. This pattern can significantly improve your application's user experience.

To define how users navigate through your application, you use routes. You can add routes to define how users navigate from one part of your application to another. You can also configure routes to guard against unexpected or unauthorized behavior.

To explore a sample app featuring the contents of this tutorial, see the live example https://stackblitz.com/angular/brlgvnamravl?file=src%2Fapp%2Fapp.component.html / download example.

## Objectives
+ Organize a sample application's features into modules.
+ Define how to navigate to a component.
+ Pass information to a component using a parameter.
+ Structure routes by nesting several routes.
+ Check whether users can access a route.
+ Control whether the application can discard unsaved changes.
+ Improve performance by pre-fetching route data and lazy loading feature modules.
+ Require specific criteria to load components.

## Prerequisites
To complete this tutorial, you should have a basic understanding of the following concepts:

+ JavaScript
+ HTML
+ CSS
+ Angular CLI
You might find the Tour of Heroes tutorial helpful, but it is not required.
