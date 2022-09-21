### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function (hungry, availableTime) {
  if (hungry === false) {
    return "Get back to work!"
  }
  else {
    if (availableTime < 20) {
      return "Pick something up and eat it in the lab."
    }
    if (availableTime > 30) {
      return "We're in a bootcamp so no much time to spare."
    }
    else return "Try a place nearby."
  }
}
```
