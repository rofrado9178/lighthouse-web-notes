### Tips

I am trying to make a function to decide for lunch according to hungry is true or false, and base on the time available,
if hungry and time less than 20 minutes, we need to eat in labs
if hungry and time 20-30 minutes , we can eat nearby
if hungry and time is more than 30 minutes, i limit max 30 minutes for lunch

```javascript
const whatToDoForLunch = function (hungry, availableTime) {
  if (hungry && availableTime <= 20) {
    console.log("Picked something up and eat it in the lab!");
  } else if (hungry && availableTime > 20 && availableTime <= 30) {
    console.log("We can try a place nearby!");
  } else if (hungry && availableTime > 30) {
    console.log(
      "We are in a bootcamp we should consider maximum 30 minutes for lunch"
    );
  } else {
    console.log("We can eat later !");
  }
};
```
