# Sketch Android Kit

This is a work-in-progress, comprehensive Android GUI template for [Sketch](http://bohemiancoding.com/sketch/).

## Requirements

* [Sketch 3](http://bohemiancoding.com/sketch/) - You will need to update to Sketch 3 if you haven't already, as the document relies heavily on symbols and is quite useless without them.

* [Roboto](http://developer.android.com/design/style/typography.html) - For the text styles to render properly, you will also need to install Roboto, the system font family introduced with Ice Cream Sandwich. The font is free under the Apache license.

## Structure

The document comprises two pages: the first an introductory artboard with a starter template and the second the main library of symbols and text styles you'll need to mock up your Android apps.

You'll notice similarities with the iOS UI Design template that ships with Sketch 3. It's intentional and is meant to be a complement to the included templates (because Android deserves some love, too).

## Support

For the purpose of creating the template from scratch, all symbols and artboards are based on the latest Android version (KitKat) and the Nexus 5 specs, respectively. Unfortunately, the Nexus 5, being the sole Android device I own, utilizes an XXHDPI resolution for assets (which is 3X the base MDPI = 1px). This means exportability is difficult if you want to scale down to other display densities. **The first stable version (v1.0) will pair everything down to the more common Retina / XHDPI (2X) resolution.**

For those unfamiliar with the current spectrum of display densities, Jeff Broderick's [density converter](http://density.brdrck.me/) can help you get acquainted and make the proper calculations.

## Contributing

This is intended to be an open source project, and I will treat it as such. Do you see anything you would change or improve on, or wish that more UI elements or display densities are supported? Please feel free to submit an issue or a pull request to the repository.

You should first familiarize yourself with Android's design paradigm by reading through [Google's official Android design guide](https://developer.android.com/design/index.html).

### Donating

If you find this project useful and want to contribute in other ways, [consider buying me a coffee][donate]. My addled, caffeine-craving body thanks you.

[donate]: mailto:square@chen.io?cc=cash@square.com&subject=%244.00&body=Here's%20a%20coffee%20on%20me%20for%20your%20awesome%20work.

### TODO before v1.0

* add navigation drawer
* add notification drawer
* add text styles
* add more action bar styles
* add extra styles for controls
* add pressed tab bars
* add text selection controls
* add home screen icon template
* add sample widgets
* add time picker screens
* deprecate buttons (match "official" style guide)
* need to scale down to XHDPI for ease of exportability (!)
* and more...
