# session-2

What is User Interface ?
UI = user interface = collection of ui components (buttons , textbox, links , cards)

But , Using HTML / JS also we can create UI components

Then why React is used to create UI ?

creating UI with html

create simple button using html 
----using predefined objects and functions------> DOM Manipulation --> DOM Button element 

1) using HTML
<body>

  <h1>Button in HTML</h1>
  <button>HTML Button </button>
  
</body>
------------------------------------------------------------------
2)  using JS 

  <script>
    // Using JavaScript to create a button
    const button = document.createElement('button'); 
    button.textContent = 'JS Button';
    document.body.appendChild(button);                       -----------> adding button in the body 
  </script>


 From above ex we can say that Creatin UI is easier in HTML as compared to JS 


 EX-2)

 creating list of mobiles :

 1) using html (lec2/index3.html)

<body>
  <ol>
    <li>Apple</li>
    <li>oppo</li>
    <li>samsung</li>
    <li>jio</li>
    <li>moto</li>
    <li>LG</li>
  </ol>

</body>
------------------------------------------------------------------
2) using JS  (lec2/index4.html)

<body>
  <h1>Creating list using li in JS </h1>
  <script>
    let ol=document.createElement('ol')
    let li1=document.createElement('li')
    li1.textContent='Apple'
    let li2=document.createElement('li')
    li2.textContent='oppo'
    let li3=document.createElement('li')
    li3.textContent='samsung'
    let li4=document.createElement('li')
    li4.textContent='jio'
    let li5=document.createElement('li')
    li5.textContent='moto'

    ol.appendChild(li1)
    ol.appendChild(li2)   
    ol.appendChild(li3)
    ol.appendChild(li4) 
    ol.appendChild(li5)

    document.body.appendChild(ol)


  </script>
</body> 

 From above ex we can say that Creatin UI is easier and simpler  in HTML as compared to JS 
If we add styles also it will be more complex

Reusing components in HTML and JS ( (lec2/index4.html))

1) in HTML 
--> copy then entire code again and again (n number of times) , no option of reusing 

2) in JS 
---> wrap the code in a function --> just call the function again and again

Hence from reusablity POV , JS is a better choice 

React combines the advantages of both HTML and JS :-
In react creating UI is easy and reusing components is also possible .


There are few more technical reasons which makes react a better choice



# How to create button and list using React ? 
