# Frequently Used JS Codes

<b>Get all the child elements:</b>
<pre><code>var all_checkbox = document.getElementById("gg_data_tags").querySelectorAll('input[type="checkbox"]')
</pre></code>

<b>Loop for the child elements:</b>
<pre><code>all_checkbox.forEach(function (item) {
  item.checked = false
})
</pre></code>


<b>Add Class to an element:</b>
<pre><code>this.result_player_two.classList.add("current-player")
</pre></code>

<b>Remove Class from an element:</b>
<pre><code>this.result_player_one.classList.remove("current-player")
</pre></code>


<b>Force checkbox to check:</b>
<pre><code>document.getElementById("checkbox").checked = true;
</pre></code>

<b>Force checkbox to uncheck:</b>
<pre><code>document.getElementById("checkbox").checked = false;
</pre></code>

<b>Push data to array </b>

<pre><code>var sel_authors = new Array()
sel_authors.push("john", "mahbub", "alam", "khan")
</pre></code>


<b>Random value betwen two numbers</b>
<pre><code> randomIntFromInterval(min, max) { // min and max included 
    return Math.floor(Math.random() * (max - min + 1) + min)
  }
</pre></code>

<b>Join Array:</b>

<pre><code>const fruits = ["Banana", "Orange", "Apple", "Mango"];
let text = fruits.join(); 
</pre></code>

<b>Array Map:</b>

<pre><code>const numbers = [65, 44, 12, 4];
const newArr = numbers.map(myFunction)

function myFunction(num) {
  return num * 10;
}
</pre></code>
