### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

``` Javascript
let whatToDoForLunch = function(hungry, availableTime) {
  if (hungry) {
    if (availableTime < 20) {
      console.log("Grab lunch and bring back to the Lab to eat!");
    } else if ((availableTime >= 20) && (availableTime <= 30)) {
      console.log("Go try a place in Gastown!");
    } else {
      console.log("This is a Bootcamp & you should reconsider");
    }
  } else {
    console.log("Wait until you are hungry!");
  }
```