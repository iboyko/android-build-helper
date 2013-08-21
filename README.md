android-build-helper
====================

Helper plugin for android gradle projects

Usage 
====================

versionCodeFromProjectVersion
----------------------------------------
Method updated version code from project version as it is in android-maven-plugin v3.6.0

    apply from: 'https://raw.github.com/iboyko/android-build-helper/master/AndroidHelperPlugin.gradle'
    ...
    android {
	    ...
    	versionCode versionCodeFromProjectVersion()
    	...
    }
    