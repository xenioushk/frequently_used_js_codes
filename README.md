# Frequently Used JS Codes

## Get all the child elements

```javascript
var all_checkbox = document.getElementById("gg_data_tags").querySelectorAll('input[type="checkbox"]')
```

## Loop for the child elements

```javascript
all_checkbox.forEach(function (item) {
  item.checked = false
})
```

## Add Class to an element

```javascript
this.result_player_two.classList.add("current-player")
```

## Add Multiple Classes to an element

````javascript
this.result_player_two.classList.add("current-player", "class_2", "class_3")```

## Remove Class from an element

```javascript
this.result_player_one.classList.remove("current-player")
````

## Add 'id' attribute to an element

```javascript
this.result_player_one.setAttribute("id", "my-id")
```

## Add custom attribute to an element

```javascript
this.result_player_one.setAttribute("data-score", "10")
```

## Remove 'class' attribute from an element

```javascript
this.result_player_one.removeAttribute("class")
```

## Remove Multiple Classes to an element

```javascript
this.result_player_two.classList.remove("class_2", "class_3")
```

## Force checkbox to check

````javascript
document.getElementById("checkbox").checked = true;```

## Force checkbox to uncheck

```javascript
document.getElementById("checkbox").checked = false;
````

## Push data to array </b>

```javascript
var sel_authors = new Array()
sel_authors.push("john", "mahbub", "alam", "khan")
```

## Random value betwen two numbers</b>

```javascript
 randomIntFromInterval(min, max) { // min and max included
    return Math.floor(Math.random() * (max - min + 1) + min)
  }
```

## Join Array

```javascript
const fruits = ["Banana", "Orange", "Apple", "Mango"]
let text = fruits.join()
```

## Array Map

```javascript
const numbers = [65, 44, 12, 4]
const newArr = numbers.map(myFunction)

function myFunction(num) {
  return num * 10
}
```

### More example

You can check more javascript example codes from [here](https://github.com/xenioushk/javascript_101).

## Acknowledgement

- [bluewindlab.net](https://bluewindlab.net)
