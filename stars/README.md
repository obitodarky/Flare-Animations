![star_rating](https://user-images.githubusercontent.com/21317964/60488031-7c9e9e00-9cbe-11e9-81c3-e68d12a10396.gif)

## How to use

- Add to assets folder. Update your `pubspec.yaml` file.
```
assets:
    - star_rating.flr
``` 

- Use the Flare Actor widget.
```
child: FlareActor("assets/star_rating.flr",
        animation: "Start Rating",
        fit: BoxFit.contain,
        )
```
