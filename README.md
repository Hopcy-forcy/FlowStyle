# FlowStyle
 est un langage de style qui se compile en css 
 il prend en compte la plupart des selecteurs sans compter ses prepros selecteur
 ## Exemple
 ```css
   body{
      bg-color : red;
      if(bg-color == red){ text-color: black;}
      else{text-color : white;}
      if(page-width >= 600px ){}
      if(parent-width <= 100px){}
   }
   h1{
    if(body-bg-color == red ){
      text-color : green;
    }
   }
 ```

## Heritage 

```css
  h1..body {}
  //ou
  h1 {
    bg-color : body-bg-color;
    text-color : #btn-text-color;
  }
```

## syntaxe

```scss
  body {
      bg: {
          img : url("");
          color : #ffb;
          size : ;
          pos :;
      };
      text: {
          color : red;
          size : 16px;
          line : 12px;
          word :  30px ;
          letter : 12px;
          weigth : 100;
          style : italic;
          font : "Times New Roman",sans;
          overflow : break;    
      }
      shadow: ;
      size: width height ;
      height : ;
      width:;
          
     
  }
```
ou 

```scss
    body {
      bg-color : ;
      bg-img : ;
      bg-size :;
      text-font :;
      text-color :;
      text-style : ;
      text-align : ;
      
    }
```

fonction

```scss
 fn name() { bg-color : red; text-color : black}
 body {
  name();
  bg-color :white;
 }
```

opérations

```js
  $size : 20% * 5 / 34px;
  $bool : !true; 
```

<div style='background-color:#fff; heigth: 100px; color: red;'>dfd</div>




 


