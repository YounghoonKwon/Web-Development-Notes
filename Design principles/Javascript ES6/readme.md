### Comparators

- === : also check data type
- == : check if the values are equal

### Properties

- innerHTML
- style
- firstChild

### Methods

- click()
- appendChild()
- setAttribute()

### Selectors

\$0 : chrome inspect current element
document.querySelector("h1").style.fontSize = "10rem"
document.querySelector("h1").style.classList.add("invisible")
document.getElementById("title").textContent = "Hello"
document.querySelector("a").attributes
document.querySelector("a").getAttribute("href")
document.querySelector("a").setAttribute("href", "https://www.google.com")

### Event Listener

document.querySelector("button").addEventListener("click", handleClick());
function handleClick(){
alert("clicked")
}
