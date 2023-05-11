# Theta Limited

[Our organization](https://theta.limited/) provides a free and open source UAS geodesy platform which enables a competitive advantage for its users.

<a href="https://github.com/mkrupczak3/OpenAthena"><img width="540" alt="OpenAthena Drone Camera Terrain Raycast Concept Diagram" src="https://github.com/mkrupczak3/OpenAthena/raw/main/assets/OpenAthena_Concept_Diagram.png"></a>

<a href="https://github.com/Theta-Limited/OpenAthenaAndroid"><img width="330" alt="OpenAthena arbitrary point location demo gif" src="https://raw.githubusercontent.com/Theta-Limited/OpenAthenaAndroid/master/assets/tap_to_locate_demo_small.gif"></a>

# OpenAthena™ for Android

Our flagship platform "OpenAthena for Android" allows operators of common drones to spot precise geodetic locations on Earth and complete their missions faster and with better accuracy.

Target resolution is accomplished by combining the sensor metadata embeded in drone images with an offline-ready Digital Elevation Model. Operators may instantly obtain the exact location of any selected point, providing actionable insights faster. The app's custom data extraction technique supports DJI, Skydio, Autel, and Parrot aircraft. It includes a database of over 40 camera models and automatically accounts for factors such as roll/pitch/yaw, position, crop, focal length, and optical and digital zoom. The geodesy-based target resolution engine then performs a raycast for the selected point towards a digital twin of the Earth as represented by a digital elevation model. The engine precisely accounts for latitudinal variations and the curvature of the Earth.

The app natively supports WGS84 latitude/longitude, [NATO 1m, 10m, and 100m Grid Refs](https://en.wikipedia.org/wiki/Military_Grid_Reference_System), [CK-42 lat/lon](https://en.wikipedia.org/wiki/SK-42_reference_system), and CK-42 [Gauss Krüger](https://desktop.arcgis.com/en/arcmap/latest/map/projections/gauss-kruger.htm) Grid Ref as output modes.

## Safe, Open, Secure

* All data processing occurs offline and requires no networked API calls. This keeps your data private and secure.

* All the source code which defines how the app operates is open source, meaning anyone can inspect it.

* Signed builds and a secure software supply chain built entirely from source preclude manipulation by bad actors.

## Multiplicative Value

The OpenAthena for Android app supports seamless integrations with platforms such as the [Android Team Awareness Kit](https://en.wikipedia.org/wiki/Android_Team_Awareness_Kit) using the industry-standard [Cursor on Target (CoT)](https://www.mitre.org/sites/default/files/pdf/09_4937.pdf) interchange format:

<img width="586" alt="OpenAthena for Android DJI_0419.JPG target shown in Google Maps satellite view" src="https://raw.githubusercontent.com/Theta-Limited/OpenAthenaAndroid/master/assets/0419_maps_screenshot.png">

<img width="586" alt="OpenAthena for Android triggers a waypoint to show in Android Team Awarness Kit at the calculated location" src="https://raw.githubusercontent.com/Theta-Limited/OpenAthenaAndroid/master/assets/ATAK_OpenAthena_CoT_Demo_landscape.png">


It also supports one tap copy/paste for use with the team messaging platform of your choice:

<img width="340" alt="Gif showing text copied to clipboard toast after taping on results box" src="https://raw.githubusercontent.com/Theta-Limited/OpenAthenaAndroid/master/assets/TextCopiedOptimized.gif">

## Make it yours

OpenAthena for Android is entirely free to use, and is licensed under the [GPLv3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) to protect your rights as a user. You have inalienable rights to view the source code of the App and/or modify the App to your own specifications. You may (subject to local and international law) distribute the App with any modifications you have made, provided that you give your users the very same rights.

## Support and Feedback

Let us help you accomplish your mission. Establish direct contact with our developers through [support@theta.limited](mailto:support@theta.limited?subject=My Question about OpenAthena).

Feedback from users is our single most valuable asset. Become involved with our development on GitHub, or submit feedback to [feedback@theta.limited](mailto:feedback@theta.limited?subject=My Feedback on OpenAthena) to shape the future of the project.
