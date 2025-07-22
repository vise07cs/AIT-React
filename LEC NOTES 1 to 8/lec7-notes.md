Lets create some more functional component

lets create a page 
1) header section 
2) main section
3) footer section


Its not a good idea to create 1 componet for all the components 
Its always advisable to divide the component into multiple components so that its easy to manage in future



For every section we will create 1 seperate  component 

lec7/webpage.html


Note ---> Any component which we assign to ReactDOM that component is considered as parent component for entire Application .

In our example (lec7/webpage.html)  --> App component is the parent component

Calling = Rendering 

From now on we will use the term rendering 
 
Rendering == calls + converting to React Element + added in DOM 


What is the difference between normal JS function and React Functional Component ?

(1)
React functional component always starts with uppercase
Normal JS function generally start with lowercase (but not mandatory)

(2)
React Functional Component will always return JSX 
Normal JS function can return any type of value

(3)
React Functional Component contains JSX code
Normal JS function does not contain JSX

-----------------------------------------------

Using attribute concept we can pass the arguements to the componenet 

In react we call it props 

Props are the properties of the component 
Props are used to pass dynamic data or input data to the components
Props are used to share the data from Parent component to child component

Note --> Functional Component 1st parameter will always be Object . And this object stores props or contains set of props as properties


