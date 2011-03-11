Developed by Kevin L. Hopkins (http://kevin.h-pk-ns.com)
You may borrow, steal, use this in any way you feel necessary but please
leave attribution to me as the source.  If you feel especially grateful,
give me a linkback from your blog, a shoutout @Devneck on Twitter, or 
my company profile @ http://wearefound.com.

# For Titanium Mobile - cachedImageView.js
------------------------------------------
For more, head out to [my site](http://kevin.h-pk-ns.com/) or to the [Appcelerator Developer Center](http://developer.appcelerator.com).


# ANDROID AND iOS USERS:
-----------------------
Implementation works the same cross-platform.  Enjoy!

# Questions?
------------
If you have any questions, please feel free to ask on my[blog](http://kevin.h-pk-ns.com/blog).


# Usage:
--------
cachedImageView Usage:

function createMyImage() {
	Ti.include('lib/cachedImageView.js');
	var win = Ti.UI.currentWindow;
	
	var imgMyImage = Ti.UI.createImageView({
		width: 120,
		height: 120,
		image: 'default.png'
	});
	
	cachedImageView('imageDirectoryName', 'http://MyRemoteServer.com/public/images/1.png', imgMyImage);
	
	win.add(imgMyImage);
	win.open({animated:true});
};

# License:
----------
Copyright © 2001 Kevin L. Hopkins. It is free software, and may be redistributed under the terms specified in the LICENSE file.