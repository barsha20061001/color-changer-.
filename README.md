# colour changer 
projects on js basics

## PROJECT LINK
[click here](https://stackblitz.com/edit/stackblitz-starters-mlsobw5c?file=index.html)

# Live site
[Live Demo](https://barsha20061001.github.io/js-projects/)

# Screenshot 
of the project when clicked on olivedrab color

<img width="1917" height="966" alt="Screenshot 2025-07-14 213321" src="https://github.com/user-attachments/assets/00784165-8f97-4a32-bb4f-294130971fc8" />



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
