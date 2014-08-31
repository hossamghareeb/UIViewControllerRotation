### UIViewControllerRotation
========================

UIViewController+Rotation category used for handling the interface orientation for all view controllers in an app
### How to use:
=======================

Just add the category in your app and then go to [UIViewController+Rotation.h](https://github.com/most-wanted/UIViewControllerRotation/blob/master/UIViewController%2BRotation.h) to set the following:
- DEFAULT_ORIENTATION => The default orientaion of your app.
- VIEW_CONTROLLERS_PORTRAIN_ONLY @[] => Array of names of ViewControllers that support the portrait orientaion.
- VIEW_CONTROLLERS_LANDSCAPE_ONLY @[] => Array of names of ViewControllers that support the landscape orientaion.
- VIEW_CONTROLLERS_LANDSCAPE_LEFT_ONLY @[] => Array of names of ViewControllers that support the landscape left orientaion only.
- VIEW_CONTROLLERS_LANDSCAPE_RIGHT_ONLY @[] => Array of names of ViewControllers that support the landscape right orientaion only.
- VIEW_CONTROLLERS_PORTRAIN_UPSIDE_DOWN_ONLY @[] => Array of names of ViewControllers that support the portrait upside down only.
- VIEW_CONTROLLERS_ALL @[] => Array of names of ViewControllers that support all orientations.
- VIEW_CONTROLLERS_ALL_BUT_UPSIDE_DOWN @[] => Array of names of ViewControllers that support all orientations except the upside down.
