# Table of Contents


- [Horizontal Responsive Width](#horizontal-responsive-width)
- [Vertical Responsive Height](#vertical-responsive-height)

<p align='center'>
<img width="100%" height="auto" src='https://www.geo-jobe.com/wp-content/uploads/2018/12/a114bcde3596d40684499375ee80eea3.gif' alt='/' />
</p>

### Horizontal Responsive Width

```
@media only screen and (max-width: 360px) {
    body {background-color: red;}
}
@media only screen and (max-width: 480px) {
    body {background-color: blue;}
}
@media only screen and (max-width: 768px) {
    body {background-color: crimson;}
}
body {background-color: yellow;}
@media only screen and (max-width: 992px) {
}
@media only screen and (min-width: 1200px) {
    body {background-color: lime;}
}

```

### Vertical Responsive Height

```
@media (min-width: 480px) and (min-height: 720px) {
    body{background-color: red;}
}
@media (min-width: 992px) and (min-height: 720px) {
    body{background-color: yellow;}
}
@media (min-width: 992px) and (min-height: 1080px) {
    body{background-color: orchid;}
}
@media (min-width: 1440px) and (min-height: 720px) {
    body{background-color: crimson;}
}
@media (min-width: 1440px) and (min-height: 1080px) {
    body{background-color: black;}
}
@media (min-width: 1920px) and (min-height: 720px) {
    body{background-color: blue;}
}
@media (min-width: 1920px) and (min-height: 1080px) {
    body{background-color: lime;}
}
```
