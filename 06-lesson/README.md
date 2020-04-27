# CSS box model 
<img src="box model diagram.png">

## 1. Borders
We can add border to an element in out page, and define the style of the border:
```css
border-style: solid;
border-width: 5px;
border-color: red;
```
We can declare the same style in one-line
```css
border: solid 5px red;
```

## Margin
`Margin` properties are used to create space around elements (outside of any defined border).

Negative values are not allowed. 
```css
* margin-top
* margin-left
* margin-right
* margin-bottom
```
```css
margin: 10px 10px 10px 10px;
```

## Padding
`Padding` properties are used to create space inside elements (inside of any defined border). 

Negative values are not allowed. 

```css
padding-top: 100px;
padding-left: 100px;
padding-right: 100px;
padding-bottom: 100px;
```
```css
padding: 10px 10px 10px 10px;
```

## Position
The `position` property specifies the type of positioning method used for an elemenet. 
1. **static** - default position for any element. 
```css
position: static;
```
2. **relative** - An element with `position: relative;` is positioned relative to its normal position. 
```css
position: relative;
```
3. **fixed** - An element with `position: fixed;` is positioned relative to the viewport. It always stays in same place, even if the page is scrolled. 

We can use `top`, `right`, `left`, `bottom` to place the element where we want. 
```css
position: fixed;
```

4. **absolute** - An element with `position: absolute;` is positioned relative to the nearest positioned ancesor.  

```css
position: absolute;
```
5. **sticky** -  An element with `position: sticky;` is positioned based on the user's scroll position. 
A sticky element is sort of `relative` and `fixed`, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place. (like position:fixed)
```css
position: sticky;
```
## z - index

The `z-index` property specifies the stack order of an element. 

An element with greater stack order is always in front - of an element with lower stack order. 
> Note: `z-index` only works on positioned elements. 

## Cursor 
We can define the shape of the mouse cursor. 
```html
<div style="cursor:wait;">wait</div>
```

## Display
The `display` property specifies if / how an element is displayed. 
1. `display: none;`   - does not show element in the page. 
2. `display: inline;` - show the elements in the same line.
3. `display: block;`  - show the elements so they take the full line. 
