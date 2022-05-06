
# Platform overview
The LTA platform consists of four major components, supported by other tools and components. The back-end is containerised.

## Major Components


| Component            | What's it for?                                                                       | How's it built?                                  | See            | Repo
|-------------|--------------------------------------------------------------------------------------|--------------------------------------------------|----------------|------|
| **iOS app**     | An iOS app for a research person to get notifications and to take surveys in.                                | XCode, Swift.                      | [the LTA readme](https://github.com/NorthEasterBunny/NorthEasterBunny#readme) | [LangTrackAppIphone](https://github.com/NorthEasterBunny/LangTrackAppIphone) |
| **Android app** | An Android app for a research person to get notifications and to take surveys in.                            | Android Studio, Kotlin.   | [the LTA readme](https://github.com/NorthEasterBunny/NorthEasterBunny#readme) | [LangTrackAppAndroid](https://github.com/NorthEasterBunny/LangTrackAppAndroid) |
| **Web App**     | A webpage for administrators, to configure and schedule survey assignments to users. | VueJS, bootstrap.                                | this readme    | [lta-webapi](https://github.com/NorthEasterBunny/lta-webapi) |
| **Web Service** | An API with a database, serving all three clients, and notifying smartphone apps about assignments.                                    | Node, Express, typescript, mongoose. | this readme    | [lta-webapp](https://github.com/NorthEasterBunny/lta-webapp) |
 
![LTA-Platform-Overview](https://i.imgur.com/m31ut8t.jpeg)
