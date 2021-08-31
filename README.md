# SleightlyBall

[![](https://img.shields.io/github/stars/justsleightly/sleightlyball.svg)](https://github.com/JustSleightly/SleightlyBall/stargazers "Stars") [![](https://img.shields.io/github/tag/justsleightly/sleightlyball.svg)](https://github.com/JustSleightly/SleightlyBall/tags "Tags") [![](https://img.shields.io/github/release/justsleightly/sleightlyball.svg)](https://github.com/justsleightly/sleightlyball/releases/latest "Releases") [![](https://img.shields.io/github/issues/justsleightly/sleightlyball.svg)](https://github.com/JustSleightly/SleightlyBall/issues "Issues") [![Visits](https://badges.pufler.dev/visits/justsleightly/sleightlyball)](https://github.com/JustSleightly/SleightlyBall) [![Updated Badge](https://badges.pufler.dev/updated/justsleightly/sleightlyball)](https://github.com/JustSleightly/SleightlyBall/commits/main)

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Showcase.gif)

# Getting Started

## Importing The Prefab

<details> 

  <summary> <strong>  Activate License </strong> </summary>

######

<blockquote>

Import the SleightlyBall unitypackage into your project, and click on the SleightlyBall.prefab at the default path *Assets/JustSleightly/SleightlyBall*. 

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Prefab.gif)

If you have never used this on this PC before, you will see a field labeled **Enter your license key**. Input your license key from your purchase and click activate. This is a one-time-use key that will authorize the current PC for future use of SleightlyBall. To reset/change seats for this license, please see our automated ticketing system in Discord.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20License%20Activation.gif)

</details>

<details>

  <summary> <strong> Add to Scene </strong> </summary>

######

<blockquote>

To prepare SleightlyBall for installation, drag the SleightlyBall.prefab into the scene for Unity base scaling, then drag it onto your desired avatar. Once the prefab detects an Avatar Descriptor and Animator, the **Main Settings** will appear in the inspector.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Prefab%20Placement.gif)

<details>

  <summary>Technical Details</summary>

######

<blockquote>

The prefab can be placed anywhere below an Avatar Descriptor, and it will automatically reparent underneath your Avatar Descriptor.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Prefab%20AutoPosition.gif)

</details>

</details>

## Main Settings

<details>

  <summary> <strong> Ball Setup </strong> </summary>

######

<blockquote>

<details>

  <summary> <strong> Ball Configuration </strong> </summary>

######

<blockquote>

Select the Hand Configuration to set up the SleightlyBall system.
|  |  |
| :------------- | :------------------------------ |
| `Both Hands` | Ball Inputs Applied to Both Hands |
| `Left Handed Only` | Ball Inputs Applied to Left Hand Only |
| `Right Handed Only` | Ball Inputs Applied to Right Hand Only |

#####

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Hand%20Configuration.png)

</details>

<details>

  <summary> <strong> Separate Balls Per Hand </strong> </summary>

######

<blockquote>

Select whether to configure each hand independently or identically.
|  |  |
| :------------- | :------------------------------ |
| `Disabled` | Each Ball Input Applies to Both Hands |
| `Enabled` | Input a Ball for Each Hand |

#####

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Separate%20Balls%20per%20Hand.png)

<details>

  <summary>Technical Details</summary>

######

<blockquote>

This option is only visible if **Ball Configuration** is set to `Both Hands`.

Enabling this option also allows for independent scaling of each hands' balls and colliders during **Anchor Positioning**.

</details>

</details>

<details>

  <summary> <strong> Ball Inputs </strong> </summary>

######

<blockquote>

Use the +/- symbol to add/remove additional balls to the system, up to 8 balls. Drag in any GameObject/Prefab from your hierarchy or your project assets. Rearrange them by click/dragging into your preferred order.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Ball%20Add%20Rearrange.gif)

<details>

  <summary>Technical Details</summary>

######

<blockquote>

All GameObjects will have their root re-positioned to (0, 0, 0).

Inputting the Avatar Root or SleightlyBall's own GameObject will automatically be removed.

Any RigidBody, Spring Joint, and Configurable Joint components within any GameObjects/Prefabs inputted will be removed.

Any Sphere, Box, Capsule, and Mesh Collider components within any GameObjects/Prefabs inputted that are not set as Triggers will be removed.

Leaving an input field blank will yield a Warning. You may continue with blank fields and manually add the balls into the hierarchy later (for advanced users).

</details>

</details>

</details>

<details>

  <summary> <strong> Additional Features </strong> </summary>

######

<blockquote>

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Additional%20Features.png)

######

<details>

  <summary> <strong> Ball Distance </strong> </summary>

######

<blockquote>

Enable this feature to include a radial puppet that adjusts the distance of the hand and head ball anchors from you by a local scale of 1 - 10x. 

<details>

  <summary>Technical Details</summary>

######

<blockquote>

If FBT Mode is enabled, this also affects foot anchors.

Adds one dedicated float (8 memory) to your expression parameters.

</details>

</details>

<details>

  <summary> <strong> Ball Strength </strong></summary>

######

<blockquote>

Enable this feature to include a radial puppet that adjusts the strength at which the ball is attracted to its anchors.

<details>

  <summary>Technical Details</summary>

######

<blockquote>

Default Ball Strength can be configured under Advanced options.

Adds one dedicated float (8 memory) to your expression parameters.

</details>

</details>

<details>

  <summary> <strong> World Constraints </strong> </summary>

######

<blockquote>

Enable this feature to include four toggles to world constrain your hands, head, or chest anchors independently, allowing you to pass the balls between your body and fixed points in the world. 

<details>

  <summary>Technical Details</summary>

######

<blockquote>

If FBT Mode is enabled, two more toggles will be included to constrain each foot anchor.

Constraining your chest anchor will cause your Chest Orbit gesture control to attract like your head/hand gesture controls rather than orbit.

Adds 0 - 6 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>
  <summary> <strong> World Physics </strong> </summary>

######

<blockquote>

Enable this feature to include three toggles to enable/disable ball collision, bounce, and gravity.

<details>

  <summary>Technical Details</summary>

######

<blockquote>

Enabling World Physics adds to your Gesture Playable layer. If these layers' order is later shifted, you must run **VRLabs' [Fix Order](https://github.com/VRLabs/VRChat-Avatars-3.0#fix-order)** script to resolve the sub-animator.

Collision is off by default, due to ball collision's ability to affect world triggers (portals, distance-based mirrors, etc).

Bounce is on by default.

Gravity is off by default.

Adds 0 - 3 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> Simple Control </strong> </summary>

######

<blockquote>

Enable this feature to add a toggle to switch between simplified versus advanced **Gesture Control**.
|  |  |
| :------------- | :------------------------------ |
| `Simple` | Only Primary/Secondary gesture controls are enabled |
| `Advanced` | All seven gesture controls are enabled |

######

<details>

  <summary>Technical Details</summary>

######

<blockquote>

The definition of a 'simple' gesture can be configured from **Remap Control Gestures**.

Adds 0 - 1 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> FBT Mode </strong> </summary>

######

<blockquote>

Enable this feature to add a toggle to change the gesture control set to include feet control.

######

<details>

  <summary>Technical Details</summary>

######

<blockquote>

See Advanced Options to select an FBT Mode.

Adds 0 - 1 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

</details>

</blockquote>

<details>

  <summary> <strong> Advanced Options </strong> </summary>

######

<blockquote>

<details>

  <summary> <strong> Write Defaults </strong> </summary>

######

<blockquote>

Enabling/Disabling this option will enable/disable Write Defaults in all generated animator states for SleightlyBall. 

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Write%20Defaults.png)

######

If it says Write Defaults **(Auto)**, then this is handled automatically to match the current Write Defaults of your Animator Controller.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Write%20Defaults%20Auto.png)

<details>

  <summary>Technical Details</summary>

####

<blockquote>

If your relevant Animator Controller(s) are all set to one Write Defaults mode, the **Write Defaults** option will automatically match and be labeled with **(Auto)**

If your relevant Animator Controller has a mix of Write Defaults On and Off, a warning will appear and the **Write Defaults** option will not be labeled with **(Auto)**. This option will be available to manually enable/disable, and the generated states will follow the manually set status.

If **World Physics** is enabled and your Gesture and FX Animator Controllers are all set to one Write Defaults mode, but the Write Defaults of the Gesture and FX Animator Controllers are different, a different warning will appear and the **Write Defaults** option will not be labeled with **(Auto)**. This option will be available to manually enable/disable, and the generated states will follow the manually set status.

</details>

</details>

<details>

  <summary> <strong> Remap Control Gestures </strong> </summary>

######

<blockquote>

Enabling this feature will allow for the rearrangement of each **Gesture Control** to map to different gestures. If **Simple Control** is enabled, then the definition of a 'simple' gesture can be redefined here as well.

By default, the gesture control mapping is as follows:

| Hand Gesture Layout | Simple? | Ball Control Mapping| FBT Mode Standard | FBT Mode Complex |
| :------------- | :-------------: | :------------- | :------------- | :------------- |
| `F1 Gesture Idle` | :white_square_button: | Idle | | |
| `F2 Gesture Fist` | :white_square_button: | Head Control | Primary Foot | Primary Trigger |
| `F3 Gesture Open Hand` | :white_check_mark: | Chest Orbit | | |
| `F4 Gesture Fingerpoint` | :white_check_mark: | Primary Hand Control | | |
| `F5 Gesture Victory` | :white_square_button: | Release Ball | | |
| `F6 Gesture Rock n Roll` | :white_square_button: | Rigid Return | | |
| `F7 Gesture Handgun` | :white_check_mark: | Secondary Hand Control | | |
| `F8 Gesture Thumbs Up` | :white_square_button: | Between Hand Control | Secondary Foot | Secondary Trigger |

######

<details>

  <summary>Technical Details</summary>

####

<blockquote>

The 'Simple?' toggle checkboxes only display if **Simple Control** is enabled.

If FBT Mode is enabled, the respective FBT Mode columns will apply.

FBT Mode Complex refers to combo gesturing with the opposite hand.

If **Remap Control Gestures** is disabled, the Gesture Control mapping and Simple Control definitions will generate according to their default configuration regardless of any changes while it is enabled.

</details>

</details>

<details>

  <summary> <strong> Disable Facial Anims </strong> </summary>

######

<blockquote>

Enable this feature to force your facial expressions to maintain their defaults while a ball mode is enabled, regardless of activated gesture.

<details>

  <summary>Technical Details</summary>

######

<blockquote>

All blendshapes that exist on your Viseme Mesh set in your Avatar Descriptor are animated to the values they were set to at the time of generating SleightlyBall. Blendshapes starting with 'vrc.' are ignored

As this only accounts for blendshapes, please be wary of any non-blendshape animation properties that are triggered on gesture (eye movement, tongue toggles, etc)

Enabling this feature but not using Viseme Blendshapes mode or having a Viseme Mesh assigned in your Avatar Descriptor will yield an error

</details>

</details>

<details>

  <summary> <strong> Force Gesture Tracking </strong> </summary>

######

<blockquote>

Enable this feature to force VRC Tracking Control to set fingers to Tracking rather than Animation while a ball mode is enabled. This is only relevant to VR controllers that use finger tracking (ex. Valve Knuckles) on Avatars that use animation overrides on finger tracking.

</details>

<details>

  <summary> <strong> Include Ball Demo Mode </strong> </summary>

######

<blockquote>

Enable this feature to toggle default Unity Spheres that follow the ball's gesture control. This is often only used for either troubleshooting, demonstration, or practice purposes.

<details>

  <summary>Technical Details</summary>

####

<blockquote>

If Disable Facial Anims is enabled, Demo Mode will also disable facial animations.

Adds 0 - 1 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> Enable Move Or Copy </strong> </summary>

######

<blockquote>

Enable the ability to Move ball input sources from their respective location in the hierarchy rather than Copy them. This is typically used when trying to maintain specific component references that would otherwise break when instantiated via Copy.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Move%20Or%20Copy.png)

######

<details>

  <summary>Technical Details</summary>

######

<blockquote>

Balls are set to Copy by default, and will behave as Copy when this option is disabled.

Ball Inputs from the project assets rather than the hierarchy cannot be set to Move and will revert to Copy.

Using the same Ball source for multiple inputs and setting them to Move will yield an error, as you cannot move one object into two locations.

Using the same Ball source for multiple inputs and setting one to Move and the others to copy will instantiate the copies first during generation, before moving the remaining one.

</details>

</details>

<details>

  <summary> <strong> Default FBT Mode On </strong> </summary>

######

<blockquote>

Enable this to enable FBT Mode by default in game.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Advanced%20Options%20FBT%20Mode.png)

######

<details>

  <summary>Technical Details</summary>

######

<blockquote>

This option is only visible if **FBT Mode** is enabled.

</details>

</details>

<details>

  <summary> <strong> Save FBT Mode </strong> </summary>

######

<blockquote>

Enable this feature to have FBT mode persist between worlds/avatar loads.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Advanced%20Options%20FBT%20Mode.png)

######

<details>

  <summary>Technical Details</summary>

######

<blockquote>

This option is only visible if **FBT Mode** is enabled.

Converts **FBT Mode** to use one dedicated bool (1 memory) in your expression parameters.

</details>

</details>

<details>

  <summary> <strong> Save Control Mode </strong> </summary>

######

<blockquote>

Enable this feature to have your gesture control mode persist between worlds/avatar loads.


######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Advanced%20Options%20Simple%20Control.png)

######

<details>

  <summary>Technical Details</summary>

######

<blockquote>

This option is only visible if **Simple Control** is enabled.

Converts **Simple Control** to use one dedicated bool (1 memory) in your expression parameters.

</details>

</details>

<details>

  <summary> <strong> Default Control Mode </strong> </summary>

######

<blockquote>

Select whether Simple or Advanced gesture control mode will be set as default.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Default%20Control%20Mode.png)

######

<details>

  <summary>Technical Details</summary>

######

<blockquote>

The definition of a Simple gesture can be defined via **Remap Control Gestures**

This option is only visible if **Simple Control** is enabled.

</details>

</details>

<details>

  <summary> <strong> Select FBT Mode </strong> </summary>

######

<blockquote>

Select which FBT Mode mapping you'd like to use.
|  |  |
| :------------- | :------------------------------ |
| `Standard` | When FBT Mode is enabled, Head/Between controls are replaced with Primary/Secondary Foot control |
| `Complex` | When FBT Mode is enabled, combo gestures act as triggers to allow for entirely alternative gesture control |

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20FBT%20Mode.png)

######

<details>

  <summary>Technical Details</summary>

######

<blockquote>

In Complex mode, you use the opposite hand from the ball to hold the trigger gesture which converts your primary hand gestures to new mappings.

Complex Mode only works with one active ball at a time.

This option is only visible if **FBT Mode** is enabled.

</details>

</details>

<details>

  <summary> <strong> Default Ball Strength </strong> </summary>

######

<blockquote>

Set the default Ball Strength when loading into this avatar for the first time.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Advanced%20Options%20Strength.png)

######

<details>

  <summary>Technical Details</summary>

######

<blockquote>

This option is only visible if **Ball Strength** is enabled.

</details>

</details>

</details>

<details>

  <summary> <strong> Next Step </strong> </summary>

######

<blockquote>

Clicking this button will begin the generation of the SleightlyBall system according to the configuration of the **Main Settings** window, and proceed to **Anchor Positioning**. This button will be greyed out if there are any red errors returned in the Inspector.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Advanced%20Options%20Strength.png)

######

</details>

<details>

  <summary> <strong> Utilities </strong> </summary>

######

<blockquote>

<details>

  <summary> <strong> Memory Calculations </strong> </summary>

######

<blockquote>

Displays the Necessary Memory to generate and the Available Memory on the current Avatar's Expression Parameters.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Calculate%20Memory.png)

######

<details>

  <summary>Necessary Memory can be calculated as:</summary>
  
######

<blockquote>

![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20Total%20Necessary%20Memory%20%3D%20Local%20Synced%20Memory%20&plus;%20Network%20Synced%20Memory)

######

where:

######

![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20Local%20Synced%20Memory%20%3D%20%5Cbegin%7Bcases%7D%20%26%20Local%20Bools%20%5Ctext%7B%20if%20%7D%20Local%20Bools%3C%208%20%5C%5C%20%26%208%20%5Ctext%7B%20if%20%7D%20Local%20Bools%20%5Cgeq%208%20%5Cend%7Bcases%7D)

######

![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20Local%20Bools%20%3D%20%5Csum%20Enabled%20Local%20Bools%7D)

######

![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20%5Cleft.%5Cbegin%7Bmatrix%7D%203%20%26%20WorldPhysics%20%5C%5C%204%20%26%20WorldConstraints%20%5C%5C%202%20%26%20WorldConstraints%5C%26FBTMode%20%5C%5C%201%20%26%20BallDemoMode%20%5C%5C%201%20%26%20%21%28%28SaveControlMode%29%5C%26SimpleControl%29%20%5C%5C%201%20%26%20%21%28%28SaveFBTMode%29%5C%26FBTMode%29%20%5C%5C%202%20*%20BallCount%20%26%20BothHands%20%5C%5C%201%20*%20BallCount%20%26%20LeftHandedOnly%20%5C%5C%201%20*%20BallCount%20%26%20RightHandedOnly%20%5C%5C%20%5Cend%7Bmatrix%7D%5Cright%5C%7D%20%5CRightarrow%20%5Csum%20EnabledLocalBools%7D)

######

and:

######

![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20Network%20Synced%20Memory%20%3D%20%5Csum%20Enabled%20Synced%20Memory)

######

![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20%5Cleft.%5Cbegin%7Bmatrix%7D%203%20%26%20BallDistance%5C%5C%204%20%26%20BallStrength%20%5C%5C%202%20%26%20SaveControlMode%5C%26SimpleControl%20%5C%5C%201%20%26%20SaveFBTMode%5C%26FBTMode%5C%5C%20%5Cend%7Bmatrix%7D%5Cright%5C%7D%20%5CRightarrow%20%5Csum%20EnabledSyncedMemory%7D)

######

</details>

</details>

<details>

  <summary> <strong> Warnings/Errors </strong> </summary>

######

<blockquote>

<details>

  <summary> <strong> ERROR: No Avatar Descriptor Detected </strong> </summary>

######

<blockquote>

Triggers if no Avatar Descriptor component can be detected in any parents of the current GameObject.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20No%20Animator.png)

######

</details>

######

<details>

  <summary> <strong> ERROR: No Animator Detected </strong> </summary>

######

<blockquote>

Triggers if no Animator component is found on the Avatar Descriptor GameObject.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20No%20Avatar%20Descriptor.png)

######

</details>

######

<details>

  <summary> <strong> ERROR: Not Enough Memory </strong> </summary>

######

<blockquote>

Triggers if the Expressions Menu does not have enough available memory to satisfy the features configured in **Main Settings**.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20Insufficient%20Memory.png)

######

</details>

######

<details>

  <summary> <strong> ERROR: Not Enough Menu Space </strong> </summary>

######

<blockquote>

Triggers if the Expressions Menu in the Avatar Descriptor already has 8 controls.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20Menu%20Space.png)

######

</details>

######

<details>

  <summary> <strong> ERROR: Model Not Humanoid </strong> </summary>

######

<blockquote>

Triggers if the model's FBX is not set to Humanoid rig configuration.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20Humanoid.png)

######

</details>

######

<details>

  <summary> <strong> ERROR: Left Hand Not Mapped </strong> </summary>

######

<blockquote>

Triggers if the model's humanoid rig configuration does not have the left hand mapped.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20Left%20Hand.png)

######

</details>

######

<details>

  <summary> <strong> ERROR: Right Hand Not Mapped </strong> </summary>

######

<blockquote>

Triggers if the model's humanoid rig configuration does not have the right hand mapped.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20Right%20Hand.png)

######

</details>

######

<details>

  <summary> <strong> ERROR: Feet Not Mapped </strong> </summary>

######

<blockquote>

Triggers if the model's humanoid rig configuration does not have both feet mapped, and **FBT Mode** is enabled.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20FBT%20Mapping.png)

######

</details>

######

<details>

  <summary> <strong> ERROR: Viseme Mesh Not Detected </strong> </summary>

######

<blockquote>

Triggers if no Viseme Mesh is detected on the Avatar Descriptor or if the Viseme Mode is not set to Blendshape, while **Disable Facial Anims** is enabled.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20Viseme%20Mesh.png)

######

</details>

######

<details>

  <summary> <strong> ERROR: Duplicate Ball Inputs Set To Move </strong> </summary>

######

<blockquote>

Triggers if multiple Ball Inputs have the same source GameObject, **Move Or Copy** is enabled, and those inputs are set to Move. The same GameObject cannot be moved to multiple locations at once.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20Move%20Multiple.png)

######

</details>

######

<details>

  <summary> <strong> WARNING: Empty Ball Inputs </strong> </summary>

######

<blockquote>

Triggers if any Ball Input fields are left blank. Balls can be added after the hierarchy is generated, but you will not be able to take advantage of any of the positioning/scaling tools.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Warning%20Empty%20Ball%20Inputs.png)

######

</details>

######

<details>

  <summary> <strong> WARNING: Mixed Write Defaults </strong> </summary>

######

<blockquote>

Triggers if both Write Defaults On and Off are detected in your FX Controller, or Gesture Controller if **World Physics** is enabled. Continuing will use whichever value of **Write Defaults** you set under **Advanced Options**.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Warning%20Mixed%20Write%20Defaults.png)

######

</details>

######

<details>

  <summary> <strong> WARNING: FX/Gesture Different Write Defaults </strong> </summary>

######

<blockquote>

Triggers if **World Physics** is enabled and your FX and Gesture controllers use different Write Defaults. Continuing will use whichever value of **Write Defaults** you set under **Advanced Options**.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Warning%20Different%20Write%20Defaults.png)

######

</details>

######

<details>

  <summary> <strong> WARNING: Default Controllers/Expressions Detected </strong> </summary>

######

<blockquote>

Triggers if the FX Controller, Expression Parameters, or Expressions Menu in your Avatar Descriptor is either default or empty. If **World Physics** is enabled, the Gesture Controller also triggers this warning.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Warning%20Default%20Expressions.png)

######

</details>

######

<details>

  <summary> <strong> ERROR: Double Layer Rig Bug Detected </strong> </summary>

######

<blockquote>

Triggers if your Avatar Descriptor has two FX Playable Layers. Pressing Fix will restore the Action Playable Layer for you, but you will need to re-populate any custom layers you had previously set here.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20Double%20FX%20Layer%20Bug.png)

######

This is a known VRCSDK bug that occurs when switching the FBX of a model between Generic and Humanoid rigs when it already has an Avatar Descriptor in the scene. 

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Double%20FX%20Layer%20Bug%20Example.png)

</details>

</details>

<details>

  <summary> <strong> Delete SleightlyBall From Avatar </strong> </summary>

######

<blockquote>

Deletes any trace of SleightlyBall out of the avatar's hierarchy and Avatar Descriptor.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Delete%20Button.png)

######

<details>

  <summary> <strong> Technical Details </strong> </summary>

######

<blockquote>

Deletes Hierarchy: Any GameObjects with the Prefix "SB".

Deletes Controller Layers: Any Layers with the SB Identifier on the AnyState.

Deletes Controller Parameters: Any Parameters with the Prefix "SB".

Deletes From Expressions Menu: Any SubMenu whose name contains "SleightlyBall" or leads to a SubMenu with the Prefix "SB".

Deletes From Expression Parameters: Any Parameters with the Prefix "SB".

<blockquote>

</details>

</details>

<details>

  <summary> <strong> Delete ALL Generated Resources </strong> </summary>

######

<blockquote>

Deletes the Generated Resources folder at path *Assets/JustSleightly/SleightlyBall/GeneratedResources*. This may contain files for more than just the current avatar if you have generated SleightlyBall multiple times in this project.

######

![](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Delete%20Button.png)

######

</details>

<details>

  <summary> <strong> Check For Updates </strong> </summary>

######

<blockquote>

Click the circular arrow next to the version number in the bottom left to check for newer versions of SleightlyBall. If a new version is detected, the arrow will turn into a red X and a pop-up window will prompt you to download it. Otherwise, the arrow will turn into a green checkmark.

</details>

</details>

## Anchor Positioning

<details>

  <summary> <strong> Edit Anchors </strong> </summary>

<blockquote>

<details>

  <summary> <strong> Edit Hand Anchors </strong> </summary>

######

<blockquote>

</details>

<details>

  <summary> <strong> Edit Head Anchor </strong> </summary>

######

<blockquote>

</details>

<details>

  <summary> <strong> Edit Foot Anchors </strong> </summary>

######

<blockquote>

</details>

</details>

<details>

  <summary> <strong> Edit Orbit Radius </strong> </summary>
  
<blockquote>

<details>

  <summary> <strong> Edit Chest Orbit Radius </strong> </summary>

######

<blockquote>

</details>

<details>

  <summary> <strong> Edit Feet Orbit Radius </strong> </summary>

######

<blockquote>

</details>

</details>

<details>

  <summary> <strong> Edit Ball Size</strong> </summary>

######

<blockquote>

</details>

<details>

  <summary> <strong> Edit Physics Collider Size</strong> </summary>

######

<blockquote>

</details>

<details>

  <summary> <strong> Complete Setup </strong> </summary>

######

<blockquote>

</details>

# Usage

# Frequently Asked Questions

## Special Thanks
