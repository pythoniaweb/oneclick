> # What’s New?
> * Anti Bot <span class='badge'>protection</span>
> * Anti Captcha Code Change <span class='badge'>protection</span>
> * Acceskey API <span class='badge'>protection</span>
> * Remaked <span class='badge'>bug fix</span>
> * New Example <span class='badge'>example</span>

# OneClick Captcha
## Start
OneClick Captcha is a easy and helpful captcha.
Easy to setup
Easy to add own function after verify
Easy to found bots

## Adding Captcha 

First u need add this code intro code

EXAMPLE 

```html
<head> U code... </head>
And here u can add captcha
<body> U code... Or here u can add captcha </body>
```

U need add this scripts

```html
<div class="captcha-code"></div> <!-- ACCES API FOR CAPTCHA (ANTI IFRAME)  NEED -->
<div id="captcha-element"></div> <!-- Here will be captcha -->
<script src="https://oneclick-2.sdddddddada.repl.co/script.js" id="1click" accesskey="websitelink"></script> <!-- Import captcha WARNING EDIT acceskey to u website url -->
```

Done captcha added!

## Creating a function if captcha done

for example create button

```html 
<button id="demo" onclick="checkcaptcha()">Verify.</button>
```
Importing captcha 
```html
<div class="captcha-code"></div> <!-- ACCES API FOR CAPTCHA (ANTI IFRAME)  NEED -->
<div id="captcha-element"></div> <!-- Here will be captcha -->
<script src="https://oneclick-2.sdddddddada.repl.co/script.js" id="1click" accesskey="websitelink"></script> <!-- Import captcha WARNING EDIT acceskey to u website url -->
<button id="demo" onclick="checkcaptcha()">Verify.</button>
```
Adding a example function and check
```html
<div class="captcha-code"></div> <!-- ACCES API FOR CAPTCHA (ANTI IFRAME)  NEED -->
<div id="captcha-element"></div> <!-- Here will be captcha -->
<script src="https://oneclick-2.sdddddddada.repl.co/script.js" id="1click" accesskey="websitelink"></script> <!-- Import captcha WARNING EDIT acceskey to u website url -->
<button id="demo" onclick="checkcaptcha()">Verify.</button>

<script>
//Yes its very basic script to check captcha
function checkcaptcha() {
   const iframe = document.getElementById("captchacheckid");// accessing the captcha element
  const iWindow = iframe.contentWindow;// accessing the captcha element
const iDocument = iWindow.document;// accessing the captcha element

// accessing the captcha element
const element = iDocument.getElementById('click').checked;
if(element == true){
  //Add u code if captcha done
  window.location.assign("https://google.com/") //u cann delete this stroke its just for example
}
 
}


  
  </script>
```
Done

# Example Captcha
If u want to see captcha (without function like redirect to other page if done) here is it

<div class="captcha-code"></div>
<div id="captcha-element"></div>
<script src="https://oneclick-2.sdddddddada.repl.co/script.js" id="1click" accesskey="pythoniaweb.github.io/oneclick/#"></script>
