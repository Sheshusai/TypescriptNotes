## OOPS in Typescrit

Object oriented programming is a programming model that organizes software design around data, or objects rather  
than functions and logic. An object can be defined as a data feild that has unique attributes and behaviour.  

1. Classes
2. Abstract Classes
3. Interfaces
4. Access Modifiers

```
class Project {
  name: string;
  budget: number:  // get error if strictPropertyIntitialization set to true

  constructor(name: string, budget: number) {
    this.name = name;
    this.budget =  budget;
  }

  printBudget() {
    console.log(`${this.name} has a budget of ${this.budget}' }
  }
}

const coolProject  = new Project('CoolProject', 10000);
coolProject.printBudget();
 ```   
