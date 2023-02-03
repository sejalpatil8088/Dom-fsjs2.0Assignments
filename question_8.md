# Assignment-8
## Main Preview
![main-preview](https://user-images.githubusercontent.com/97457589/216287788-0ad39682-2f50-467e-bb95-230a047595ad.png)


## Task-1
## Making scrolling sidebar
output:-
<img width="770" alt="ass8 1-after" src="https://user-images.githubusercontent.com/97457589/216288332-d845b9e5-563c-45f0-b789-86659bb01241.png">

```
 // Adding scroll in sidebar
let aside = document.querySelector(".new");
aside.style.overflowY = "scroll";

// Adding content in sidebar

let addHr = document.createElement("hr");
addHr.classList.add("hr-line");
aside.appendChild(addHr);

let addH2 = document.createElement("h2");
addH2.classList.add("new-head");
let addH2Txt = document.createTextNode("This is my customer heading");
addH2.appendChild(addH2Txt);

aside.appendChild(addH2);

let addP = document.createElement("p");
addP.classList.add("new-p");
let addPtxt = document.createTextNode("The most important first step is to satisfy the customer by meeting their expectations.");
addP.appendChild(addPtxt);

aside.appendChild(addP);
```
## Task-2
## Change background
output:-
![ass8 2-after](https://user-images.githubusercontent.com/97457589/216290355-24bbaf9b-2e9f-4db0-90a3-d1be24e2ae4a.png)


```
// change background color
let bgc = document.querySelector("body");
bgc.style.background = "#fff";

```
## Task-3
## Create responsive nav menu
output:-
![ass8 3-after](https://user-images.githubusercontent.com/97457589/216289616-948e8702-80e2-41ac-97ed-5cefe9c31056.png)
```
// Nav menu

let navIcon = document.querySelector("nav button span");

navIcon.addEventListener("click", (click) => {
  let navItems = document.querySelector("#navbarTogglerDemo01");
  if ((navItems.style.display = "none")) {
    navItems.style.display = "block";
  } else if ((navItems.style.display = "block")) {
    navItems.style.display = "none";
  } else {
    navItems.style.display = "none";
  }
});
```


