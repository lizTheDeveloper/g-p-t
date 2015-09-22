## Livecoding samples

Work with these samples in order to explore the different behaviors of functions.
Cover:
* Writing a function
* Calling a function
* Return statements
* Storing a returned value in a variable
* Using previously set variables as arguments
* Calling a function as an argument
* Order of execution
* Variable Scope

```javascript
function pastryCost(numPastry) {
    return numPastry * 2.5;
}

var pastries = pastryCost(2);

function coffeeCost(numCoffee) {
    return numCoffee * 5.5;
}

var coffees = coffeeCost(2);

var subTotal = pastries + coffees;

function applyTax(tax, subTotal) {
    var taxTotal = subTotal + (subTotal * tax);
    return subTotal + tax;
}

var total = applyTax(0.825, subTotal);

function applyTip(total, tip) {
    var tip = total * tip;
    return total + tip;
}

var totalAfterTip = applyTip(total, 0.15);

console.log("Breakfast for two in San Francisco: " + totalAfterTip);
```