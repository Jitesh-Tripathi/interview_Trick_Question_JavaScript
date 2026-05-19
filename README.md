# interview_Trick_Question_JavaScript
Sharing some good questions asked.

----------------------------------------

1)  Write a function that, given a 2D matrix of integers, returns the sum of elements within a given rectangular submatrix defined by its upper-left and lower-right coordinates.

2) What’s the output?
```
const a = {};
const b = { key: ‘b’ };
const c = { key: ‘c’ };

a[b] = 123;
a[c] = 456;

console.log(a[b]);


---------------------
a[b] = 123;  // a["[object Object]"] = 123
a[c] = 456;  // a["[object Object]"] = 456  ← overwrites 123

console.log(a[b]); // a["[object Object]"] → 456
```
Answer : 456

3) What’s the output?
```
function checkAge(data) {
  if(data === { age: 18 }) {
    console.log('You are an adult!');
  } else if (data == { age: 18 }) {
    console.log('You are still an adult.');
  } else {
  console.log(`Hmm.. You don't have an age I guess`);
  }
};


checkAge({ age: 18 });

```

Answer: it will print console.log(Hmm.. You don't have an age, I guess);

4)  What’s the output?
```
for( var i = 0; i < 5; i++) {
  setTimeout(function() {
    console.log(i);
  }, 1000);
};
```
Answer:  5



5) What’s the output?
```
for( let i = 0; i < 5; i++) {
  setTimeout(function() {
    console.log(i);
  }, 1000);
};

    
```
Answer:  0,1,2,3,4,5



6) Promise.all() vs Promise.allsettled() vs Promise.race() vs Promise.any()

Answer

7) What Promise returns?

Answer: pending fullied rejected

8) What is Proimise channing?

Answer

9) What is React-Window lib, and why is it used?

Answer: To handle a long list

10) React reconciliation vs React Fibre

Anwser

11) What is a higher-order component (HOC) vs. a custom hook?

Answer

12)pure component in functional vs class React?

Answer

13) Write a JavaScript function.         Input -” I love my India”.    ——- > output - “Aidni Ym Evol I".

Answer

14) What is closer, and write a function of closure ?

Answer

15)What are higher order fucntion ?

Answer

16) What types of errors in JavaScript ?

Answer

17) What is TDZ?

Answer

18)What is reconciliation in React ?

Answer

19)What are the controlled and uncontrolled components ?

Answer

20) What are workers and clusters in Node.js?

Answer

21) What is the difference between const and let?

Answer

22) Redux is unidirectional or bidirectional & why ?

Answer

23) What are shallow copy and deep copy  in JavaScript?

Answer

24) Write an interface in TypeScript?

Answer

25) What is different between any and unknown types in TypeScript?

Answer

26) 3 Core Features of Redux. 

Answer

27) Authentication vs. Authorisation?

Answer

28) Thunk vs Saga in Redux? What is middleware ?

Answer

29) Error boundary in React and how to use it in code ?

Answer

30) What is re-rendering in React ?

Answer

31) Which Azure service is used to deploy the web application ?

Answer

32) What is App Insights in Azure ?

Answer

33) What are Azure Functions ?

Answer

34) What is IAM in Azure ?

Answer

35) What is MSAL ?

Answer

36 ) What is an identity token vs an Auth Token vs an Access Token  vs a Refresh Token?

Answer

37) What is a JWT Token ?

Anwser

38) What is API versioning, and what are Azure API Management (APIM) services

Answer

39) API rate limiting vs throttling ?

Answer

40) What are tuples in Typescript ?

Answer

41) Multi-threading vs. multi-processing ?

Answer

42) How to handle a large application when the node is a single thread ?





