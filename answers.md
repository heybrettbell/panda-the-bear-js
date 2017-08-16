 ## Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead.

 image = document.querySelector(".profile-image").src = "images/chappelle.png";
 "images/chappelle.png"


## Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.

image = document.querySelector(".photography").src = "https://placebear.com/325/325";

## Select the heading that says "Panda the Bear" and change it to your own name.

title = document.querySelector("h1").innerText = "Brett Bell";

## Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector)

work = document.querySelector("#employment > h3").innerText = "Work History";

## Change the colour of the body.

body_colour = document.body.style.color = "blue";

## Change the colour used by the highlight class.

for (i = 0; i < highlight.length; i++) {highlight[i].style.color = "yellow"};

## Change the font family of the h1 to 'monospace'.
var title = document.querySelectorAll("h1");
for (i = 0; i < title.length; i++) {title[i].style.fontFamily = "monospace"};

## Find a way to select the round icons in the sidebar and then change their colour.
circles = document.querySelectorAll(".action-icon-bg");
for (i = 0; i < circles.length; i++) {circles[i].style.backgroundColor = "red"};

## Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself".
document.getElementById("name").placeholder = "Identify Yourself";

## Change the placeholder attribute of the message field to "state your business".
document.getElementById("message").placeholder = "State your business";


## Give the name field a "value" attribute of "your nemesis".
document.getElementById("name").value = "Your nemesis";

## Change the value attribute of the email field to "koalathebear@gmail.com".
document.getElementById("email").value = "koalathebear@gmail.com";

## Change the value of the submit button on the contact form to "En garde!".
document.getElementById("submit").value = "En garde";

## We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute).
document.getElementById("submit").disabled = true;

## We should help Panda protect their privacy by clearing their personal details from the sidebar. You can use reset() to do this.
document.getElementById("myForm").reset();
