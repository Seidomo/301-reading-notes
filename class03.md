# MUSTACHE AND FLEXBOX

- [**back to home**](https://seidomo.github.io/reading_notes/home)



## Javascript Templating

Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.



## MUSTACHE

Mustache is a logic-less template syntax and it's refered logic-less is because
there are no if's, else, or for loops only tags.

Mustache.js is an implementation of the mustache template system in JavaScript. 


# FLEXBOX CSS

 **PROPERIIES**

*display*

```
.project{
    display: flex; ___________________
}

```
This defines a flex container inline or block depending on the given value. 
It enables a flex context for all its direct children.



*flex-wrap*


```
.project{
     flex-wrap: nowrap | wrap | wrap reverse; 
}

```

By default, flex items will all try to fit onto one line but we can change that and allow the items to wrap as needed with this property.

*flex-flow*


```
.project{
     flex-flow: column wrap; 
}

```

This is a shorthand for the flex-direction and flex-wrap properties which together define the flex container’s main and cross axes. 

*justify-content*


```
.project{
    justify-content: ____________________ ;
}

```

This defines the alignment along the main axis. It helps distribute extra free space leftover when either all the flex items on a line are inflexible or are flexible but have reached their maximum size. 





**ATTRIBUTION**

- [Templating with Mustache](https://medium.com/@1sherlynn/javascript-templating-language-and-engine-mustache-js-with-node-and-express-f4c2530e73b2)

-[A Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)