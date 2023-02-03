# Assignment-5
## Main Preview
![orignal](https://user-images.githubusercontent.com/97457589/215742895-cb0662b3-85c0-4811-9ace-9b0f0c666062.png)

## Task:-
## Add a button inside header [Pro Subscription], adding a recipes card and change copyright text
output:-
![DOM P2 SS](https://user-images.githubusercontent.com/97457589/215744447-a6172f77-9ad4-4709-9adf-7cfc6d5f2e32.png)


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
![output](https://user-images.githubusercontent.com/97457589/215745032-03cbec88-f1f2-437f-a6c0-1b6aefd8d26d.png)

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
