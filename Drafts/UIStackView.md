
It's been a busy week. AltConf was amazing, and now it's time to





# UIStackView

Starting with iOS 9 there's a new way to layout views in UIKit. `UIStackView` allows us to express layout as a stack of views. They might be aligned either vertically or horizontally. It is a pretty expressive layer of abstraction over AutoLayout possibly saving us much time creating and debugging constraints or layout code.

# Another item in the hierarchy

`UIStackView` is a... view. In order to use it has to be added to the view hierarchy. It might cause 

# ComponentKit



# View != Layout

Treating layout as a part of a view is a common fallacy.  It's everywhere in UIKit. Constraints are added to views, autoresizing masks are view properties. 

Universal views for iPhone and iPad tend to be really complex.


UIKit is main thread only



