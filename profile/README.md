# Theta Informatics LLC

[Theta Informatics LLC](https://theta.limited/) provides OpenAthena™, software which allows common drones to spot precise locations quickly:

<img width="540" alt="OpenAthena Drone Camera Terrain Raycast Concept Diagram" src="https://github.com/mkrupczak3/OpenAthena/raw/main/assets/OpenAthena_Concept_Diagram.png">

<a href="https://github.com/Theta-Limited/OpenAthenaAndroid"><img width="330" alt="OpenAthena arbitrary point location demo gif" src="https://raw.githubusercontent.com/Theta-Limited/OpenAthenaAndroid/master/assets/tap_to_locate_demo_small.gif"></a>

# OpenAthena™ for Android

Theta's flagship platform [OpenAthena for Android](https://github.com/Theta-Limited/OpenAthenaAndroid) allows operators of regular off-the-shelf drones to obtain a precise location from any pixel of a single drone image.

Operators may instantly obtain the exact location of any selected point within a drone image, providing actionable insights faster. Target resolution is accomplished by combining the sensor metadata automatically embeded in drone images (containing data such as lat/lon, camera angle, and zoom level) with an offline-ready Digital Elevation Model which stores the altitude of terrain. This unique approach allows instant location analysis using just one drone image, no need for time-consuming mapping or processing!

The app's custom data extraction technique supports most Skydio, Parrot, Teal, Autel, and DJI aircraft. It includes a database of over 60 camera models (including both color and thermal cameras) and automatically accounts for factors such as roll/pitch/yaw, position, crop, focal length, lens distortion, and optical and digital zoom. The geodesy-based target resolution engine then simulates a raycast for the selected point towards a digital twin of the Earth to give you the precise coordinates of your selected point within the image. The engine precisely accounts for latitudinal variations and the curvature, rotation, and gravity of the Earth.

The app natively supports latitude/longitude, UTM, [NATO 1m, 10m, and 100m Grid Refs](https://en.wikipedia.org/wiki/Military_Grid_Reference_System), [CK-42 lat/lon](https://en.wikipedia.org/wiki/SK-42_reference_system), and CK-42 [Gauss Krüger](https://desktop.arcgis.com/en/arcmap/latest/map/projections/gauss-kruger.htm) Grid Ref as output modes.

## Safe, Secure

* All data processing occurs offline (once a Digital Elevation Model is loaded automatically). This keeps your data private and secure.

* Signed builds and a secure software supply chain built entirely from source preclude manipulation by bad actors.

## iOS version

OpenAthena for iOS is available for users of iPhone® and iPad® products:

https://github.com/Theta-Limited/OpenAthenaIOS

<a href="https://github.com/Theta-Limited/OpenAthenaIOS"><img width="330" alt="openathena for ios an arbitrary image point is selected and the coresponding location calculated is displayed" src="https://github.com/Theta-Limited/.github/assets/25494111/86968e65-5fde-4e7f-9201-4ccc7babc193"></a>

# api.openathena.com

Theta Informatics LLC hosts a RESTful API service at [https://api.openathena.com](https://api.openathena.com) which makes OpenAthena's terrain-raycast technique available to your own hardware and software applications. To request a free evaluation API key, email <a href="mailto:info@theta.limited?subject=api.openathena.com Evaluation API Key">info@theta.limited</a>.

Deep Dive and video demo:
[https://www.youtube.com/watch?v=it9khfq-IeQ](https://www.youtube.com/watch?v=it9khfq-IeQ)


# OpenAthena™ Core

Theta Informatics' **OpenAthena™ Core** makes OpenAthena's novel terrain-raycast technique available as a portable Java software library. Unlike the mobile Android and iOS versions, OpenAthena Core is designed and licensed to enable you to integrate the software's novel terrain-raycast technique into your own firm's solutions.

<a href="https://theta.limited/openathena-core"><img width="586" alt="OpenAthena Desktop and Core demo" src="https://github.com/user-attachments/assets/20c55801-ec56-402d-8bbb-847301a47298"></a>


OpenAthena Core is provided to purchasers as a Java software library with full source code. This allows OpenAthena Core to be extremely flexible for integration as a component of your own proprietary solution. It features a command line interface, Java bindings, and remote use over a RESTful API for seamless integration with your existing software:

<img width="586" alt="OpenAthena Core RESTful API demo" src="https://github.com/user-attachments/assets/72bd5e17-bd9b-4fd8-b732-465369e53a08">

<br><br>

More info is available at [https://theta.limited/openathena-core](https://theta.limited/openathena-core)

Contact <a href="mailto:info@theta.limited?subject=OpenAthena-Core Evaluation License">info@theta.limited</a> to obtain a free evaluation copy for your developers.

<br>

## Multiplicative Value

The OpenAthena apps support seamless integrations with platforms such as the [Android Team Awareness Kit](https://en.wikipedia.org/wiki/Android_Team_Awareness_Kit) using the industry-standard [Cursor on Target (CoT)](https://www.mitre.org/sites/default/files/pdf/09_4937.pdf) interchange format:

<img width="586" alt="OpenAthena for Android DJI_0419.JPG target shown in Google Maps satellite view" src="https://raw.githubusercontent.com/Theta-Limited/OpenAthenaAndroid/master/assets/0419_maps_screenshot.png">

<img width="586" alt="OpenAthena for Android triggers a waypoint to show in Android Team Awarness Kit at the calculated location" src="https://raw.githubusercontent.com/Theta-Limited/OpenAthenaAndroid/master/assets/ATAK_OpenAthena_CoT_Demo_landscape.png">


## It's free real estate 

OpenAthena for Android is entirely free to use.


## Support and Feedback

Let us help you accomplish your mission. Establish direct contact with our developers through <a href="mailto:support@theta.limited?subject=My Question about OpenAthena" data-type="mailto" data-id="mailto:support@theta.limited?subject=My Question about OpenAthena">support@theta.limited</a>.

Feedback from users is our single most valuable asset. Become involved with our development on GitHub, or submit feedback to <a href="mailto:feedback@theta.limited?subject=My Feedback on OpenAthena" data-type="mailto" data-id="mailto:feedback@theta.limited?subject=My Feedback on OpenAthena">feedback@theta.limited</a> to shape the future of the project.
