A small javascript class that allows you to track the users scroll speed. I wrote this insbired by cschuffs post here: [http://stackoverflow.com/questions/21660348/how-to-detect-scroll-speed-with-jquery](http://stackoverflow.com/questions/21660348/how-to-detect-scroll-speed-with-jquery)

Usage:

    var scrollSpeedMonitor = new ScrollSpeedMonitor(function (speedInPxPerMs, timeStamp, newDirection)
    {
		console.log('Scroll speed: ' + speedInPxPerMs);
	};

We use this as a sub component in our [https://github.com/SocialbitGmbH/JavascriptStarScroller](https://github.com/SocialbitGmbH/JavascriptStarScroller "JavascriptStarScroller").


## License  
    Copyright 2014 Socialbit GmbH

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.   
