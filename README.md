A mobile-first splash / flyer for The Sippy Cups
================================================

Hey there. In December 2012, the Alvin Sherman Library, Research, and Information Technology Center had **The Sippy Cups**--a kid-friendly, San Francisco Wiggle-like band [they do a fun pseudo-cover of the Ramones - which makes them super tolerable to any young parent]--and Public Library Services asked me (the Web Services Librarian) to make a splash where we could stream samples with the band's permission.

I took about a day and churned out the attached. This is a **mobile-first** single page splash designed with [SASS](http://sass-lang.com). There isn't a whole lot to it, but the presence of a CSS Gradient, Transition, and having to periodically resize or swap the background image for devices means that there is a separate _LTE IE8_ stylesheet and a few fixer-uppers in the CSS (like **.no-backgroundsize {}**) that depend on [Modernizr](http://modernizr.com).

But this is just a piece of the pie!
-----------------------------------

So, this is just a custom page template and part of a larger Wordpress site called [Concerts at the Alvin Sherman Library](http://sherman.library.nova.edu/concerts). I only included the relevant library. You should know that it inherits the stylesheet from the Sherman Library theme which includes the really important bits - like the grid! 