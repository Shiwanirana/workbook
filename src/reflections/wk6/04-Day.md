# Day 4
_01/21/2021_

## What i learned in coding school is...
how to code

## 1. What is a nested route?
When building the single page applications, nested routes are used for complex user interfaces within the nested components. A route with in a route is known as nested route. 

## 2. When might you use a nested route? (other than the provided example)
Nested route can be used any where in any relationships. For example building a web site, when you are using dynamic pages, you need nested route for the flow of your site.
{
  path: '/my-route',
  component: EmptyRoute,
  children: [{
     name: 'route',
     path: '',
     component: My Route
  },{
     name: 'route.child-one',
     path: 'child-one',
     components: ChildOne
    }]
}

## 3. Can you pass parameters through nested routes? When might you use them?
Yes, you can pass parameters through nested routes using Id.

Day-4 Afternoon Project:  https://shiwanirana.github.io/partner-pokedex/.