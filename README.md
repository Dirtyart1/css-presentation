# css-presentation

#Relative

 This positioning is one of the most confusing and misused.It means is "relative to itself". If you set position: relative; on an element but no other positioning attributes (top, left, bottom or right), it will not effect it's positioning, it will be exactly as it would be if you left it as position: static;
 But if you do give it some other positioning attribute, say, top: 10px;, it will shift it's position 10 pixels down from where it would normally be.


[relative example](https://www.youtube.com/watch?v=YBJqKWXL2vg)


# Absolute 

**This type of positioning allows the user complete freedom to position any element of the webpage precisely where they want it(to the pixel).**

### VIDEO 
[absolute example](https://www.youtube.com/watch?v=-NrTyWT9l8A)

_"This is a very powerful type of positioning that allows you to literally place any page element exactly where you want it. You use the positioning attributes top, left bottom and right to set the location. Remember that these values will be relative to the next parent element with relative (or absolute) positioning. If there is no such parent, it will default all the way back up to the <html> element itself meaning it will be placed relatively to the page itself."_

![example image](http://www.iraqtimeline.com/maxdesign/basicdesign/images/absrel.png)

**This is a serious thing to consider every time you use absolute positioning. It's overuse or improper use can limit the flexibility of your site.**

_credit to css-tricks_
