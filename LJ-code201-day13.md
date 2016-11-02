# LJ Code 201 - Day 13

So we are halfway thru the third week. This week didn't start too well for me being sick, so my focus has been all over the place. Overall, I still feel somewhat ok, but as for the material this week, I feel like I'm really going to have to dive in deeper and review. Local storage is something that I am having a hard time wrapping my head around. I believe I got my assignment to work, but I dont think I fully understand why it works.

```
if (localStorage['storedClicks']) {
  var storedData = JSON.parse(localStorage['storedClicks']);
  for (var i = 0; i < productArray.length; i++){
    productArray[i].numOfClicks += storedData[productArray[i].name];
  }
  localStorage['storedData'] = JSON.stringify(storedData);
}else {
  for (var i = 0; i < productArray.length; i++){
    toStore[productArray[i].name] = productArray[i].numOfClicks;
  }
  localStorage['storedClicks'] = JSON.stringify(toStore);
}
```
This is the snippet that I use for my code. I guess I just don't fully understand the JSON methods(?).

In other news, I am very excited to get started on project week. There are actually a few ideas given today, that I think would be cool to work on. 
