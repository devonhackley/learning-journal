# LJ Code 201 - Day 3

Day 3. It's crazy that it's only been three days. It feels like we've been working for a least a week already. Compared to the first couple of days, I felt like I've learned so much. Coming into this I wasn't really comfortable with CSS and HTML, though I still don't feel amazing about it, I defintely think that I am starting to hold my own.

Today we discussed a lot about boxes in html and loops in javascript. I felt like after today's lesson I feel better about my understanding with boxes and its associated properties. I wasn't too confused with loops, I think having prior coding experience really did help me, not just in solidifying the knowledge I have but it gave me the opportunity to see how its done in javascript. Not too different from what I've seen before though.


If statement, within a for loop, within a while. Look at me haha.
```
while(userTries <= 6){
  var answer7 = prompt(seventhQuestion);
  userTries++;
  console.log('answer7: ', answer7);
  var userCorrect = false;
  for (var i = 0; i < answerArray.length; i++) {
    if(answer7 === answerArray[i]) {
      console.log('answerArray[i]: ', answerArray[i]);
      alert('That is correct!');
      userScore++;
      alert('Your Score: ' + userScore);
      alert('Possible answers: ' + answerArray);
      userCorrect = true;
      break;
    }
  }
  if (userCorrect === true){
    break;
  }
}

```

I'm hoping with the next couple of days we really dive into layouts of our pages and hopefully get some group work in. I don't have a lot of experience in coding in groups so that is one of the things I'm most excited about.
I'm also glad I got my linter to work and actually used the dev tools. Both are defintely handy.
