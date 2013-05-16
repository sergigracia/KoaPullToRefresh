KoaPullToRefresh
================
KoaPullToRefresh is a minimal & easily customizable pull-to-refresh control. You can change the font, colors, size and even replace the spinning icon using FontAwesome. This library is very easy to add and customize. This pull to refresh control is developed for [Teambox](http://teambox.com) and is based on the [SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh).

![](https://dl.dropbox.com/s/z3c413vrrfsxfez/KoaPullToRefresh_S1.png)

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

[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/a2cc0b866193ddfa6f06c859bc7ef2ec "githalytics.com")](http://githalytics.com/sergigracia/KoaPullToRefresh)