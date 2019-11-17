# `What I Learned In Week 10`

## `Grid Template Areas`
* I loved this topic. I think its very convenient and fun. It was easy to understand and use.

```
#app {
  display: grid;
  height: 1300px;
  width: 2000px;
  grid-template-areas: 
    "area-1 area-1 area-1 area-1"
    "area-2 area-3 area-3 area-6"
    "area-2 area-4 area-4 area-6"
    "area-5 area-5 area-5 area-5"
  ;
  grid-template-rows: 1.7fr 2.5fr 2.5fr 1.7fr;
  grid-template-columns: 1fr 2fr 2fr 1.5fr;
}
```

```
#header {
  grid-area: area-1;
}

#footer {
  grid-area: area-5;
}
```

---

## `Responsive Grid`

* We use responsive grid when we want to make the layout adjustable to different devices such as iphone, desktop and Ipad.
* We use @media for the adjustment. We can have different layouts for different screen sizes. The following codes are used on my holy-responsive-grid project.
  
```
#app {
  font-size: 8em;
  text-align: center;
  height: 100vh;
  display: grid;
  grid-template-rows: 20% 30% 30% 20%;
  grid-template columns : 20% 30% 30% 20%;
  grid-template-areas:
    "hd1 hd1 hd1 hd1"
    "nv1 ar1 ar1 ad1"
    "nv1 ar2 ar2 ad1"
    "ft1 ft1 ft1 ft1"
}
```
```
@media (max-width:500px) {
  #app {
    font-size: 3em;
    text-align: center;
    height: 100vh;
    display: grid;
    grid-template-rows: 15% 10% 25% 10% 25% 20%;
    grid-template columns : 100%;
    grid-template-areas:
      "hd1"
      "nv1"
      "ar1"
      "ad1"
      "ar2"
      "ft1"
  }
}
```
---

## `Japanese Grid`
* This project was very hard and confusing to me. I struggled from the beginning till the end. We worked with Kejal and it became easier. We used two laptops and figured it out.

## `Objects`

