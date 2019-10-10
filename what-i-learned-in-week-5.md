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