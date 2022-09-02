# HTML-CCS-and-JV
## cheat sheet

### HTML: VS code
#### get template setup
```
!
and
html:5
```

#### ramdom words
```
lorem + number
```

#### EM is xx times 12

#### get image from the file
```
../ from outside folder

./ inside the folder
```
#### class vs id css
```
. for class use it multiple time
# for ID ue it for unique item
```

#### order of Universal, element, class and id
first Universal, second element, third class and last id

#### position
absolute box need to have relative section. need a container which is section

#### Pseudo Class
```
## touch
button:hover {
  background-color: #772014;
  color: #fff;
}

## click
/* The user is actively pressing down on the element */
button:active {
  font-size: 180%;
  box-shadow: 0 0 10px #000 inset;
}

/* The element is currently in focus, either by tabbing to or clicking on it */
button:focus {
  outline: none;
  border-color: #8ac4ff;
}

transition duration 1st when touch the box will change
```

```

.hide {
  display: none;
}

.myDIV:hover + .hide {
  display: block;
  color: red;
}
```

#### EMMT know of quickly write the code

#### parent child and sibling
>parent<br/>
 >> child
 >> sibling

#### create varable 
```
:root {
  /* declare a variable with `--` syntax */
  --dark: #13293d;
  --light: #fff;
  --navlink-color: #b9c6ae;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1%;
  /* use CSS var() function to reference a variable created above */
  background-color: var(--dark);
  color: var(--light);
}

```
