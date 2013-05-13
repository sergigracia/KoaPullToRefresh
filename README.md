KoaPullToRefresh
================
A new pull to refresh control based on the [SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh).

Installation
============
### From CocoaPods
1. Add ```pod 'KoaPullToRefresh'``` to your Podfile.
2. Edit your app's Info.plist to contain the key: ```"Fonts provided by application"``` (```UIAppFonts```). Then add ```FontAwesome.ttf``` to the list under that key.

### Manually
1. Drag the KoaPullToRefresh/KoaPullToRefresh folder into your project.
2. Add the ```QuartCore framework``` to your project.
3. Edit your app's Info.plist to contain the key: ```"Fonts provided by application"``` (```UIAppFonts```). Then add ```FontAwesome.ttf``` to the list under that key.
4. Import ```KoaPullToRefresh.h```.

Usage
=====
### Adding KoaPullToRefresh
```objective-c
[tableView addPullToRefreshWithActionHandler:^{
	// Tasks to do on refresh. Update datasource, add rows, …
	// Call [tableView.pullToRefreshView stopAnimating] when done.
}];
```

Requirements
============
* iOS >= 5.0
* ARC

Contact
=======
* Sergi Gracia: sergigram@gmail.com
* Polina Flegontovna: polina.flegontovna@gmail.com

License
=======
KoaPullToRefresh is available under the MIT License. See the License file for more info.