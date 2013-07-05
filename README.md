# Augmented Reality - Wikitude SDK Module
by Wikitude GmbH - [www.wikitude.com](http://www.wikitude.com)


### The Wikitude Titanium Module 


The Wikitude Titanium Module enables you to embed an augmented reality view in your Titanium project. 

* Simple and seamless native Titanium integration
* Fully customizable augmented reality (AR) view
* Full feature set of the Wikitude SDK
* AR content is purely written in HTML and JavaScript

![image](http://www.wikitude.com/wp-content/uploads/2012/12/Module_Titanium.png)

For detailed documentation including a setup and getting started guide  please see the official documentation under: [http://developer.wikitude.com/documentation](http://developer.wikitude.com/documentation)


### Supported mobile operating systems
* Android 
* iOS


### Tested Titanium versions
* Titanium SDK 3.1.1
**Important: Modules run on [Titanium 3.1+](http://www.appcelerator.com/platform/titanium-platform) only**


###Further Developer Resources or Need Help?
* [Full documentation and additional tutorials](http://developer.wikitude.com/documentation)
* [Developer Forum](http://developer.wikitude.com/developer-forum)
* [Wikitude SDK Download](http://developer.wikitude.com/download)
* [Google+ Page for News](https://plus.google.com/u/0/103004921345651739447/posts)
* [Developer Newsletter](http://www.wikitude.com/developer/newsletter)


### WATERMARK

The free trial version of the Wikitude SDK shows a start-up animation and a trial watermark in the camera-view. To get rid of this please register as a developer at the [Wikitude](www.wikitude.com) website and have a look at the store and [pricing plan](http://www.wikitude.com/products/wikitude-sdk/pricing/).

Enter the SDK-key when creating the WikitudeView:

	arview = wikitude.createWikitudeView({
			licenseKey: 'YOUR-KEY' , 
			bottom: 0,
			left: 0,
			right: 0,
			top: 0
		});
		
Please use the id listed in `tiapp.xml` as package-identifier when requesting the license key

	<id>com.wikitude.titaniumsample</id>

## LICENSE
``` 
   Copyright 2013 [Wikitude GmbH](http://www.wikitude.com)

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
 ``` 

