# This is a header
## Fun headers
### Is good to practice LOL
#### Now with four
##### with five #
###### This is the last one, i promise :P

Is good to learn while you practiced.


![Tanjiro Kamado]([https://octodex.github.com/images/yaktocat.png](https://static.wikia.nocookie.net/kimetsu-no-yaiba/images/d/dd/Tanjiro_Kamado_Full_Body_%28Anime%29.png/revision/latest?cb=20241010231004))


``` javascript
//breathing animation effect
var const breathingStyle = (element, scale = 1.05, duration = 1000) => {
  element.animate([
    { transform: `scale(1)` },
    { transform: `scale(${scale})` },
    { transform: `scale(1)` }
  ], {
    duration: duration,
    iterations: Infinity,
    easing: 'ease-in-out'
  });
};

// Example usage: applying breathing style to an element with id "sword"
const sword = document.getElementById("sword");
if (sword) breathingStyle(sword);
```
