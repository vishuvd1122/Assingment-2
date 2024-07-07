# Assingment-2



Assignment-2 Solutions 
Name-Vishu Diwakar
Uni. Roll number-2215001992

1.b) using tag

2.b) using p tag 

3.b) false

4.b) false
 
5.c) 10000000000

6.A-const names = people.map(person => person.name);
       console.log(names); 
   B-const peopleWithSalary = people.map(person => ({
      ...person,
      salary: 50000
      }));
      console.log(peopleWithSalary);
  C-const filteredPeople = people
      .filter(person => person.age > 30)
      .map(person => ({
       name: person.name,
       age: person.age
       }));
       console.log(filteredPeople);

7-function main(cb1, cb2, x, y) {
  const sum = cb1(x, y);
  const difference = cb2(x, y);
 return { sum: sum, 
              difference: difference }; 
}

function add(a, b) {
  return a + b;
}

function subtract(a, b) {
  return a - b;
}

const result = main(add, subtract, 11, 4);
console.log(result);

8-c)map function

10-C)[ ] 

11-B)display : none removes the element from the dom while visibility :            hidden just hides the element.

12.A)4 10 18

13.A) [1,2,3,4] 

