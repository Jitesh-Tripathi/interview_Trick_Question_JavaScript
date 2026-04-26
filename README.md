# interview_Trick_Question_JavaScript
Sharing the Some good question asked.

#question1 

Write a function that, given a 2D matrix of integers, returns the sum of elements within a given rectangular submatrix defined by its upper-left and lower-right coordinates.

**Answer: 456**

Why  : 

#question2

What's the output?

const a = {};


const b = { key: 'b' };


const c = { key: 'c' };


  a[b] = 123;

  
  a[c] = 456;

  
console.log(**a[b]**);


**Answer** : 456 


Why  : 


#question3


What's the output?


  function checkAge(data) {

  
    if(data === { age: 18 }) {

    
      console.log('You are an adult!');

      
    } else if (data == { age: 18 }) {

    
      console.log('You are still an adult.');

      
    } else {

    
      console.log(`Hmm.. You don't have an age I guess`);

      
    }

    
  }; 

  
_checkAge({ age: 18 });_



Answer: it will print console.log(`Hmm.. You don't have an age I guess`);


Why:


#question4

What's the output?


 for( var i = 0; i < 5; i++) {

  setTimeout(function() {

  
    console.log(i);

    
  }, 1000);

  
 };

**Answer:  5**


Why 


#question5 


What's the output?
 
 
 for( let i = 0; i < 5; i++) {
 
  
  setTimeout(function() {
  
    
    console.log(i);
  
  
  }, 1000);
 
 
 };

**Answer:  0,1,2,3,4,5**


Why
 

