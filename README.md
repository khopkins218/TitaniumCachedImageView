# cachedImageView.js
------------------------------------------
For more, head out to [my site](http://kevin.h-pk-ns.com/) or to the [Appcelerator Developer Center](http://developer.appcelerator.com).


## Android and iOS Users:
-----------------------
Implementation works the same cross-platform.  Enjoy!

## Questions?
------------
If you have any questions, please feel free to ask on my [blog](http://kevin.h-pk-ns.com/) or via the contact information found there.


## Usage:
--------
cachedImageView Usage:
        Ti.include('lib/cachedImageView.js');
	function createMyImage() {
		var win = Ti.UI.currentWindow;
	
		var imgMyImage = Ti.UI.createImageView({
			width: 120,
			height: 120,
			top:10,
                        left:10
		});
	
		cachedImageView('imageDirectoryName', 'http://MyRemoteServer.com/public/images/1.png', imgMyImage);
	
		win.add(imgMyImage);
		win.open({animated:true});
	};

# License:
----------
No License, just use and enjoy!
