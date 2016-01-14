A place for tricks of the trade.

# Table of Contents
1. [CSS](#css)
2. [jQuery](#jquery)
3. [Random](#random)


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
# jQuery

shorthand document ready function
```
$(function(){ 
	//jQuery code here 
});
```

# Random

to tunnel to localhost:3000 on the same network for mobile testing (besides running the ios simulator on xcode)

`$ipconfig` from the command line

`en0` = ethernet0
`en2` = ethernet1

look for inet for ethernet0 (wifi) or ethernet1 (ethernet) 

`<inet>:3000` will forward to your static ip on your network and forward to port 3000