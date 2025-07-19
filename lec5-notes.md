Lets create a simple card :
- user image
- user name 
- some content <p>
- simple button

-----------> lec5/cardJSX.html and lec5/card.css

Suppose we want one more card 

In normal HTML we had to re -write the entire code 

To reuse the code :

we need to place the aleardy created JSX (which is inside a JS variable ; in this case cardJSX , inside a newly creaetd variable)

 let cardJSX2 = <div> {cardJSX}</div>        ------> will display one card

         let cardJSX2 = (
          <div> 
            {cardJSX}
            {cardJSX}
            {cardJSX}
            
                                      ---------------> nOW 3 CARDS will be dispalyed  
            
            
            </div>
         
        );
 
        

To add JS code inside JSX element we need to place the JSX element inside {}

<jsx> {js code} <jsx>

<jsx attribute1={ js code} > {js code} <jsx>

We can assign JS code to jsx attribute also
EX: 

      let imgURL="https://st1.bollywoodlife.com/wp-content/uploads/2024/06/Akshay-Kumar.jpg"
        let cardJSX = (
          <div className="card">
            <div className="img">
              <img src={imgURL} alt="Random Image" width='80%' />      --------->   ********   

            </div>
        )
 ----------> we are passing imgURL variable inside JSX {} 


 To add JS code inside JSX element we need to place the JS variable inside {}


 ** To get better at CSS , master Flex concept (spend 1-2 hrs there)
You can just imagine How difficult it would be to create cards in JS 


=================================================================

Currently we are showing the same data in the card , lets make it dynamic 

 we need to pass input to the {card} component  :--------> lec5/cardJSX2.html

 maybe , we can use the concept of functions in JS and pass different arguements in parameters 

 Lets create UI inside JS FUnction   -------------------> lec5\cardJSX2.html



we are displayin image, name and paragraph dynamically using JS functions 

React is all about practice