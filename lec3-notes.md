Github --> kabir-Sagiii/AIT-ReactDemos


In react creating UI is as simple as HTML
And we can reuse the UI like in JS 

# How to create button and list using React ? 

1) crete a button using react  (lec3/ReactButton.html)

s1) Create a HTML file
s2) Add basic code of HTML (skeleton)
s3) Add script tag inside your body tag 
s4) Integrate react with HTML Document (React is a JS Library (Library=collection of predefined functions or classes or objets ))
https://legacy.reactjs.org/docs/cdn-links.html   (1st link )

* Do it in head section 

 <title>Button in React</title>
  <script src="https://unpkg.com/react@18/umd/react.development.js" ></script>                   ------> CDN Link
</head>


HTML ---> HTML elements ----> UI components
JS ---> pre defined object & function ---> DOM --->UI component
REACT----> Pre defined object and function ----> React Element ---> Add in DOM ----> UI component

Create React Element 

s5) let reactElement= React.createElement('<tagname>' , {----}, Children )        --------->    (tagname , object , children)

  <script >
    let buttonReactElement=React.createElement("button", {}, "React Button");
  
  </script>  

To show button on the page ---> We need to add the buttonElement in DOM ----> To do this we have to take help of another Library  ---> ReactDOM 
s6)   Integrate ReactDOM with HTML -------> https://legacy.reactjs.org/docs/cdn-links.html
  2nd link 

s7) use ReactDOM.render(<React Element>, DOM element reference(location where you want to show ))        

<body id="body">

  <script >
    let buttonReactElement=React.createElement("button", {}, "React Button");
    ReactDOM.render(buttonReactElement,document.getElementById("body"));

  </script>
</body>



--------> Our button is now created 

===========================================================================================


Create a h1 tag using React  ----> (lec3/ReactH1.html)

===========================================================================================




We can say that creating UI  in HTML is still easy than React

This is where JSX came into picture .
JSX= JS +XML   (95% similar to HTML )

let h2=<h2>----</h2>

let button = <button>--------</Button>

JSX elements will be converted to react elements 

ReactDev---------> JSX Elemnts-----------> babel compiler ---------> React Elements----->ReactDOM-------->DOM------>UI


=======================================================================================


