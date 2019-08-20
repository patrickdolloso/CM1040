# Week 14: Intro to JS - continue
```JS
document.getElementById("play").style.textAlign="center";
```

```JS
var allh3 = document.getElementsByTagName("h3");

var firsth3 = allh3[0];

firsth3.insertAdjacentHTML("beforeend","<p>Now on sale!</p>");
```

```JS
var allArticles = document.getElementsByTagName("article");

for(var i = 0; i < allArticles.length; i++)
{
    allArticles[i].style.textAlign="center";
}
```

```JS
document.getElementById("flower").style.borderStyle="dashed";

document.getElementById("flower").style.borderStyle="dashed";

document.getElementById("flower").style.borderStyle="dashed";

// to combine these:
document.getElementById("flower").setAttribute("style", "border-style:dashed; border-color:pink; border-width:10;");
```

```JS
document.getElementById("mediumA").onclick = function(){document.getElementsByTagName("body")[0].className="medium"};
```