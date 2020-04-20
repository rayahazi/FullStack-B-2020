# Lesson 05

## Selectors
1. Name of variable. 
for example: 
```css
p{

}
h1{

}
```

2. Id: This can modifiy only one variable. 
We can't have two identical id's. 
```html
<h1 id="headerId"></h1>
```
```css
#headerId{

}
```

3. Class: class can modify many variables that have the same class. 
(It can be from a diffrent type). 
```html
<h3 class="test"></h3>
<input type="number" class="test"/>
```
```css
.test{

}
```

## Range for input:
1. Case the type = text (string)
```html
<input type="text" required minlength="2" maxlength="8"/>
```
2. Case type = number
```html
<input type="number" min="9" max="120"/>
```
## Div -  block element
We use div to separate blocks of code in the HTML page. 
```html

<div>
            
</div>
```
## Span - Inline element
We use span in text. (when we want to change only small piece of code)
```html
<span></span>
```

## Label - תוית
Label will be used usually with input tags. 
Label will not go to the next line. Which is usefull for input tags.
(Similar to p tag)
```html
<label></label>
```

## Radio button
```html
<input type="radio"/>
```
## Checkbox
```html
<input type="checkbox"/>
```

## Video
1. from youtube:
Go to the video, right click, and `העתק קוד הטמעה`
```html
    <iframe width="560" height="315" src="https://www.youtube.com/embed/Zz1DrO0_aOg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

2. from local folder:
```html
<video controls>
    <source src="" type="video/mp4">
</video>
```
