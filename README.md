LockNav : A jQuery Plugin
=======

This is a jQuery Plugin that can be used to help control how a web page will behave when end users click refresh or use the back button of a web browser.
 
Demonstration: http://clintbray.com/ShareItems/LockNav/


Use
===

````javascript
$.lockNav({
	DisableF5: true,
	WarnBeforeUnload: true,
	WarningMessage: 'You may lose information.'
});
````

##Options


###DisableF5
type (boolean)
default = true

###WarnBeforeUnload
type (boolean)
default value = true

###WarningMessage
type (string)
default value = 'By refreshing or navigating away from this page; you may lose data you are currently working with.'

##Getting and Setting Options

````javascript
// getting
var bWarnBeforeUnload = $.lockNav().settings.WarnBeforeUnload;

// setting
$.lockNav().settings.WarnBeforeUnload = true;
````









