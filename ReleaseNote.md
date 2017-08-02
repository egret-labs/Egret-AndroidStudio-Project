##Egret Android Support Based On Android Studio Release Notes 
---

### Egret Android Support 5.0.5 Release Notes
--
Updated: July 03, 2017

miniSDKVersion:14

- **[Fix]** Fixed Chinese font is clearly downwards on Android 5.*.
- **[Fix]** Fixed continuously calling egret.getOption may cause a flashback.
- **[Fix]** Fixed bug in version 5.0.3 that application has probability of flashing at non-first start.
- **[Fix]** Fixed bugs.

### Egret Android Support 5.0.3 Release Notes
--
Updated: July 21, 2017

miniSDKVersion:14

- **[Fix]** Fixed current playback time cannot be read correctly
- **[Fix]** Fixed bugs.

### Egret Android Support 5.0.1 Release Notes
--
Updated: June 29, 2017

miniSDKVersion:14

- **[Fix]** Fixed short audio may be played repeatedly.
- **[Fix]** Fixed application goes into the background may lead to audio can not be played.
- **[Fix]** Fixed call drawToTexture may be given an error.
- **[Fix]** Fixed bugs.

### Egret Android Support 4.1.0 Release Notes
--
Updated: May 23, 2017

miniSDKVersion:14

- **[Fix]** Fixed lag and flashing caused by playing audio.
- **[Fix]** Fixed setting background transparency is invalid
- **[Fix]** Fixed part of the scene rendering error problem after open optimization.
- **[Fix]** Fixed bugs.

### Egret Android Support 4.0.3 Release Notes
--
Updated: March 08, 2017

miniSDKVersion:14

- **[Fix]** Fixed the images saved by the drawToTexture interface would be partially rendered incorrectly.
- **[Fix]** Fixed bugs.

### Egret Android Support 4.0.2 Release Notes
--
Updated: February 21, 2017

miniSDKVersion:14

- **[Fix]** Fixed the frequent switching between several input boxes that could cause a crash problem.
- **[Fix]** Fixed using filters on some phones can cause a crash.
- **[Fix]** Fixed some small audio may cause crash.
- **[Fix]** Fixed the input box does not show right at partial resolution.
- **[Fix]** Fixed bugs.

### Egret Android Support 4.0.1 Release Notes
--
Updated: January 24, 2017

miniSDKVersion:14

- **[Add]** Added image picker feature(Please refer to the Developer Center to get instructions).
- **[Add]** Support for converting ArrayBuffer or Base64 to textures(Please refer to the Developer Center to get instructions).
- **[Fix]** Fixed setting the transparency of the vector illustration is invaild after opening CmdBatch.
- **[Fix]** Fixed issues related to hot update.
- **[Fix]** Fixed the filter shader can not be compiled on some phone models.
- **[Fix]** Fixed the input box may be obscured by the keyboard before starting editing.
- **[Fix]** Fixed WebSocket can not connect to a non-default port that appeared in the last version.
- **[Fix]** Fixed bugs.

### Egret Android Support 4.0.0 Release Notes
--
Updated: January 09, 2017

miniSDKVersion:14

- **[Add]** Added support for wss protocol.
- **[Fix]** Edit template for custom hot-update methods, set old version of hot-update as default.
- **[Fix]** Fixed game version record would be updated even if hot-update is not finished successfully.
- **[Fix]** Fixed bugs.

### Egret Android Support 3.2.6 Release Notes
--
Updated: December 27, 2016

miniSDKVersion:14

- **[Update]** Add template for custom hot-update methods.
- **[Update]** Https request would not need to verificate certificates.
- **[Fix]** Fixed the application could not launch again after hot-update failed.
- **[Fix]** Fixed GameLoadingView doesn't show up if run game with local zip.
- **[Fix]** Fixed bugs.

### Egret Android Support 3.2.5 Release Notes
--
Updated: December 13, 2016

miniSDKVersion:14

- **[Fix]** Fixed GameLoadingView doesn't show up if hot-update is not proceed appeared in 3.2.4.
- **[Fix]** Fixed input box is sheltered after changing the hierarchy of GLSurfaceView.
- **[Fix]** Fixed bugs.

### Egret Android Support 3.2.4 Release Notes
--
Updated: November 29, 2016

miniSDKVersion:14

- **[Fix]** Fixed setting start time of audios sometimes invalid.
- **[Fix]** Fixed rendering of filters.
- **[Fix]** Override the hot update logic, consider the network disconnect and other cases.
- **[Fix]** Fixed setting input box to single line sometimes invalid.
- **[Add]** Added optimization switch for rendering textures.
- **[Add]** Added Splash features. Applications display a picture instantly at start. Usage is in the comments in SplashActivity.
- **[Fix]** Fixed bugs.

### Egret Android Support 3.2.3 Release Notes
--
Updated: November 15, 2016

miniSDKVersion:14

- **[Fix]** Fixed setting volume of audios is useless.
- **[Fix]** Fixed part of audios could not play caused by actively stop audios repeatedly.
- **[Fix]** Fixed games crashed on some Android simulator.
- **[Fix]** Fixed cursor would not be the end of the text when input box got focus.
- **[Fix]** Fixed bugs.

### Egret Android Support 3.2.2 Release Notes
--
Updated: November 01, 2016

miniSDKVersion:14

- **[Fix]** Fixed rendering problems under specific cases.
- **[Fix]** Fixed text shows wrong color when editting input box with prompt text at the first time.
- **[Update]** Add a switch to optimize rendering efficiency(details: http://developer.egret.com/cn/github/egret-docs/Engine2D/native/other/index.html ).
- **[Fix]** Fixed bugs.

### Egret Android Support 3.2.1 Release Notes
--
Updated: October 18, 2016

miniSDKVersion:14

- **[Note]** This release optimized efficiency of rendering, if exception occurred when rendering, please close the optimization.
- **[Update]** Support modifying the game View hierarchy.
- **[Fix]** Fixed rendering problems under specific cases .
- **[Fix]** Fixed text position offset in some models.
- **[Fix]** Handled situation that the number of audios is excessive.
- **[Fix]** Fixed bugs.

### Egret Android Support 3.2.0 Release Notes
--
Update: September, 27 2016

miniSDKVersion:14

- **[Note]** This release optimized efficiency of rendering, if exception occurred when rendering, please close the optimization.
- **[Add]** Supported filter rendering.
- **[Add]** Supported mesh rendering.
- **[Update]** Improved efficiency of the scene rendering.
- **[Update]** Improved stability.
- **[Fix]** Fixed text position shifts upward when rendering default font in some models.
- **[Fix]** Fixed there must be a hot update when starting the game at the first time .
- **[Fix]** Fixed bugs.

### Egret Android Support 3.1.8 Release Notes
--
Update：September 02, 2016

miniSDKVersion:14

- **[Fix]** Fixed prompt text in InputBox dont disappear while editting.
- **[Fix]** Fixed crash on playing audios.
- **[Update]** Improved stability.
- **[Fix]** Fixed bugs.

### Egret Android Support 3.1.7 Release Notes
--
Update：August 25, 2016

miniSDKVersion:14

- **[Fix]** Fixed crash on setting illegal value of color.
- **[Fix]** Fixed crash on playing audios.
- **[Fix]** Fixed unable to load online audios.
- **[Fix]** Fixed audios cannot been released completely.
- **[Add]** Support italic text.
- **[Add]** Add ColorTransform Filter.
- **[Update]** Improved stability.
- **[Fix]** Fixed bugs.

### Egret Android Support 3.1.6 Release Notes
--
Update：August 08, 2016

miniSDKVersion:14

- **[Fix]** Fixed the position of input box is wrong when height of input box and line height is different.
- **[Fix]** Fixed lag problem when multi sound effect are simultaneously playing.
- **[Update]** Improved stability.
- **[Fix]** Fixed bugs.

### Egret Android Support 3.1.5 Release Notes
--
Update：July 25, 2016

miniSDKVersion:14

- **[update]** MinSdkVersion Level14 .
- **[Update]** Improved stability.
- **[Fix]** Fixed bugs.

### Egret Android Support 3.1.4 Release Notes
--
Update：July 12, 2016

- **[Add]** Get battery info of device. 
- **[Update]** Improved stability.
- **[Fix]** Fixed bugs.

### Egret Android Support 3.1.3 Release Notes
--
Update：June 27, 2016

- **[Update]** Improved stability.
- **[Fix]** crash caused by characters replacing in EUI label.
- **[Fix]** Fixed bugs.