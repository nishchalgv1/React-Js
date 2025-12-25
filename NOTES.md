# What is CDN?
- Content Delivery Network
- These are the websites where react has been hosted and we are just pulling react from there into our project

## What is CDN ? Why do we use it?
## What is cross-origin?


1. <script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
- First file is the core file of the react. 

2. <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
- This is the react library useful for DOM operations

- `React.createElement()` takes 3 arguments
1. What tag you need to create?
2. Object
3. What we have to put inside h1 tag?  (just like we have innerHTML in javascript)

## NOTE: 
- First of all we need to tell react `What is the root where we need to render stuff?`
 I need to render my heading inside the root (<div id = root> </div>)
- So first of all I need to create root inside react

## Conclusion: 
First of all ***React*** wants to have root where it will do all the ***DOM Manipulaton***

# NOTE
- creating Element is the core thing of react
- whenever we are creating a root and rendering something inside it - It is the job of ReactDOM.

# root is the place where all the React code will run 