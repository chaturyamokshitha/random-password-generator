CLICK HERE FOR THE OUTPUT:
    VERCEL LINK:https://random-password-generator-beryl-chi.vercel.app/

Introduction:
* This mini project using javascript generates random password for the user and allows to copy it every time button to generate is clicked

  Languages:
  1.HTML
  2.TAILWINDCSS
  3.JAVASCRIPT

  Code Explanation:
  *In HTML basically we are creating a input with type text so the password is diplayed in the input box and a button when clicked generates password
  and displays the password in input box.
  *In CSS the styles are applied accordignly.
  *In javascript :
    *we are accessing the input and button using the document.getElementById('name of id given in html ');
    *when the button is clicked we are calling a function called generatepassword().
  
  Generatepassword function-->
  *taking a pass variable which is empty string;
  *defining a length variable assinging as 12 which mean the length of password is 12.(we can take any length);
  *taking variables like uppercase,lowercase,number,symbol that needed to be included in the password
  *so how exactly we create is using math.random we are getting a number under the length of uppercase variable and flooring that number
  after flooring we are accessing using that index value and adding it to the pass variable which is empty.
  *the above step is followed for uppercase,lowercase,number,symbol variables.
  *but what if the length is less than 12 then we need to take care of that case
  *by taking a variable allchar which contains all variable values and adding this to pass like remaining variables
  until length is equal to 12.
  *Finally displaying the pass by manipulating styles
  
  
  
