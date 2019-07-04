# Flare-Animations
Common animations in [Flare](https://www.2dimensions.com/about-flare) that can be used in Flutter Apps.

## How to use Animations in Flutter.

- Download your chosen animation. Animations can be found in the folders. Each animation has a different folder. Feel free to check them out.

- Make Sure to add Flare package in your `pubspec.yaml` file.
```
dependencies:
  flutter:
    sdk: flutter
  
  flare_flutter: any
```
See the Flare package for Flutter [here](https://pub.dev/packages/flare_flutter)

- Add your animation in `assets` in `pubspec.yaml` file. Animations will have a `.flr` extension
```
assets:
  - animation.flr
```

- Import packages from Flare
```
import 'package:flare_flutter/flare_actor.dart';
```

- Using the FlareActor Widget, add the path to your animation and the name of Animation.
```
FlareActor("assets/animation.flr",
        animation: "Animation Name",
        fit: BoxFit.contain,
        )
``
