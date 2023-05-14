# What I learned from the intro class

+ Review of machine learning
+ Web scraping
  Here is an example of scraping comments data from amazon.com with JavaScript:
  (Of course you can find the element and right click it and select `copy selector ` and then copy it then type `$$(" copied content ") ` in the console)

```javascript
let reviewText = "";

const reviewElements = $$(".review-text");

for ( let r of reviewElements) {
    reviewText += r.innerText + "\n";
}

console.log(reviewText);
```
