# Assignment-9
## Main Preview
![orignal](https://user-images.githubusercontent.com/97457589/216294558-e6616761-10b9-47be-87c6-d7ee86f8b913.png)

## Task-1
## Change Title Color
output:-
![task1](https://user-images.githubusercontent.com/97457589/216294714-209fa64f-0a48-40a1-8f16-8744388f9341.png)

```
// change h1 color
let changeColor = document.querySelector(".caption h1");
changeColor.style.color = "red";
```
## Task-2
## Change Button background color after click.
output:-
![task2](https://user-images.githubusercontent.com/97457589/216294974-3263c183-11a0-4e64-b564-0ae270379175.png)
```
// change background color when we click the button


let btn = document.querySelector(".add-to-cart");
btn.addEventListener("click" , (event) => {
    event.target.style.backgroundColor = "red";
});

```
