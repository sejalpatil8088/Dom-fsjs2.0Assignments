# Assignment-5
## Main Preview

## Task:-
##Add a button inside header [Pro Subscription], adding a recipes card and change copyright text
output:-


```
// add button
let button = document.createElement("a");
let buttonText = document.createTextNode("Pro Subscription");
button.appendChild(buttonText);

let proSubcription = document.querySelector(".navbar .nav-center div:last-child");
proSubcription.appendChild(button);
button.classList.add("btn");
button.style.cursor = "pointer";
```

output:-
```
// adding Receipe
let recipesList = document.querySelector(".recipes-container .tags-container div")

let newRecipes = document.createElement("a");
let newRecipesName = document.createTextNode("chinese(7)");
newRecipes.appendChild(newRecipesName);

recipesList.appendChild(newRecipes);
recipesList.style.cursor = "pointer";

// Add recipe card
// add div
let card = document.querySelector(".recipe-gallery");

let newCard = document.createElement("div");
card.appendChild(newCard);
newCard.classList.add("card");
// add image
let selectCard = document.querySelector(".recipe-gallery .card:last-child");

let cardImage = document.createElement("img");
cardImage.src = "./img/recipe-6.jpeg";
cardImage.classList.add("recipe-img");
selectCard.appendChild(cardImage);

// add heading 
let heading = document.createElement("h5");
let addHeading = document.createTextNode("biryani");
heading.appendChild(addHeading);
heading.classList.add("recipe-name");
selectCard.appendChild(heading);

// add paragrap
let paragrap = document.createElement("p");
let addparagrap = document.createTextNode("prep:15min | cook:30min");
paragrap.appendChild(addparagrap);
paragrap.classList.add("recipe-disp");
selectCard.appendChild(paragrap);

```
