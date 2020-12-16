---
title: "Copy Paste Programming"
date: "2014-11-27"
description: Sometimes you need to make a change that's similar to one you've made before, or you have some logic that's performed in more than one location, and it needs to change.
---

![CopyPasteProgramming](images/CopyPasteProgramming-300x300.jpg)

Sometimes you need to make a change that's similar to one you've made before, or you have some logic that's performed in more than one location, and it needs to change.  The temptation, of course, is to simply copy the code you need from the first place where it's used to any other places where it can be used.  This works, and it's a great way to increase the total number of Lines of Code that you are able to produce, but it results in Spaghetti Code, Technical Debt, and is probably the biggest way in which the [Don't Repeat Yourself principle](http://deviq.com/don-t-repeat-yourself) is violated.

Rather than copying code from one place to another, create an abstraction to contain the logic, and route all of the code through this abstraction.  If this creates more coupling between modules than you want, then it may be acceptable to have one such abstraction in each logical module, so that within the context of a given module, no duplication of this logic exists.

## See Also

[Version Control](http://deviq.com/version-control)

[Spaghetti Code](http://deviq.com/spaghetti-code)

[Technical Debt](http://deviq.com/technical-debt)

[Don't Repeat Yourself Principle](http://deviq.com/don-t-repeat-yourself)

## Reference

[NimblePros AntiPatterns 2012 Wall Calendar](http://nimblepros.com/products/software-craftsmanship-2012-calendar.aspx)

[Principles, Patterns and Practices of Mediocre Programming](http://bit.ly/mediocreppp)