Version 0.5 (2018-12-07)

* Added a new interface IPermissionRequestResult2 with method OnPermissionDeniedAndDontAskAgainAction()


Version 0.4.1 (2017-10-24)

* Fixed crash on Android Marshmallow when the Fragment is recreated


Version 0.4 (2017-08-28)

* Fixed issues with Android Oreo (IllegalStateException)


Version 0.3 (2017-08-24)

* Moved the plugin code to utilize delegates instead of having to override the callback methods
* Added sample script
* Big thanks to @Briksins for his contribution


Version 0.2 (2017-07-07)

* There's no more need to override the main manifest - the plugin's manifest contains the necessary SkipPermissionsDialog metadata flag


Version 0.1 (2017-07-04)

* Initial version