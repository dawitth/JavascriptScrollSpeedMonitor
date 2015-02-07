A small javascript class that allows you to track the users scroll speed. I wrote this insbired by cschuffs post here: [http://stackoverflow.com/questions/21660348/how-to-detect-scroll-speed-with-jquery](http://stackoverflow.com/questions/21660348/how-to-detect-scroll-speed-with-jquery)

Usage:

    var scrollSpeedMonitor = new ScrollSpeedMonitor(function (speedInPxPerMs, timeStamp, newDirection)
    {
		console.log('Scroll speed: ' + speedInPxPerMs);
	};

We use this as a sub component in our [https://github.com/SocialbitGmbH/JavascriptStarScroller](https://github.com/SocialbitGmbH/JavascriptStarScroller "JavascriptStarScroller").