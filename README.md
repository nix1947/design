## Classes and Id's
* used to desing the particular section.
* Id's used once ony inside a HTML document. 
* using Id's is not good practive

## Box Model.
* Margin.Border.padding.content.
* height and width of the element is added for the content + padding, which won't use
* The solution is to use box-sizing. 


## HTML elements
* Block elements
* Inline elements ` images, links, strong`
* cannot use height and width in inline elements. need to use features to using display: block block-inline to use height and width.

## Default use 
```
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Helvetica;
}
``` 

## clear fix class
```
.clearfix:after{
    /* 
     <div class="clearfix"></div>
     put this element before the element which you want to push down at the bottom.
    */
    content: "";
    display: table;
   clear: both;
}
```

## Making circle
```
border-radius: 50%
```

## Element Positioning
* all elements are relative position by default.
* with absolute positioning we can put element anywhere inside their parent element.
* To enable absolute position in element, parent position should be relative by declaring `position: relative;`
