# CSS

## Font in CSS

```

1. Color : red ; // changing the text color


2. font-family: sans=serif;   // lekhar font change kore;
// google thika o font anon jai


3. font-style : italic;  // tera .. backa font koron jai


4.font-weight: bold; // bold , lighter,, halka patla koron jai  
// like mota, moro, patla

5. text-decoration: underline; // underline koron er jonno use kora jai
// dotted, wavy, cyan dotted  .. use kora jai

6. font-size: 18px;  // font er size contron kora jai

7. text-align: center: // text center a aiye




```

# Border in CSS

```
1. border-style: dashed; // border er style change koron jai .. 
// solid, dashed, dotted, inset, outset.. last er dui ta sundor lage


2. border-width : 5px; // border er line mota choto korar jonno

3. border-color: gold; // border er color er jonno

4. border-radius: 10px;  // border er side ti kom korbar jonno

5. padding: 5px;  // padding a up-down approach a kaj kore.. eda barar koman jai


6.border-top-style: dotted; // border er uporer left to right (top) re control koron jai

7. border-bottom-style : dotted; // border er middle a left to right (bottom) re control koron jai

8. border-left-style: double; // left a sudu change

9. border-left-width : 10px; // border er left er j border ache ,, only tar size control kora jai

10. border-left-color: silver // border er left er side er color o change koron jai 


```


## Background in css

```
1. background-color : red; // background er color change korbo

2. background: liner-gradient(skyblue, lightgreen) // liner-gradient dile multiple color use korte parmu ek sathe

// but problem hoibo j color repeat hoiya jaibo

// use korte houbo

3. background-repeat: no-repeat;  // ata dile background repeat hoito na

// problem hoibo aber??
// joto tul lekha oto tuk color aibo .. full page aito na

4. background-attachement: fixed; // background fixed hoiya jaibo sob khane

5. background : linear-gradient(to right, skyblue, lightgreen)

    background : linear-gradient(to left, skyblue, lightgreen)

    background : linear-gradient(to top, skyblue, lightgreen)

// color shifting koron jai eda diya

6. background-image: url(photo.png)
// css diya photo add korte parmu.. background a

7.  background-repeat: no-repeat;
        background-attachment: fixed;

        // color er moto jamne use korso 

8. background-position: center; // background er position ata center a thakbo.. 

9. background-size: cover: // background er size fully cover hoiya thakbo


```

## Margin in CSS
```
1. margin: 0px; // margin is the space of an element

2. padding: 0px; // padding is the space between contact & border


 3. margin-top: 50px;
            margin-left: 50px;
            margin-bottom: 50px;
            margin-right: 50px;
// same process to shift by using left, bottom, right

4. margin: 50%; // we can also use percentage in margin

5. margin-left: auto; // box ta ekdom right a jaibo ga page er  // space aiya porbo left diya

6. margin-right: auto;  / box ta ekdom left a jaibo ga page er  // space aiya porbo right diya

// jodi 5 + 6 er sathe use kori.. horizonatally middle aiya porbo responsive type a 

```

## Float in css

```
1. float: left; // suppose ami ekta photo add korsi..photo sathe niche onnek text ache ..
// right to obiviosly gap thakbo

// jodi ai properties use kori
photo left a aiya porbo
// r left di photo right a aiya porbo 

2. float: right;
// same oi photo right a
// text sob left a same row te ---


// problem same line a suro hoibo
// akhon ki bhabe niche antam

3. clear: right; // jodi float: right; thake clear: right; left thakle left

4. clear : both; //  eda hoile to perfect 

```

## Position in css

```
1. position: static; // eda kichu change hoito na.. eda defaultv thake

2. position: relative; // eda hoile position re change korte parmu

2. a.   top: 50px;
   b.   left: 50px; // eda hoile px means empty space hoibo ki

3. position: absolute; // absolute means , eda ignore  boro.
// box ase, tar niche text ache.. absolute dile text ta box er piche aiya porbo.. ignore koira   

4. position: fixed; // etar position fixed thakbo.. scrool korle o.. tar pichone o textc thakbo

5. position: sticky; // eda hoile same jaiga te oi thakbo

   but  ai khane- top, bottom, left, right use korte oi hoibo..
   // eda same jaiba oi thake but scroll korle upore diya jai ga

``


## Pseudo in css
```
1. a:link{

}// atype a use korle link re activity change koron jaibo

2. a:visited{

}// atype use korle visit korar por aber j page amu ..ata re change koron jaibo

3. a:hover{

}// ata use korle j somoi cursor anmu oi time a live activity change korte parmu

4. a:active{

}// ai bhabe use korle jodi link click kori age  change hoibo tar properties jda dimu.. tar por kam korbo

5. li:nth-child(1){

}

// li ul edi html a banan pore.. jodi ami li re edit korte chai amne korte parmu..(number) j lekhmu oi number li er access paiya lamu

6. li:nth-child(odd){

}// odd, even o use korte parmu

7. li:nth-child(2n){

}

//2n means 2 ghor pore pore color change hoibo

```

## Shadow in css

```
1. text-shadow = 0px 0px 0px grey;

// text a shadow aibo .. 
first px ta + hoile right a
minus hoile left a
// second px positive number hoile down
minus hoile upore
// thrid is the blur
// 4rd one always is color

2. text-shadow = 10px 10px 10px grey, -10px -12px -2px red;
// dui ta shadow use korte parba ...sundor hoi


3. box-shadow: 5px 5px 5px black;
// same but box hoiya shadow hoi

```

## Icon in CSS
```
https://fontawesome.com/


here you get the icons
```

## Transform in Css

```
1. transform: translateX(150px) 
// suppose if have abox , that box have this properties then the box .. will shift to right.. if minus then left .. much more jaibo

2. transform: translateY(150px) // its for up &
 down approach

3. transform: translate(120px, 100px) // eta eek sathe o kora jai .. just X or Y thakto na

4. transform: rotateX(180deg) // 180 deg hoiya jaibo box er bitore  data
 
5. transform: rotateY(180deg)

6. transform: rotateZ(180deg)

7. transform: scaleX(2) // koto tuk spread hoi.. right left approach

8. transform: scaley(2) // koto tuk spread hoi.. up down approach

9. transform: scale(2, 3) // if ek sathe

10. transform: skewX(45deg) // ata box oi left right approach hoiya jai degree te

11. transform: skewY(45deg) // same but up down approach

12. transform: skew(45deg, 45deg) // ek sathe hoile


// ai sobti eksathe o use kora jai

13. transform: (1, 0, 0, 1, 0, 0)
// matrix combines the folllowing 
// scaleX()
//SkewY()
// skewX()
// scaleY()
// translateX()
// translateY()


```

