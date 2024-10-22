# Asynchronous JavaScript at Netflix, Microsoft and the World - JSConf.Asia 2015 #

This is a presentation at [JSConf.Asia](http://jsconf.asia) on [Asynchronous JavaScript at Netflix, Microsoft, and the World](jsconfasia-2015.pdf).

## Outline ##

What's does a mouse drag event have in common with an Array of numbers?

The answer to this question may surprise you: they are both collections. This key insight holds the key to dramatically simplifying asynchronous programming in JavaScript. In this talk you will learn how you can use the familiar JavaScript Array#extras methods to create surprisingly expressive asynchronous programs. Using just a few functions, you will learn how to do the following:

- Declaratively build complex events out of simple events (ex. drag n' drop)
- Coordinate and sequence multiple Ajax requests
- Reactively update UIs in response to data changes
- Eliminate memory leaks caused by neglecting to unsubscribe from events
- Gracefully propagate and handle asynchronous exceptions

In this talk we'll be exploring the Reactive Extensions for JavaScript (RxJS) library which allows us to treat events as collections. We'll also contrast RxJS with Promises and other popular approaches to building asynchronous programs in JavaScript. We'll also dive into the future with RxJS with generators, ES7 asynchronous functions, and even query transformations.

We'll talk about how this approach was used at Netflix, Slack, and Microsoft with great success with solving such problems as asynchronous search via autocomplete, scrolling, and infrastructure such as multiplexed WebSockets.

## Resources

Reactive Extensions:
- [ReactiveX.io](http://reactivex.io/)
- [RxJS GitBook](http://xgrommx.github.io/rx-book/)
- [Current RxJS](https://github.com/Reactive-Extensions/RxJS)
- [Future RxJS](https://github.com/ReactiveX/RxJS)
- [RxMarbles](http://rxmarbles.com/)
- [Learn RxJS](http://reactivex.io/learnrx/)
- [RxVision](http://jaredforsyth.com/rxvision/)

Blog Posts:
- [The introduction to Reactive Programming you've been missing](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)
- [Two Minute Introduction to RxJS](https://medium.com/@andrestaltz/2-minute-introduction-to-rx-24c8ca793877)
- [Reactive Programming and MVC](http://aaronstacy.com/writings/reactive-programming-and-mvc/)
- [Visualizing Reactive Streams](http://jaredly.github.io/2015/03/06/visualizing-reactive-streams-hot-and-cold/)

Related Presentations:
- [Async JavaScript at Netflix - Jafar Husain](https://www.youtube.com/watch?v=XRYN2xt11Ek)
- [Reactive All The Things - Ben Lesh and Martin Gontovnikas](https://www.youtube.com/watch?v=zbBVG8bOoXk)

Promises:
- [Cancellation Spec](https://github.com/promises-aplus/cancellation-spec)
- [Aborting a Fetch](https://github.com/whatwg/fetch/issues/27)

Object.observe:
- [Object.observe specification](https://github.com/arv/ecmascript-object-observe)
- [Object.observe being withdrawn](https://esdiscuss.org/topic/an-update-on-object-observe)

ECMA Observable:
- [ES Observable Spec](https://github.com/zenparsing/es-observable/)

Functional Reactive Programming (FRP Links):
- [What is Functional Reactive Programming](http://stackoverflow.com/questions/1028250/what-is-functional-reactive-programming)
- [Denotational Design: from meanings to programs](https://github.com/conal/talk-2014-bayhac-denotational-design)

Contact Information:
- [@ReactiveX](https://twitter.com/ReactiveX)
- [@mattpodwysocki](https://twitter.com/mattpodwysocki)

# LICENSE

The MIT License (MIT)

Copyright (c) 2015 Matthew Podwysocki

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
