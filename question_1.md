# Assignment-1
## Task -1
## Adding [hire me] button inside nav menu, change nav [Contact] buuton to [Projects] and Removeing footer social icons.
###Output :-
![task1](https://user-images.githubusercontent.com/119742317/216367685-47296129-843d-4029-8e7d-8109770450d9.png)

```
// add hire me inside nav manu
  const list = document.createElement("li");
  const list_items = document.createTextNode("Hire Me");
  list.appendChild(list_items);

  const element = document.querySelector("ul")
  element.appendChild(list);


// change Contact to projects
let myproject = document.querySelector("header nav ul li:nth-child(3)");
myproject.innerText = "Projects";

```
## Task-2
## Changeing Header search field Placeholder text and hide [Hire Me] Button from nav menu.
####Output :
![task2](https://user-images.githubusercontent.com/119742317/216370247-363b5a43-e8d2-4a3f-9a88-67e359a270e3.png)

```
 // remove last nav menu
let remove = document.querySelector("ul")
 remove.removeChild(remove.children[3]);


// changing search field
let inputtext = document.querySelector("header .search-field input");
inputtext.placeholder = "Search my project";

```
## Task-3
## Changeing hero paragraph span text and display footer social icons.
####Output:-
![task3](https://user-images.githubusercontent.com/119742317/216370781-bd575e5e-14ba-4edf-af28-68fa0f50e26b.png)

```
// changing paragram 
let span1 = document.querySelector(".hero-section .hero-left-section p span:nth-child(3)");
span1.innerText = "an Employee";

let span2 = document.querySelector(".hero-section .hero-left-section p span:nth-child(5)");
span2.innerText = "iNeuron intelligence Pvt Ltd";

//changing search feild
let search = document.querySelector("header .search-field input");
search.placeholder = "Search";

// include footer icons
document.querySelector("footer ul").style.visibility = "visible";
document.querySelector("footer ul").style.visibility = "hidden";

```

## Task-4
## Changeing hero avtar image and restore placeholder text.
#### Output:-
![task4](https://user-images.githubusercontent.com/119742317/216387054-b1cfef31-ed61-48d2-b065-326074b9a231.png)
```
// change image 
let image = document.querySelector(".hero-right-section img").src="https://hiteshchoudhary.com/static/a8d73d1aac4c79e9bb689640e6090367/2eaab/person-image.jpg";

```
## Task-5
## Restore paragraph span text, Hero avtar image and adding a [Support Me] Button.
#### Output:-
![task5](https://user-images.githubusercontent.com/119742317/216387608-ebea697c-d039-401e-842d-4b1684c3a5d9.png)
```
// Add support me button
let button = document.createElement("button");
let buttonText = document.createTextNode("support me");
button.appendChild(buttonText);

let supportMe = document.querySelector(".hero-section .hero-right-section .hero-right-section-btns");
supportMe.appendChild(button);
```
