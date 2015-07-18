
On the Swift 2.0 error handling rage

If you haven't been following the Swift world closely -- just like me -- you might be wondering what's the 2.0 error `throwing` model rage about. It's all about types. We know that a given function throws, but we don't know what will be thrown.


Types give us more safety. That's why Swift is so powerful. Generics, optionals, and powerful protocols embrace `type driven development`. Swift embraces types.

If you saw this:



And didn't know what was going on




# Maybe it's just Objective-C legacy

Errors in Foundation are not typed. They are instances of the same class; `NSError`. 