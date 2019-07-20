# Media Queries and user-select tutorial with example below:

---



## User-select example code given below:

```
.box1 {
    height: 100vh;
    width: 100%;
    background-color: red;
    padding: 20px;
    box-sizing: border-box;
    color: white;
    user-select: all;
}

.box1::selection {
    background-color: green;
}
```
## media quries example code:

> @media screen and (max-width:980){}

```

@media screen and (max-width:900px) {
    .box1 {
        background-color: yellow;
        font-size: 30px;
        color: black;
        box-sizing: border-box;
    }
}

@media screen and (max-width:780px) {
    .box1 {
        background-color: tomato;
        font-size: 25px;
        color: white;
        box-sizing: border-box;
    }
}

@media screen and (max-width:690px) {
    .box1 {
        background-color: blue;
        font-size: 20px;
        color: white;
        box-sizing: border-box;
    }
}
```
