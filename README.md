<p align="center">
  <img src="https://github.com/user-attachments/assets/c67c1713-4f2b-4a15-967a-299aeea7276c" width="200" style="margin: 0 auto;"/>
</p>

# MagicKlaw
MagicKlaw is a game for iOS using 3D physics to simulate the experience of playing at a claw machine in an arcade. Complete with all the fun, challenge, and rewards you'd expect from the classic arcade experience. The game is made in Unity with C# with custom assets/models created using Blender.

## Narrative
Your Great Grandfather Albert was no ordinary wizard—he was a bundle of joy who lived to spread laughter and fun. One day, he cast a spell on himself and transformed into a magical claw, becoming Clawbert, so he could share his joy with the world through the wonder of a claw machine!

## Enter the Pocket Dimension
In the game, you play as Albert’s great-grandchild who stumbles upon the enchanting pocket dimension Clawbert has created. Here, fun takes center stage, and your arcade adventure begins!

## In-game Screenshots

<img src="https://github.com/user-attachments/assets/fdd046ce-865e-4be9-b40d-b6d06709bee3" height="512"/>
<img src="https://github.com/user-attachments/assets/b581538a-0a70-41cd-a7dd-8082e3fe6c8e" height="512"/>
<img src="https://github.com/user-attachments/assets/3a4a1686-d6e8-40c6-964c-69c1f3ddff2e" height="512"/>
<img src="https://github.com/user-attachments/assets/76bba06d-aada-47d9-addf-b80e40fb47f8" height="512"/>

## iOS Build Instructions

Due to the nature of the iOS build, it is quite a bit more involved than the standalone Windows and Android versions.  To build the iOS/MacOS version, you will need a Mac device. The instructions for the setup is below:

1. Download the iOS/MacOS version from the link above.
2. Unzip the file & open the xCode project file within.
3. On the left-side panel within xCode, click the topmost project folder to open the Project Settings
4. In the Signing & Capabilities menu tab, enable Automatically Manage Signing.
5. Additionally, set the team, and change the bundle ID to anything unique (e.g. Add your name, random characters) and press Try Again to finish the setup.
6. If you are building for MacOS and not for iOS, you may skip to step 9.
7. Make sure your iPhone is connected & developer mode is enabled. (See [here](https://developer.apple.com/documentation/xcode/enabling-developer-mode-on-a-device) how to do this)
8. Ensure your iPhone is selected as the target device in the top middle bar of xCode.
9. Press the Play/Build button in the top-left of the title bar to build & run the game.
