# css-presentation

#relative

 This positioning is one of the most confusing and misused.It means is "relative to itself". If you set position: relative; on an element but no other positioning attributes (top, left, bottom or right), it will not effect it's positioning, it will be exactly as it would be if you left it as position: static;
 But if you do give it some other positioning attribute, say, top: 10px;, it will shift it's position 10 pixels DOWN from where it would normally be.
There are two other things that happen when you set position. One is that it introduces the ability to use z-index on that element, which doesn't really work with statically positioned elements. Even if you don't set a z-index value, this element will now appear on top of any other statically positioned element. The other thing that happens is it limits the scope of absolutely positioned child elements. Any element that is a child of the relatively positioned element can be absolutely positioned within that block.
