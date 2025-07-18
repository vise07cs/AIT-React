
Create a list using React (lec4/ReactList.html)

=========================================================================================

     <script>
       let ol=React.createElement("ol",{},[
        React.createElement("li",{},"Raj"),
        React.createElement("li",{},"Vikram"),
        React.createElement("li",{},"Aditya"),
        React.createElement("li",{},"Singh"),



      ])
      ReactDOM.render(ol,document.getElementById("root"));


    </script>


    In oreder to pass more than 1 children in the element we neeed to create an array .
    Here inside the ol element we want to create li


    How to configure attributes in React Element ---> Here 2nd arguement comes into picture 

      let ol=React.createElement("ol",{type:'a'},[.......]) 


      lets add some inline CSS

           let ol=React.createElement("ol",
       {
        type:'a',
        id:"myList",
        style: { color: 'red',  backgroundColor: 'black'  }
      
      }
      [.........]
           )



=======================================================================================================


Suppose we want to create a structure like this using React


<div>
  <div>
    <div>
      <h2></h2>
      <p></p>
    </div>

  </div>

</div>



  <script >
     let container=React.createElement("div",null,React.createElement("div",null,
      React.createElement("div",null),[
        
      React.createElement("h2",null,"React H2 Element"),
      React.createElement("p",null,"This is a paragraph in React"),

      ]
     ))

     ReactDOM.render(container,document.getElementById("body"));
    

  </script>

The above structure is ver very complex 

This is where JSX came into picture .
JSX= JS +XML   (95% similar to HTML )

let h2=<h2>----</h2>

let button = <button>--------</Button>

JSX elements will be converted to react elements 

ReactDev---------> JSX Elemnts-----------> Babel compiler ---------> React Elements----->ReactDOM-------->DOM------>UI


1) Lets create button using JSX  (lec4/jsxButton.html)

   we need Bable for this  ---> https://babeljs.io/setup#installation

  <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>


   <script type="text/babel">
    
    let buttonJSX = <button> JSX Button</button>
    ReactDOM.render(buttonJSX, document.getElementById("root"));


     </script>



2) lets create a lsit of Mobiles using JSX ------------>  (lec4/jsxList.html)


 HTML like syntax inside JS variable or JS Script ,  it is JSX 


 