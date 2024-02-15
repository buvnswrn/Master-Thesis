## Unity Robotics Warehouse Environment

## Installation Requirements:
- Unity 2021.3.16f1 with URP High Fidelity
- Microsoft Airsim Framework

## Installation Process:
- Mostly the scene should be running out of the box, but if any issue persists, please install the following.
- Install the **Microsoft Airsim Framework for Unity** according to the documentation mentioned in official website - https://microsoft.github.io/AirSim/Unity/
    - Note that a successful installation must be verified before testing this scene
    - If the AJAN-Airsim Service issues an error: `WARNING:tornado.general:Connect error on fd 1072: WSAECONNREFUSED` even after starting the Airsim scene then, either there is an issue in the communication or Airsim is not properly installed.
    - There is a lot of issues pertaining to the installation of Airsim, so please do install and verify it carefully since it is a hard requirement to run the simulation.
-  Once, airsim is installed. Ensure the following ports are open and not restricted: 
    - `41451` - Airsim server port
- Ensure all the below packages are installed properly before proceeding
    - `NuGetForUnity` - 3.1.3
    - `Robotics Warehouse Shared Code` - 0.0.1-preview
    - `Robotics Warehouse URP` - 0.0.1-preview
    -  `Burst` - 1.8.2
    - `Collections` - 1.2.4
    - `Core RP Library` - 12.1.8
    - `Custom NUnit` - 1.0.6    
    - `Editor Coroutines` - 1.0.0
    - `Input System` - 1.5.1
    - `JetBrains Rider Editor` - 3.0.25
    - `Mathematics` - 1.2.6
    - `Newtonsoft Json` - 3.0.2
    - `Perception` - 0.9.0-preview.2
    - `Post Processing` - 3.2.2
    - `Python for Unity` - 4.0.0-exp.5
    - `Searcher` - 4.9.1
    - `Services Core` - 1.6.0
    - `Shader Graph` - 12.1.8
    - `Test Framework` - 1.1.31
    - `TextMeshPro` - 3.0.6
    - `Timeline` - 1.6.4
    - `Unity Render Streaming` - 3.1.0-exp.7
    - `Unity Simulation Capture` - 0.0.10-preview.24 
    - `Unity Simulation Client` - 0.0.10-preview.10
    - `Unity Simulation Core` - 0.0.10-preview.25
    - `Unity UI` - 1.0.0
    - `Universal RP` - 12.1.8
    - `Version Control` - 1.17.7
    - `Visual Studio Editor` - 2.0.21
    - `WebRTC` - 3.0.0-pre.6
- Ensure the given `settings.json` file is used. Meaning, placed under the `My Documents/Airsim/`
-  Start the simulation scene and you should see the rotor of the drones rotating.
    - If there is a toolbox window - `Render Streaming Wizard`. see that everything is checked and is green and then close it else wait for few seconds before starting the scene.
-  If you face any issues. Please check https://github.com/buvnswrn/AirsimDemo/issues?q=is%3Aissue+ for any potential workaround.

## Simulation Scenes:
- Gesture Problem -  For executing the Usecase 1
- Inspection Problem - For Executing the Usecase 2

Note: Ensure proper NavMesh data is done. Else, bake the scene once and try with the parts involving navigation. Else navigation related endpoints will fail.

