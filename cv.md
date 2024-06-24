# Tatiana Kiseleva

## Contact Info
* **email** tanja.kiseleva.92@gmail.com
* **phone** +79161008185
* **city** Khimki

##Skils

* Git, GitHub
* CSS (Framework Bootstrap, Preprocessor SCSS, BEM methodology)
* HTML
* JS

## Code examples

```
function{color:blue} findLongestWord(text) {
    let words = text.split(" ");
    let word = "";
    // for (let i = 0; i < words.length; i++) {
    //     if (word.length < words[i].length) {
    //         word = words[i];
    //     }
    // }
    for (let item of words) {
        if (word.length < item.length) {
            word = item;
        }
    }
    return (word);
}
const longestWord = findLongestWord("Lorem ipsum dolor sit 
amet, consectetur adipiscing elit. Praesent 
rutrum, quam sit amet semper tempus, velit 
nibh pellentesque dui, nec consectetur 
erat orci et libero. ");
console.log(longestWord);
```

![me](/C:\Users\Laptop\Downloads/foto.html "my foto")