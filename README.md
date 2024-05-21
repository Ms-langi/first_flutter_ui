# first_flutter_ui

I am unable to see the image in the splashscreen. I get the below error
════════ Exception caught by image resource service ════════════════════════════
The following _Exception was thrown resolving an image codec:
Exception: Invalid image data

#4      AssetBundleImageProvider._loadAsync (package:flutter/src/painting/image_provider.dart:759:18)
image_provider.dart:759
<asynchronous suspension>
#5      MultiFrameImageStreamCompleter._handleCodecReady (package:flutter/src/painting/image_stream.dart:985:3)
image_stream.dart:985
<asynchronous suspension>

Image provider: AssetImage(bundle: null, name: "assets/testlogo.png")
Image key: AssetBundleImageKey(bundle: PlatformAssetBundle#a2046(), name: "assets/testlogo.png", scale: 1.0)
════════════════════════════════════════════════════════════════════════════════
Reloaded 1 of 701 libraries in 7,193ms (compile: 4452 ms, reload: 1000 ms, reassemble: 524 ms).
