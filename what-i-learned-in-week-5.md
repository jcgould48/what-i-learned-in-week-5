What I learned in week 4 
### Monday
****

Making a calculator

Dom - Document object module

You will not change the actual files of CSS or HTLM.  You are just changing how we view it by manipulating the DOM

.queryselector  helps you find elements in html

It works like a function


### Tuesday

When transferring from JS to css, you have to be careful to make sure certain things get sent as strings


### Wednesday

DRY - Don't repeat yourself
WET -Write everything twice
AHA- Avoid hasty abstraction

Abstraction-

Functions within DOM that can reduce repetition.

``` javascript 
const greetingParagraph - paragraphThatSaysHi()

function paragraphThatSaysHi(){
    const hi = document.createElement('p')
    hi.innerText ='Hi'
    return hi;
}
```

### Thursday
Application programming interface (API) - Code that is designed to be used by coders. For instance, when you write something on Javascript that interplays with other codes.

There are all sorts of APIs on the internet that take in information (day of week) and output information in response (weather forecast for that day)

Our project 'Domb and Domber' were essentially basic APIs.

With the Domination project we further explored the different way functions can be used to change the Dom.  An important lesson from this is the different structures and resulting effects these functions have on the DOM.

* **Side Effect Query Functions**-
        These functions won't `return` anything, just make changes to the current DOM. They also won't take in any complex objects, just strings! Remember that variables with strings in them can be used _exactly the same_ as the strings themselves.
* **Side Effect Node Element Functions**-
        These functions will take in an HTML Element, complete with all the sub-variables and and sub-sub-variables that come with it. They then manipulate that element according to the specifications below. 
* **Pure Functions Returning Node Elements**-
        These functions will all take in parameters and use them to make and return node elements. They don't do _anything_ to the DOM. So to test them, we have to use other functions.