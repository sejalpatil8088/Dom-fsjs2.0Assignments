# Assignment-2
## Main Preview
![orignal](https://user-images.githubusercontent.com/97457589/215530350-ee60d7cf-1985-4135-9a71-0fa3330d7be9.png)

## Task-1
## Changing Accordian background color.

output:-
![task6](https://user-images.githubusercontent.com/119742317/216393876-ff7edbe0-5fda-4940-a942-be3f224cf933.png)
```
// change h3 background color
let h3colors = document.querySelectorAll(".accordian h3");
for(var i=0; i<h3colors.length; i++){
    h3colors[i].style.backgroundColor = '#dadaf8';
}


//change contact menu to projects
let changemenu = document.querySelector("header nav ul li:nth-child(3)");
changemenu.innerText = "Projects";
```
## Task-2
## Adding accordian
output:-
![task7](https://user-images.githubusercontent.com/119742317/216396287-985ac529-00a2-4c44-bfb8-1d3815f6045c.png)

```
// Adding accordian

let accordianAdd = document.createElement("div");
let accordianWrapper = document.querySelector(".accordian-wrapper");
accordianWrapper.appendChild(accordianAdd);

// adding class name in new accordian

let element = document.querySelector(".accordian-wrapper div:last-child");
element.classList.add("accordian");

// Adding H3 inside accordian

let addH3 = document.createElement("h3");
let addH3text = document.createTextNode("Skills");
addH3.appendChild(addH3text);

let accordianHeading = document.querySelector(
  ".accordian-wrapper .accordian:last-child"
);
accordianHeading.appendChild(addH3);

addH3.style.background = "#dadaf8";
// Adding Paragraph inside accordian

let addpara = document.createElement("p");
let addptext = document.createTextNode(
  "I posses a very good command over the Full Stack Development technologies like MERN which can be seen in my work over the Github"
);
addpara.appendChild(addptext);

let accordianpara = document.querySelector(
  ".accordian-wrapper .accordian:last-child"
);
accordianpara.appendChild(addpara);

// Add click function in last accordian

let lastAccordian = document.querySelectorAll(".accordian:last-child h3");
lastAccordian.forEach((element) => {
  element.addEventListener("click", () => {
    let para = element.nextElementSibling;
    if (para.style.display === "block") {
      para.style.display = "none";
    } else {
      para.style.display = "block";
    }
  });
});
```
