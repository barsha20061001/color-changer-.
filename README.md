# colour changer 
projects on js basics

## PROJECT LINK
[click here](https://stackblitz.com/edit/stackblitz-starters-mlsobw5c?file=index.html)

# link 
[click here](https://stackblitzstartersmlsobw5c-1sss-dku6uoxj--8080--96435430.local-credentialless.webcontainer.io)

# solution code

```javascript

const buttons = document.querySelectorAll('.button');
const body = document.querySelector('body');

buttons.forEach(function (button) {
  console.log(button);
  button.addEventListener('click', function (e) {
    console.log(e);
    console.log(e.target);
    if (e.target.id === 'grey') {
      body.style.backgroundColor = e.target.id;
    }
    if (e.target.id === 'white') {
      body.style.backgroundColor = e.target.id;
    }
    if (e.target.id === 'blue') {
      body.style.backgroundColor = e.target.id;
    }
    if (e.target.id === 'yellow') {
      body.style.backgroundColor = e.target.id;
    }
    
  });
});



```
