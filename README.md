AR Balloon Shooter

A simple Augmented Reality (AR) game built with Unity and AR Foundation, where players shoot balloons that appear in the real world through their device's camera. This project is ideal for beginners learning AR game development with Unity, featuring plane detection, touch-based interaction, and visual feedback.

Features





AR Plane Detection: Balloons spawn on real-world surfaces detected by ARCore (Android) or ARKit (iOS).



Touch Interaction: Tap to shoot balloons, triggering a pop sound and visual effect.



Assets Included: Balloon models, pop sound, and scripts for spawning and interaction.



Cross-Platform: Supports Android and iOS devices with AR capabilities.

Prerequisites





Unity Hub and Unity Editor (2019.4 or later recommended).



AR-Compatible Device: Android (ARCore-supported) or iOS (ARKit-supported). Check Google AR Devices for compatibility.



Development Environment:





Android: Android SDK, USB Debugging enabled.



iOS: Xcode, Apple Developer account for deployment.



Git (optional, for cloning this repository).

Setup Instructions





Download the Project:





Download the .unitypackage file from Google Drive.



Alternatively, clone this repository:

git clone https://github.com/your-username/ar-balloon-shooter.git



Open in Unity Hub:





Install Unity Hub from unity3d.com.



Create a new 3D project in Unity Hub (Unity 2019.4 or later).



In Unity, go to Assets > Import Package > Custom Package and select the downloaded .unitypackage file.



Install AR Plugins:





Open Window > Package Manager in Unity.



Install the following packages:





AR Foundation (latest compatible version).



ARCore XR Plugin (for Android).



ARKit XR Plugin (for iOS).



Ensure versions are compatible to avoid errors.



Configure the Scene:





Open the main scene from the Assets folder (e.g., Scenes/MainScene).



Verify that the scene includes an AR Session, AR Session Origin, and AR Camera (auto-imported with the package).



Ensure the AR Camera has the tag MainCamera.



Build and Run:





Go to File > Build Settings and select Android or iOS.



Click Switch Platform to configure for your target platform.



Connect an AR-compatible device via USB (enable Developer Options and USB Debugging for Android).



Click Build and Run to deploy the game to your device.

How to Play





Launch the app on your AR-compatible device.



Point the camera at a flat surface (e.g., table or floor) to detect planes.



Wait for balloons to spawn on the detected surface.



Tap on balloons to shoot them, triggering a pop sound and visual effect.



Continue shooting balloons as they appear!

Project Structure





Assets/Scripts: Contains C# scripts for balloon spawning, shooting mechanics, and AR interaction.



Assets/Models: Balloon 3D models and textures.



Assets/Sounds: Pop sound effect for balloon destruction.



Assets/Scenes: Main game scene with AR setup.

Contributing

Contributions are welcome! To contribute:





Fork this repository.



Create a new branch (git checkout -b feature/your-feature).



Make your changes and commit (git commit -m "Add your feature").



Push to the branch (git push origin feature/your-feature).



Open a Pull Request with a detailed description of your changes.

Please ensure your code follows Unity best practices and includes comments for clarity.

Credits





Source: Adapted from the Instructables tutorial for AR game development.



Assets: Balloon models and pop sound provided by the original .unitypackage.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Support

For issues or questions, open an issue on this repository or refer to:





Unity AR Foundation Documentation



Google ARCore Documentation



Apple ARKit Documentation

Happy AR gaming!
