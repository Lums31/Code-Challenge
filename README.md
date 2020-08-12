# Coding Challenge
For tokwa friends CJ and Jerome coding challenge.

__Instructions ❗__

1. fork this repo and.
2. clone your forked repo in your local machine.
3. Create a folder with your first name, and put your codes inside.
4. File to create, `index.html` and `index.js`
5. In your HTML file... create a form with two fields, `firstname` and `lastname` field with submit button.
6. In your js file..... use this API to validate the form in the HTML....




```js
// index.js


// Put your codes here for creating `FormValidator` function code.
// Hints :
// - form submit event listener inside the `FormValidator` function




// this must stay...
FormValidator({
    id: "formIdHere",
    rules: {
        firstname: "minLen:2", // means minimum length
        lastname: "maxLen:5", // means maximum length
    }
});

```

7. When the HTML form is submitted (form submit event), form validation starts , and console.log() if the `firstname` and `lastname` passed the validation(simple message).

8. When done, push the code in your repo and perform __pull request__ in this repo.

Goodluckz mga ka tokwa! 😊✌️
