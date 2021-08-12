
# SleightlyBall

[![](https://img.shields.io/github/stars/justsleightly/sleightlyball.svg)](https://github.com/JustSleightly/SleightlyBall/stargazers "Stars") [![](https://img.shields.io/github/tag/justsleightly/sleightlyball.svg)](https://github.com/JustSleightly/SleightlyBall/tags "Tags") [![](https://img.shields.io/github/release/justsleightly/sleightlyball.svg)](https://github.com/justsleightly/sleightlyball/releases/latest "Releases") [![](https://img.shields.io/github/issues/justsleightly/sleightlyball.svg)](https://github.com/JustSleightly/SleightlyBall/issues "Issues")

# Information

# Instructions

### Activate License
<details>
  <summary> </summary>

######
Import the SleightlyBall unitypackage into your project, and click on the SleightlyBall.prefab at the default path *Assets/JustSleightly/SleightlyBall*. If you have never used this on this PC before, you will see a field labeled **Enter your license key**. Input your license key from your purchase and click activate. This is a one-time-use key that will authorize the current PC for future use of SleightlyBall. To reset/change seats for this license, please see our automated ticketing system in Discord.
</details>

### Add to Scene
<details>
  <summary> </summary>

######
To prepare SleightlyBall for installation, drag the SleightlyBall.prefab into the scene for Unity base scaling, then drag it onto your desired avatar. Once the prefab detects an Avatar Descriptor and Animator, the **Main Settings** will appear in the inspector.
</details>

## Main Settings
<details>
  <summary> Ball Setup </summary>

######
### Ball Configuration
Select the Hand Configuration to set up the SleightlyBall system
|  |  |
| :------------- | :------------------------------ |
| `Both Hands` | Ball Inputs Applied to Both Hands |
| `Left Handed Only` | Ball Inputs Applied to Left Hand Only |
| `Right Handed Only` | Ball Inputs Applied to Right Hand Only |

### Separate Balls Per Hand

######
Select whether to configure each hand independently or identically
|  |  |
| :------------- | :------------------------------ |
| `Disabled` | Each Ball Input Applies to Both Hands |
| `Enabled` | Input a Ball for Each Hand |

#####
<blockquote><details>
  <summary>Technical Details</summary>

######
This option is only visible if **Ball Configuration** is set to `Both Hands`

Enabling this option also allows for independent scaling of each hands' balls and colliders during **Anchor Positioning**
</details></blockquote>

### Ball Inputs

######
Use the +/- symbol to add/remove additional balls to the system, up to 8 balls. Drag in any GameObject/Prefab from your hierarchy or your project assets. Rearrange them by click/dragging into your preferred order.

<blockquote><details>
  <summary>Technical Details</summary>

######
 Any RigidBody, Spring Joint, and Configurable Joint components within any GameObjects/Prefabs inputted will be removed

Any Sphere, Box, Capsule, and Mesh Collider components within any GameObjects/Prefabs inputted that are not set as Triggers will be removed

Leaving an input field blank will yield a Warning. You may continue with blank fields and manually add the balls into the hierarchy later (for advanced users)
</details></blockquote>

</details>

### Additional Features

#### Ball Distance
<details>
  <summary> </summary>

######
Enable this feature to include a radial puppet that adjusts the distance of the hand and head ball anchors from you by a local scale of 1 - 10x. 

<blockquote><details>
  <summary>Technical Details</summary>

######
 Adds one dedicated float (8 memory) to your expression parameters.
</details></blockquote>

</details>

#### Ball Strength
<details>
  <summary> </summary>

######
Enable this feature to include a radial puppet that adjusts the strength at which the ball is attracted to its anchors. 

<blockquote><details>
  <summary>Technical Details</summary>

######
Adds one dedicated float (8 memory) to your expression parameters.
</details></blockquote>

</details>

#### World Constraints
<details>
  <summary> </summary>

######
Enable this feature to include four toggles to world constrain your hands, head, or chest anchors independently, allowing you to pass the balls between your body and fixed points in the world. 

<blockquote><details>
  <summary>Technical Details</summary>

######
Constraining your chest anchor will cause your Chest Orbit gesture control to attract like your head/hand gesture controls rather than orbit.

Adds 0 - 4 memory to your expression parameters (See **Memory Calculations** for more details).
</details></blockquote>

</details>

#### World Physics
<details>
  <summary> </summary>

######
Enable this feature to include three toggles to enable/disable ball collision, bounce, and gravity.

<blockquote><details>
  <summary>Technical Details</summary>

######
Enabling World Physics adds to your Gesture Playable layer. If these layers' order is later shifted, you must run VRLabs' [Fix Order](https://github.com/VRLabs/VRChat-Avatars-3.0#fix-order) script to resolve the sub-animator.

Collision is off by default, due to ball collision's ability to affect world triggers (portals, distance-based mirrors, etc).

Bounce is on by default.

Gravity is off by default.

Adds 0 - 3 memory to your expression parameters (See **Memory Calculations** for more details).
</details></blockquote>

</details>

### Advanced Options

#### Simple Control
<details>
  <summary> </summary>

######
Enable this feature to add a toggle to switch between simplified versus advanced **Gesture Control**.
|  |  |
| :------------- | :------------------------------ |
| `Simple` | Only Primary/Secondary gesture controls are enabled |
| `Advanced` | All seven gesture controls are enabled |

######
<blockquote><details>
  <summary>Technical Details</summary>

######
The definition of a 'simple' gesture can be configured from **Remap Control Gestures**

Adds 0 - 1 memory to your expression parameters (See **Memory Calculations** for more details).
</details></blockquote>

</details>

##### Default Control Mode
<details>
  <summary> </summary>

######
Select whether Simple or Advanced gesture control mode will be set as default.

<blockquote><details>
  <summary>Technical Details</summary>

######
This option is only visible if **Simple Control** is enabled
</details></blockquote>

</details>

##### Save Control Mode
<details>
  <summary> </summary>

######
Enable this feature to have your gesture control mode persist between worlds/avatar loads.

<blockquote><details>
  <summary>Technical Details</summary>

######
This option is only visible if **Simple Control** is enabled

Converts **Simple Control** to use one dedicated bool (1 memory) in your expression parameters.
</details></blockquote>

</details>

#### Disable Facial Anims
<details>
  <summary> </summary>

######
Enable this feature to force your facial expressions to maintain their defaults while a ball mode is enabled, regardless of activated gesture.

<blockquote><details>
  <summary>Technical Details</summary>

######
All blendshapes that exist on your Viseme Mesh set in your Avatar Descriptor are animated to the values they were set to at the time of generating SleightlyBall. Blendshapes starting with 'vrc.' are ignored

As this only accounts for blendshapes, please be wary of any non-blendshape animation properties that are triggered on gesture (eye movement, tongue toggles, etc)

Enabling this feature but not using Viseme Blendshapes mode or having a Viseme Mesh assigned in your Avatar Descriptor will yield an error
</details></blockquote>

</details>

#### Force Gesture Tracking
<details>
  <summary> </summary>

######
Enable this feature to force VRC Tracking Control to set fingers to Tracking rather than Animation while a ball mode is enabled. This is only relevant to VR controllers that use finger tracking (ex. Valve Knuckles) on Avatars that use animation overrides on finger tracking.
</details>

#### Ball Demo Mode
<details>
  <summary> </summary>

######
Enable this feature to toggle default Unity Spheres that follow the ball's gesture control. This is often only used for either troubleshooting, demonstration, or practice purposes.

<blockquote><details>
  <summary>Technical Details</summary>

####
Adds 0 - 1 memory to your expression parameters (See **Memory Calculations** for more details).
</details></blockquote>

</details>

#### Write Defaults
<details>
  <summary> </summary>

######
Enabling/Disabling this option will enable/disable Write Defaults in all generated animator states for SleightlyBall. If it says Write Defaults **(Auto)**, then this is handled automatically to match the current Write Defaults of your Animator Controller.

<blockquote><details>
  <summary>Technical Details</summary>

####
If your relevant Animator Controller(s) are all set to one Write Defaults mode, the **Write Defaults** option will automatically match and be labeled with **(Auto)**

If your relevant Animator Controller has a mix of Write Defaults On and Off, a warning will appear and the **Write Defaults** option will not be labeled with **(Auto)**. This option will be available to manually enable/disable, and the generated states will follow the manually set status.

If **World Physics** is enabled and your Gesture and FX Animator Controllers are all set to one Write Defaults mode, but the Write Defaults of the Gesture and FX Animator Controllers are different, a different warning will appear and the **Write Defaults** option will not be labeled with **(Auto)**. This option will be available to manually enable/disable, and the generated states will follow the manually set status.
</details></blockquote>

</details>

#### Remap Control Gestures
<details>
  <summary> </summary>

######
Enabling this feature will allow for the rearrangement of each **Gesture Control** to map to different gestures. If **Simple Control** is enabled, then the definition of a 'simple' gesture can be redefined here as well.

By default, the gesture control mapping is as follows:

| Hand Gesture Layout | Simple? | Ball Control Mapping|
| :------------- | :-------------: | :------------- |
| `F1 Gesture Idle` | :white_square_button: | Idle |
| `F2 Gesture Fist` | :white_square_button: | Head Control |
| `F3 Gesture Open Hand` | :white_square_button: | Chest Orbit |
| `F4 Gesture Fingerpoint` | :white_check_mark: | Primary Hand Control |
| `F5 Gesture Victory` | :white_square_button: | Release Ball |
| `F6 Gesture Rock n Roll` | :white_square_button: | Rigid Return |
| `F7 Gesture Handgun` | :white_check_mark: | Secondary Hand Control |
| `F8 Gesture Thumbs Up` | :white_square_button: | Between Hand Control |

######
<blockquote><details>
  <summary>Technical Details</summary>

####
The 'Simple?' toggle checkboxes only display if **Simple Control** is enabled

If **Remap Control Gestures** is disabled, the Gesture Control mapping and Simple Control definitions will generate according to their default configuration regardless of any changes while it is enabled
</details></blockquote>

</details>

### Memory Calculations
<details>
  <summary> </summary>

######
Displays the Necessary Memory to generate and the Available Memory on the current Avatar's Expression Parameters.

<blockquote><details>
  <summary>Necessary Memory can be calculated as:</summary>
  
  ######
![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20Total%20Necessary%20Memory%20%3D%20Local%20Synced%20Memory%20&plus;%20Network%20Synced%20Memory)

where:

![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20Local%20Synced%20Memory%20%3D%20%5Cbegin%7Bcases%7D%20%26%20Local%20Bools%20%5Ctext%7B%20if%20%7D%20Local%20Bools%3C%208%20%5C%5C%20%26%208%20%5Ctext%7B%20if%20%7D%20Local%20Bools%20%5Cgeq%208%20%5Cend%7Bcases%7D)

![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20Local%20Bools%20%3D%20%5Csum%20Enabled%20Local%20Bools%7D)

![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20%5Cleft.%5Cbegin%7Bmatrix%7D%203%26%20World%20Physics%5C%5C%204%26%20World%20Constraints%5C%5C%201%26%20Ball%20Demo%20Mode%5C%5C%201%26%20%21%28Save%20Control%20Mode%29%20%5C%26%20Simple%20Control%29%5C%5C%202%20*%20Ball%20Count%26%20Both%20Hands%5C%5C%201%20*%20Ball%20Count%26%20Left%20Handed%20Only%5C%5C%201%20*%20Ball%20Count%26%20Right%20Handed%20Only%20%5Cend%7Bmatrix%7D%5Cright%5C%7D%20%5CRightarrow%20%5Csum%20Enabled%20Local%20Bools)

and:

![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20Network%20Synced%20Memory%20%3D%20%5Csum%20Enabled%20Synced%20Memory)

![equation](https://latex.codecogs.com/png.latex?%5Cfn_jvn%20%7B%5Ccolor%7BMagenta%7D%20%5Cleft.%5Cbegin%7Bmatrix%7D%208%20%26%20Ball%20Distance%5C%5C%208%20%26%20Ball%20Strength%5C%5C%201%20%26%20Save%20Control%20Mode%20%5C%26%20Simple%20Control%20%5Cend%7Bmatrix%7D%5Cright%5C%7D%20%5CRightarrow%20%5Csum%20Enabled%20Synced%20Memory)
</details></blockquote>

</details>

### Warnings/Errors

### Next Step

### Delete SleightlyBall From Avatar

### Delete ALL Generated Resources

### Check For Updates

## Anchor Positioning

### Edit Hand Anchors

### Edit Head Anchor

### Edit Orbit Radius

### Edit Ball Size

### Edit Physics Collider Size

### Complete Setup
