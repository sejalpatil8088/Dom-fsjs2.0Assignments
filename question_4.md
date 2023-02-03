# Assignment-4
## Main Preview
![ass4](https://user-images.githubusercontent.com/119742317/216633107-7fd1c6b2-9572-4ca0-91f2-dec00b817680.png)

## Task:-
## Change card stats background Color
output:-
![output4](https://user-images.githubusercontent.com/119742317/216633439-6a38c3cd-c82c-4049-9e0c-a53c1919759a.png)


```
//changing stats text color
let statColor = document.querySelectorAll("div .stat, .stat-value");
for(let i = 0; i < statColor.length; i++){
    statColor[i].style.color = "#fff";
}

// barbarian 
let barbarian = document.querySelector(".clash-card__unit-stats--barbarian");
barbarian.style.backgroundColor = "#ec9b3b";
barbarian.style.color = "#fff";

// archer 2
let archer = document.querySelector(".clash-card__unit-stats--archer");
archer.style.backgroundColor = "#ee5487";
archer.style.color = "#fff";


// giant
let giant = document.querySelector(".clash-card__unit-stats--giant");
giant.style.backgroundColor = "#f6901a";
giant.style.color = "#fff";

//goblin
let Goblin = document.querySelector(".clash-card__unit-stats--goblin");
Goblin.style.backgroundColor = "#82bb30";
Goblin.style.color = "#fff";

// wizard
let wizard = document.querySelector(".clash-card__unit-stats--wizard");
wizard.style.backgroundColor = "#4facff";
wizard.style.color = "#fff";
```
