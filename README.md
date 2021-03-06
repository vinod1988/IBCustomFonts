About IBCustomFonts
===================

**IBCustomFonts** category allows you to use custom fonts from Interface Builder (IB) when building your iOS apps.

Apps using **IBCustomFonts** category are **approved by Apple App Store** (as of September 2013).

No need to use *IBOutlets*, subclassing of *UILabels* and *UIButtons* or change fonts in code.

Tested on iOS6 and iOS7.
    
Usage
=====

1) Add *UIFonts+IBCustomFonts.m* file to your Xcode project

2) Add custom fonts to your application as usual (don't forget to define them in your app `Info.plist` as `Fonts provided by application` array)

3) Add new dictionary to your app `Info.plist` named `IBCustomFonts` and add to it key-value pairs where key is name of font used in IB and value is name of your custom font.
    For example: `HelveticaNeue-Regular` and `CustomFont-Regular`.
    
4) In previous example in IB use *HelveticaNeue-Regular* in places where do you want to see your *CustomFont-Regular* at runtime.
