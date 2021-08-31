# What we will learn

 - Forms

 - The Conditional (Ternary) Operator 

The source of this summary [The first link](https://reactjs.org/docs/forms.html)

The source of this summary [The second link](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

______________________________________

## Forms

**What is a ‘Controlled Component’?**

 An input form element whose value is controlled by React.

**Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

The best way is wait to store the users responses from the form into state when they submit the form. because the data will be more reliable and it won't keep changing also storing unconfirmed information.

**How do we target what the user is entering if we have an event handler on an input field?**

it will runs once the input are changed.

______________________________________

## The Conditional (Ternary) Operator

**Why would we use a ternary operator?**

Shorten your if statements into one line of code with the conditional operator.

**Rewrite the following statement using a ternary statement**

if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

 let v = (x===y ?  console.log(true) : console.log(false))


 ## Things I want to know more about
 
about the Conditional (Ternary) Operator