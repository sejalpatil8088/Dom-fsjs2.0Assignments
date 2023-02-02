# Assignment-1
## Task -1
## Adding [hire me] button inside nav menu, change nav [Contact] buuton to [Projects] and Removeing footer social icons.
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
