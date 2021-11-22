### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true) {
    if (availableTime < 20) {
      console.log('scoop some dons and run it back QUICKTIMES');
    } else {
      if (availableTime <= 20 || availableTime <= 30) {
        console.log('you\'re chillin, touch gastown');
      } else {
        if (availableTime > 30) {
          console.log('oh? so you\'re chillin? go do ya damn homework');
        }
      }
    }
  } else {
    if (hungry === false) {
      console.log('wait til mans are marved you bum');
    }
  }
};
```
