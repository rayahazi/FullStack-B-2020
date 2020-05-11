# CSS selectors

* Selects only the p that is right after the div
```css
div + p {
    /*Some code*/
}
```
* Selects only the p that are inside the div
```css
div > p {
    /*Some code*/
}
```
* Selects only the first-child in element that is also p: 
```css
p:nth-child(1) {
    /*Some code*/
}
```
* Hover: when we move the mouse over an object. 
```css
button:hover{
    /*Some code*/
}
```
* Checked: when we select an input(in this example: input(checkbox))
```css
input:checked + label {
    /*Some code*/
}