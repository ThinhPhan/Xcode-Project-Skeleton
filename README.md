Xcode-Project-Skeleton
======================

# Introduction
As a software project grows, the name and location of a file becomes increasingly important.

The fact is that beyond a certain point, a well structured project is essential for working efficiently with your code base.

> **Note** : This approach not cover Universal App.

# My Structure

```
/<ProjectName>
	/Application      	# App delegate, Prefix headers, main.m, Info.plist
    /Controllers      	# Base view controllers
    /Models           	# Models, Core Data schema etc
    /Views            	# Views XIB, Storyboard
    /Library          	# Anything that falls outside of the MVC pattern, Categories and helpers.
	/Resources          # Images, videos, .strings files
	/Vendor             # 3rd party dependencies not managed by CocoaPods
/Pods
```

**Job Done:**

* Structure folders.
* Initial Project.
* Clean up : Prefix Headers, missing files 
* Build no errors and warnings.

**Next Step:**

* Install CocoaPods.
* Create scripts do all stuff automatically.
* Implement simple app in another repo.
