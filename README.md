A place for tricks of the trade.

# Table of Contents
1. [CSS](#CSS)
2. [JQuery](#jQuery)


# CSS

##### pseudo elements
You can add html elements using css like commas to lists by using `::after` css selector

after each `<span>` element add a comma =>
```
#sales-tool-office-list span::after {
  content: ', ';
}
```
on the last `<span>` in the list of spans dont have a comma =><br>
`::last-child` is a psuedo element css selector
```
#sales-tool-office-list span::last-child::after {
  content: none;
}
```

##### pseudo classes
give the color to all anchor tags on hover.
```
a:hover {
    color: #FF00FF;
}
```
# JQuery

shorthand document ready function
```
$(function(){ 
	//jQuery code here 
});
```

