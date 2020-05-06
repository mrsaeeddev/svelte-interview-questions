

<h4 align="center">
    <a href="https://github.com/iamsaeeddev/svelte-questions">
        <img src="https://raw.githubusercontent.com/iamsaeeddev/svelte-interview-questions/master/logo.png">
    </a>
</h4>

# Svelte Questions
> Concepts and Questions related to Svelte

# Questions
## Q.1 What is Svelte?
Svelte is a tool for building fast web applications.

It is similar to JavaScript frameworks such as React and Vue, which share a goal of making it easy to build slick interactive user interfaces.

But there's a crucial difference: Svelte converts your app into ideal JavaScript at build time, rather than interpreting your application code at run time. This means you don't pay the performance cost of the framework's abstractions, and you don't incur a penalty when your app first loads.

## Q.2 How's Svelte different from traditional frontend frameworks like ReactJS and VueJS?
Traditional frameworks like ReactJS and VueJS do the bulk of their work in the browser i.e on the run time while Svelte shifts that work into build step i.e during compile time. 

So, instead of updating the DOM using Virtual DOM diffing, Svelte writes code that surgically updates the DOM when the state of your app changes.

## Q.3 What is reactivity in app development?
At the heart of modern interactive web applications is the concept of reactivity. When an app is reactive, it means that any change of values (e.g. as a result of user input) will be automatically reflected in the Document Object Model (DOM), a logical tree structure that represents the HTML page a user can see in the browser, or any other place in which there are values that depend on the changed ones.

## Q.4 How do modern frameworks other than Svelte make it possible to develop reactive apps?
The introduction of modern asynchronous and event-driven web app frameworks such as React, Angular and Vue made it possible to develop such reactive apps. To that end they use various techniques (such as the Virtual DOM) that interpret the app code in the background, making it possible to update individual elements of the app without having to refresh the entire HTML page.


