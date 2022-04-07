# Balloon Pop
Play a carnival game: pop the balloon at the game booth!

# Register
Don't have an API key? Make sure to register for FREE at [echo3D](https://www.echo3d.co/).

# Packages Used
* Unity 2019.4.0f1
* Latest echo3D SDK

# How to Play
Click the red balloon with your mouse.

# Setup
* Clone this repo: https://github.com/echo3Dco/Unity-echo3D-BalloonPop
* [Install the echo3D Unity SDK](https://docs.echo3d.co/unity/installation)
* Find the 3D models in 'Models' folder.
* Go to [echo3D console](https://console.echo3d.co/#/pages/contentmanager) and click "Add to Cloud" and upload the models.
* In [metadata for the carnival booths](https://docs.echo3d.co/web-console/manage-pages/data-page/global-data-and-metadata) in the echo3D console, change 'scale' to .2 and xAngle to 90.
![metadata](https://user-images.githubusercontent.com/99516371/162153972-b53a1800-0a34-4bdf-91e8-89f0da199032.png)
* In [metadata for the balloon](https://docs.echo3d.co/web-console/manage-pages/data-page/global-data-and-metadata) in the echo3D console, change 'scale' to 10, 'x' to 8.34, 'y' to 77.82 and 'z' to 404.![metadataballoons](https://user-images.githubusercontent.com/99516371/162258378-559c9d57-660b-4fba-9126-4b8e452b0de9.png)
* Open the 'BalloonPopScene' scene.
* In the Hierarchy, go to each object (Background, RedBalloonObject) and click on the echo3D child. Add your API key and the Entries ID per object from the Inspector.

![APIkeys](https://user-images.githubusercontent.com/99516371/162153945-fd779bde-d1e3-42e7-b476-f44dc6ff8971.png)



# Learn more
Refer to our [documentation](https://docs.echo3d.co/) to learn more about how to use echo3D.

# Support
Feel free to reach out at support@echo3D.co or join our [support channel on Slack](https://echo3d.slack.com/ssb/redirect).

# Screenshot
![BalloonPopScreenshot](https://user-images.githubusercontent.com/99516371/162152966-9e998266-bcf6-412f-a7a5-99bf40ffc5d5.png)





