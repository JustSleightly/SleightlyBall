# SleightlyBall System [<img src="https://github.com/JustSleightly/Resources/raw/main/Icons/JSLogo.png" width="30" height="30">](https://vrc.sleightly.dev/ "JustSleightly") [<img src="https://github.com/JustSleightly/Resources/raw/main/Icons/Discord.png" width="30" height="30">](https://discord.sleightly.dev/ "Discord") [<img src="https://github.com/JustSleightly/Resources/raw/main/Icons/GitHub.png" width="30" height="30">](https://github.sleightly.dev/ "Github") [<img src="https://github.com/JustSleightly/Resources/raw/main/Icons/Store.png" width="30" height="30">](https://store.sleightly.dev/ "Store")

[![GitHub stars](https://img.shields.io/github/stars/JustSleightly/SleightlyBall)](https://github.com/JustSleightly/SleightlyBall/stargazers) [![GitHub Tags](https://img.shields.io/github/tag/JustSleightly/SleightlyBall)](https://github.com/JustSleightly/SleightlyBall/tags) [![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/JustSleightly/SleightlyBall?include_prereleases)](https://github.com/JustSleightly/SleightlyBall/releases) [![GitHub issues](https://img.shields.io/github/issues/JustSleightly/SleightlyBall)](https://github.com/JustSleightly/SleightlyBall/issues) [![GitHub last commit](https://img.shields.io/github/last-commit/JustSleightly/SleightlyBall)](https://github.com/JustSleightly/SleightlyBall/commits/main) [![Discord](https://img.shields.io/discord/780192344800362506)](https://discord.sleightly.dev/)

![SB Gumroad Showcase gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Gumroad%20Showcase.gif)

**SleightlyBall** is a "spring joint ball" like system built for **VRChat** users. It is the most customizable, modular, feature-rich ball system with an automatic setup tool, allowing for 2 step installation without any VRChat 3.0 or advanced Unity experience whatsoever.

This is a **system** and does not include any balls in its own package. Please import your own.

## Available now at [store.sleightly.dev](https://store.sleightly.dev/)

<img src="https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20CJ%20Demo.gif" height="280"> <img src="https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Default%20Settings.png" height="280">

### Features

- **Drag and drop setup** - works with **any** object, not just balls
- Supports balls on either (or **both**) hands
- Supports up to **8 balls per hand**
- Multiple anchor points around the body - pass the ball between hands, head, chest, even the feet or world
- Configurable ball **distance** and/or **strength** from in-game
- **Constrain** any of your anchors in world space or local space and still control balls to and from them
- Mesh based physics (not particle) which works with **any** object, including **collision, bounce, and gravity** toggles
- **Throw/Shoot** modes you can toggle between
- **Share** your balls with other players! **Constrain** it to them, or make it **orbit** them
- FBT Mode options to also control the balls with your **feet**
- Smart Dynamic Audio supports up to **8 audios** both played **aloud or locally**
- **Pilot** the ball like a drone **without** using a constraint-based piloting system, meaning less desync
- Toggle between simple/complex gesture sets in case you want to manage less gestures
- **Automatic Write Defaults detection** and compatibility with both on/off
- **Drag and drop gesture remapping** to any configuration you prefer
- **Automatically disable facial expressions** while controlling the balls
- **Automatically optimizes your parameter memory** saving up to 46 memory other systems would use. **Up to 54/59 (91.5%)** of the menu options can fit **within 8 memory!**

| Specifications | Minimum | Default | Max | Unoptimized |
| :--- | :--- | :--- | :--- | :--- |
| `Memory` | 1 | 32 | 55 | 87 |
| `Icons` | 2 | 33 | 57 | 56 |
| `FX Layers` | 5 | 43 | 77 | 54 |
| `Animation Clips` | 15 | 101 | 167 | 148 |

## Showcase / Performance Reel

[<img src="https://img.youtube.com/vi/p-oQoq1jhgk/0.jpg" width="410">](https://www.youtube.com/watch?v=p-oQoq1jhgk "SleightlyBall Showcase") [<img src="https://img.youtube.com/vi/FAZC2S2NiLU/0.jpg" width="410">](https://www.youtube.com/watch?v=FAZC2S2NiLU "SleightlyBall Performance Reel")

## V2 Update

[Patch Notes](https://github.com/JustSleightly/SleightlyBall/releases)

[<img src="https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20V2%20Title.gif" height="280">](https://www.youtube.com/watch?v=XxFettcttWk "SleightlyBall V2 Update")

<details>

  <summary> <strong> Full Demo GIF </strong> </summary>
​
<blockquote>

![SB Script Showcase gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Script%20Showcase.gif)

</details>

---

# Requirements

1. Basic Unity experience + VRChat SDK3 uploading experience.
2. A **validated** license key for first time activation.
    1. License keys can be purchased from my [store](https://store.sleightly.dev/).
    2. Keys must be validated by joining my [discord](https://discord.sleightly.dev/) and opening a ticket with my automated discord bot.
3. An active **internet connection** while in Unity in order to use the tool - cannot be used offline.
4. Only compatible with Unity for **Windows** - not compatible with Unity for Mac/Linux at this time.
5. Pre-requisite import - [VRChat Creator Companion SDK](https://vrchat.com/home/download) version `3.1.13` or newer.

---

# Installation

### Unity Installation Guide Video

[![SleightlyBall Unity Installation Guide](http://img.youtube.com/vi/JV56OLPQJi8/0.jpg)](http://www.youtube.com/watch?v=JV56OLPQJi8 "SleightlyBall Unity Installation Guide")

SleightlyBall's installer now looks *sleightly* different than at the time of this video recording.

### Importing The Prefab

<details>

  <summary> <strong> Add to Scene </strong> </summary>
​
<blockquote>

To add SleightlyBall to your scene, click on **JustSleightly** in the top toolbar, and click on the **SleightlyBall** menu option. You can also press **Alt + S** for *SleightlyBall*.

This will add the installer onto the first active loaded Avatar Descriptor in the scene.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

If you have any GameObjects selected in the scene, clicking the Menu Item for SleightlyBall will search all selected objects and parents first for an Avatar Descriptor.

If there are no active Avatar Descriptors found in the scene, the installer will be added to the base scene.

</details>

</details>

<details>

  <summary> <strong>  Activate License </strong> </summary>
​
<blockquote>

If you have never used this on this PC before, you will see a field labeled **Enter your license key**. Make sure you've validated your license key on the [Discord](https://discord.sleightly.dev/) server, then input your license key from your purchase and click activate. This is a one-time-use key that will authorize the current PC for future use of SleightlyBall.

You will also be prompted to come up with a security question and password. These will be used if you ever need to reset/transfer your license, so please remember your selection. Please don't use any sensitive information for your responses.

If your license key is not working due to it already being in use, click the *Transfer License* option.

</details>

### Main Settings

<details>

  <summary> <strong> Ball Setup </strong> </summary>
​
<blockquote>

<details>

  <summary> <strong> Ball Configuration </strong> </summary>
​
<blockquote>

Select the Hand Configuration to set up the SleightlyBall system.
|  |  |
| :------------- | :------------------------------ |
| `Both Hands` | Ball Inputs Applied to Both Hands |
| `Left Handed Only` | Ball Inputs Applied to Left Hand Only |
| `Right Handed Only` | Ball Inputs Applied to Right Hand Only |

![SB Hand Configuration png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Hand%20Configuration.png)

</details>

<details>

  <summary> <strong> Ball Inputs </strong> </summary>
​
<blockquote>

Use the +/- symbol to add/remove additional balls to the system, up to 8 balls. Drag in any GameObject/Prefab from your hierarchy or your project assets. Rearrange them by click/dragging into your preferred order.

If you have an option for Individual/Shared control, please see the related section under [Animator Pseudo API](https://github.com/JustSleightly/SleightlyBall#animator-pseudo-api).

![SB Ball Add Rearrange gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Ball%20Add%20Rearrange.gif)

<details>

  <summary> Technical Details </summary>
​
<blockquote>

All GameObjects will have their root re-positioned to (0, 0, 0).

If the input GameObject is a prefab, the prefab will be unpacked.

Inputting the Avatar Root or SleightlyBall's own GameObject will automatically be removed.

Any RigidBody, Spring Joint, and Configurable Joint components within any GameObjects/Prefabs inputted will be removed.

Any Sphere, Box, Capsule, and Mesh Collider components within any GameObjects/Prefabs inputted that are not set as Triggers will be removed.

Leaving an input field blank will yield a Warning. You may continue with blank fields and manually add the balls into the hierarchy later (for advanced users).

</details>

</details>

</details>

<details>

  <summary> <strong> Additional Features </strong> </summary>
​
<blockquote>

![SB Additional Features png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Additional%20Features.png)

<details>

  <summary> <strong> Ball Distance </strong> </summary>
​
<blockquote>

Enable this feature to include a radial puppet that adjusts the distance of the hand and head ball anchors from you by a local scale of 1 - 10x.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

This also affects your orbit radius, but the radius may be scaled differently than your hand anchor distance depending on your initial set radius.

If FBT Mode is enabled, this also affects foot anchors and foot orbits.

Adds one dedicated float (8 memory) to your expression parameters.

</details>

</details>

<details>

  <summary> <strong> Ball Strength </strong></summary>
​
<blockquote>

Enable this feature to include a radial puppet that adjusts the strength at which the ball is attracted to its anchors.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

Default Ball Strength can be configured under Advanced options.

Adds one dedicated float (8 memory) to your expression parameters.

</details>

</details>

<details>

  <summary> <strong> World Constraints </strong> </summary>
​
<blockquote>

Enable this feature to include four toggles to world constrain your hands, head, or chest anchors independently, allowing you to pass the balls between your body and fixed points in the world.

Enable **Local Space** to constrain them to your Avatar instead of the World, such as simulating Follower behaviour.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

If FBT Mode is enabled, two more toggles will be included to constrain each foot anchor.

Constraining your chest anchor will cause your Chest Orbit gesture control to attract like your head/hand gesture controls rather than orbit.

Enabling Local Space will disable any currently active World Constraints.

World Constraints remember their dropped rotation as well.

Adds 0 - 7 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> World Physics </strong> </summary>
​
<blockquote>

Enable this feature to include three toggles to enable/disable ball collision, bounce, and gravity.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

The ball’s collision, when enabled, can affect world triggers (portals, distance-based mirrors, etc).

Collision is on by default.

Bounce is on by default.

Gravity is off by default.

Adds 0 - 3 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> Simple Control </strong> </summary>
​
<blockquote>

Enable this feature to add a toggle to switch between simplified versus advanced **Gesture Control**.
|  |  |
| :------------- | :------------------------------ |
| `Simple` | Only 'simple' gesture controls are enabled |
| `Advanced` | All seven gesture controls are enabled |

<details>

  <summary> Technical Details </summary>
​
<blockquote>

By default, Primary, Secondary, and Orbit are considered `Simple` gestures.

The definition of a `Simple` gesture can be configured from **Remap Control Gestures**.

Adds 0 - 1 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> Shoot Toggle </strong> </summary>
​
<blockquote>

Enable this feature to add a toggle to switch between ball throw vs ball shoot.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

The shoot forward driver lasts 0.25 seconds which can result in unique behaviors, such as briefly curving the shot, or slowing down on impact if shot into a surface with collision enabled at short range.

Adds 0 - 1 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> FBT Mode </strong> </summary>
​
<blockquote>

Enable this feature to add a toggle to change the gesture control set to include feet control.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

See Advanced Options to select an FBT Mode.

Adds 0 - 1 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> Pilot Mode </strong> </summary>
​
<blockquote>

Enable this feature to add a two-axis puppet control for each enabled hand.

The puppet menu, by default, pilots position on the XZ plane: AKA Moving Forward, Moving Backward, Strafing Left, and Strafing Right.

**If you do a Thumbs Up gesture** in either hand while the puppet menu is open, the axes swap to XY controls, replacing Forward and Backward with Up and Down.

Closing the puppet menu will have the ball maintain its position in world space, until you **activate your Rigid Return gesture while the menu is closed**.

*While the piloting is less desynced than your typical constraint based piloting system, it is still not in perfect sync due to Unity Physics in VRC and other network difficulties. Please be aware others may not see the ball in the exact same location you do.*

<details>

  <summary> Technical Details </summary>
​
<blockquote>

The ball piloting rotation is only constrained to your head's Y rotation. This means you can turn your head left/right to steer the ball, but the ball will never move up or down unless you Thumbs Up.

Adds 17 - 18 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> Hide On Idle </strong> </summary>
​
<blockquote>

Enable this feature to add a toggle that hides the ball when performing the Idle gesture.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

When using **Simple Control**, non-simple controls will also hide the ball.

Adds 0 - 1 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> Ball Audio </strong> </summary>
​
<blockquote>

Enable this feature to add up to 8 audio sources to attach to the balls.

Audio can be enabled, disabled, or played locally only.

![SB Audio List png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Audio%20List.png)

If you add more than one audio, you can select from any of them in-game.

Balls will play their default audio unless a Song Override is selected.

If a song override is cleared, the balls will return to their default audio.

![SB Audio Name Default png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Audio%20Name%20Default.png)

<details>

  <summary> Technical Details </summary>
​
<blockquote>

If a ball is already enabled and playing audio when the other ball is enabled, the other ball will jump in sync with the other audio.

Adds 0 - 11 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> Rotation Types </strong> </summary>
​
<blockquote>

Enable this feature to include three toggles to alter the way the balls rotate/face.

| | |
| --- | --- |
| `Head Follow` | Balls rotate in sync with your head. |
| `Head Aim` | Balls will always face away from your head based on its own position. |
| `None` | Ball will stop rotating and preserve its current rotation. |

<details>

  <summary> Technical Details </summary>
​
<blockquote>

Adds 0 - 3 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> Gesture Lock </strong> </summary>
​
<blockquote>

Enable this feature to add a toggle to lock your current SleightlyBall controls without locking your VRChat gestures.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

Adds 0 - 2 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> Avatar Interactions </strong> </summary>
​
<blockquote>

Enable this feature to include three features that interact with other players:

<details>

  <summary>Player Sharing</summary>
​
<blockquote>

Activate to allow others to physbone grab your objects.

This requires others to enable Avatar Interactions with you in VRChat.

See Advanced Options to select a Sharing Mode.

</details>

<details>

  <summary>Player Orbit</summary>
​
<blockquote>

Activate to cause your Throw/Shoot control to orbit the first player it detects within its path.

</details>

<details>

  <summary>Player Constrain</summary>
​
<blockquote>

Activate to locally constrain the ball within range of another player

</details>

<details>

  <summary> Technical Details </summary>
​
<blockquote>

Generates an SB_Renderer object to use as a culling cube.

Adds 0 - 5 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> ToggleHUD </strong> </summary>
​
<blockquote>

Enable this feature to add a HUD to assist with keeping track of your currently toggled options.

This primarily helps with the lack of menu indicators for toggles when optimizing lots of memory.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

See Advanced Options to select an ToggleHUD position.

This option is only available if Disable Memory Optimization is not enabled, and there is memory being optimized.

Adds 0 - 2 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

</details>

</blockquote>

<details>

  <summary> <strong> Advanced Options </strong> </summary>
​
<blockquote>

![SB Advanced Options png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Advanced%20Options.png)

<details>

  <summary> <strong> Write Defaults </strong> </summary>
​
<blockquote>

Enabling/Disabling this option will enable/disable Write Defaults in all generated animator states for SleightlyBall.

![SB Write Defaults png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Write%20Defaults.png)

If it says Write Defaults **(Auto)**, then this is handled automatically to match the current Write Defaults of your Animator Controller(s).

![SB Write Defaults Auto png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Write%20Defaults%20Auto.png)

<details>

  <summary> Technical Details </summary>
​
<blockquote>

If your FX Animator Controller is set to one Write Defaults mode, the **Write Defaults** option will automatically match and be labeled with **(Auto)**.

If your FX Animator Controller has a mix of Write Defaults On and Off, a warning will appear and the **Write Defaults** option will not be labeled with **(Auto)**. This option will be available to manually enable/disable, and the generated states will follow the manually set status.

States with BlendTrees that are also set to Write Defaults On and have `(WD On)` in the name are omitted from the scan.

</details>

</details>

<details>

  <summary> <strong> Remap Control Gestures </strong> </summary>
​
<blockquote>

Enabling this feature will allow for the rearrangement of each **Gesture Control** to map to different gestures. If **Simple Control** is enabled, then the definition of a `Simple` gesture can be redefined here as well.

![SB Gesture Remapping gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Gesture%20Remapping.gif)

<details>

  <summary> Technical Details </summary>
​
<blockquote>

The `Simple?` toggle checkboxes only display if **Simple Control** is enabled.

If FBT Mode is enabled, the respective FBT Mode columns will apply.

FBT Mode Complex refers to combo gesturing with the opposite hand.

If **Remap Control Gestures** is disabled, the Gesture Control mapping and Simple Control definitions will generate according to their default configuration regardless of any changes while it is enabled.

</details>

</details>

<details>

  <summary> <strong> Disable Facial Anims </strong> </summary>
​
<blockquote>

Enable this feature to force your facial expressions to maintain their defaults while a ball mode is enabled, regardless of activated gesture.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

All blendshapes that exist on your Viseme Mesh set in your Avatar Descriptor are animated to the values they were set to at the time of generating SleightlyBall. Blendshapes used on your Viseme Mesh are ignored.

As this only accounts for blendshapes, please be wary of any non-blendshape animation properties that are triggered on gesture (eye movement, tongue toggles, etc.). These can be adjusted during **Anchor Positioning**.

Enabling this feature but not using Viseme Blendshapes mode or having a Viseme Mesh assigned in your Avatar Descriptor will yield an error.

This also affects **Ball Demo** if it is included.

</details>

</details>

<details>

  <summary> <strong> Force Gesture Tracking </strong> </summary>
​
<blockquote>

Enable this feature to force VRC Tracking Control to set fingers to Tracking rather than Animation while a ball mode is enabled. This is only relevant to VR controllers that use finger tracking (ex. Valve Knuckles) on Avatars that use animation overrides on finger tracking.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

This also affects **Ball Demo** if it is included.

</details>

</details>

<details>

  <summary> <strong> Attach To Index Finger </strong> </summary>
​
<blockquote>

By default, the ball hand anchors will be reparented to your wrist bone. Enable this attach to your furthest Index finger bone instead.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

If you do not have Index finger bones mapped, it will end up attached to your wrist bone anyway regardless of this setting.

This setting will locate your furthest bone regardless of it you have all three finger bones mapped in your humanoid rig.

</details>

</details>

<details>

  <summary> <strong> Enable Move Or Copy </strong> </summary>
​
<blockquote>

Enable the ability to Move ball input sources from their respective location in the hierarchy rather than Copy them. This is typically used when trying to maintain specific component references that would otherwise break when instantiated via Copy.

![SB Move Or Copy png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Move%20Or%20Copy.png)

<details>

  <summary> Technical Details </summary>
​
<blockquote>

Balls are set to Copy by default, and will behave as Copy when this option is disabled.

Ball Inputs from the project assets rather than the hierarchy cannot be set to Move and will revert to Copy.

Using the same Ball source for multiple inputs and setting them to Move will yield an error, as you cannot move one object into two locations.

Using the same Ball source for multiple inputs and setting one to Move and the others to copy, will instantiate the copies first during generation, before moving the remaining one.

</details>

</details>

<details>

  <summary> <strong> Include Ball Demo Mode </strong> </summary>
​
<blockquote>

Enable this feature to toggle default Unity Spheres that follow the ball's gesture control. This is often only used for either troubleshooting, demonstration, or practice purposes.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

If **Disable Facial Anims** is enabled, Demo Mode will also disable facial animations.

If **Force Gesture Tracking** is enabled, Demo Mode will also force gesture tracking.

Adds 0 - 1 memory to your expression parameters (See **Memory Calculations** for more details).

</details>

</details>

<details>

  <summary> <strong> Disable Memory Optimization </strong> </summary>
​
<blockquote>

Enable this feature to disable all memory optimization and use a dedicated bool for each toggle. This is primarily an option for those who prefer the default VRChat menu indicators.

</details>

<details>

  <summary> <strong> Separate Balls Per Hand </strong> </summary>
​
<blockquote>

Select whether to configure each hand independently or identically. Enable this to input a ball for each hand rather than have each ball apply to both hands.

![SB Separate Balls per Hand png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Separate%20Balls%20per%20Hand.png)

<details>

  <summary> Technical Details </summary>
​
<blockquote>

This option is only visible if **Ball Configuration** is set to `Both Hands`.

Enabling this option also allows for independent scaling of each hands' balls and colliders during **Anchor Positioning**.

</details>

</details>

<details>

  <summary> <strong> Select Sharing Mode </strong> </summary>
​
<blockquote>

Select which Sharing Mode you'd like to use.

| | |
| --- | --- |
| `Standard` | When Sharing is enabled, immediately world constraint the ball and allow it to be grabbed by others. When it is grabbed and released, it stays where it was released. One toggle per L/R. |
| `Complex` | When Sharing is enabled, allow all of your anchors to be grabbed by others. When it is grabbed and released, it returns to the original anchor position. Rotation is frozen during grab. |

![SB Sharing Mode png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Sharing%20Mode.png)

<details>

  <summary> Technical Details </summary>
​
<blockquote>

In Complex mode, you can use gesture controls to continue to pass the ball between anchors.

This option is only visible if **Avatar Interactions** is enabled.

</details>

</details>

<details>

  <summary> <strong> Select FBT Mode </strong> </summary>
​
<blockquote>

Select which FBT Mode mapping you'd like to use.

|  |  |
| :------------- | :------------------------------ |
| `Standard` | When FBT Mode is enabled, Head/Between controls are replaced with Primary/Secondary Foot control |
| `Complex` | When FBT Mode is enabled, combo gestures act as triggers to allow for entirely alternative gesture control |

![SB FBT Mode png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20FBT%20Mode.png)

<details>

  <summary> Technical Details </summary>
​
<blockquote>

In Complex mode, you use the opposite hand from the ball to hold the trigger gesture which converts your primary hand gestures to new mappings.

Complex Mode only works with one active ball at a time.

This option is only visible if **FBT Mode** is enabled.

</details>

</details>

<details>

  <summary> <strong> Select HUD Position </strong> </summary>
​
<blockquote>

Select which HUD Position you'd like to use.

![SB ToggleHUD Position png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20ToggleHUD%20Position.png)

<details>

  <summary> Technical Details </summary>
​
<blockquote>

This option is only visible if **ToggleHUD** is enabled.

</details>

</details>

<details>

  <summary> <strong> Select Shoot Strength % </strong> </summary>
​
<blockquote>

Set the strength of the forward driver when using Ball Shoot mode.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

This option is only visible if **Shoot Toggle** is enabled.

</details>

</details>

<details>

  <summary> <strong> Select Pilot Speed % </strong> </summary>
​
<blockquote>

Set the speed of the ball when using Pilot Mode.

<details>

  <summary> Technical Details </summary>
​
<blockquote>

Up/Down speeds are halved relative to the speed set for Forward/Backward/Left/Right

This option is only visible if **Pilot Mode** is enabled.

</details>

</details>

</details>

<details>

  <summary> <strong> Saved/Default Parameters </strong> </summary>
​
<blockquote>

Designate which parameters should be saved (*persist between worlds/avatar loads*) and which values they should start with by default on.

Saving some options may increase your required memory.

![SB Saved Default Parameters png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Saved%20Default%20Parameters.png)

</details>

<details>

  <summary> <strong> Save File Path </strong> </summary>
​
<blockquote>

Select where to create the GeneratedSBResources folder which contains all of the generated files.

![SB Save File Path png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Save%20File%20Path.png)

<details>

  <summary> Technical Details </summary>
​
<blockquote>

By default, this path is `Assets/JustSleightly/SleightlyBall`.

Changes made to this path will attempt to be saved to your editor preferences for use in other projects as well.

</details>

</details>

<details>

  <summary> <strong> Begin Setup </strong> </summary>
​
<blockquote>

Clicking this button will begin the generation of the SleightlyBall system according to the configuration of the **Main Settings** window, and proceed to **Anchor Positioning**. This button will be greyed out if there are any red errors returned in the Inspector.

![SB Begin Setup png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Begin%20Setup.png)

</details>

<details>

  <summary> <strong> Utilities </strong> </summary>
​
<blockquote>

<details>

  <summary> <strong> Memory Calculations </strong> </summary>
​
<blockquote>

Displays the Required Memory to generate, the Available Memory on the current Avatar's Expression Parameters, and the Optimized Memory that will be saved with the current configuration.

![SB Calculate Memory png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Calculate%20Memory.png)

<details>

  <summary> Necessary Memory can be calculated as: </summary>
  ​
<blockquote>

```math
TotalRequiredMemory = LocalSyncedMemory + NetworkSyncedMemory + CustomBallMemory
```

where:

```math
LocalSyncedMemory =\begin{cases}LocalBools & LocalBools <8\\8 & LocalBools  \geq  8\end{cases} 
```

```math
LocalBools = \Sigma EnabledLocalBools
```

```math
\Sigma EnabledLocalBools =\begin{cases}2 * Ball Count & BothHands\\1 * Ball Count & LeftHandedOnly\\1 * Ball Count & RightHandedOnly\\5 & WorldConstraints\\2 & WorldConstraints\&FBTMode\\3 & WorldPhysics\\1 & SimpleControl\&(!SaveControlMode)\\1 & ShootToggle\&(!SaveThrowShootMode)\\1 & FBTMode\&(!SaveFBTMode)\\1 & HideOnIdle\&(!SaveHideOnIdle)\\3 & BallAudio\&(!SaveAudioMode)\\1 + AudioCount & BallAudio\&(AudioCount > 1)\\3 & RotationTypes\&(!SaveRotationType)\\1 * HandCount & GestureLock\\1 & AvatarInteractions\&(!SavePlayerOrbit)\\1 * HandCount & AvatarInteractions\\2 & AvatarInteractions\&(SharingMode==Standard)\\1 & AvatarInteractions\&(SharingMode==Complex)\\1 & ToggleHUD\&(!SaveToggleHUD)\\1 & BallDemoMode\end{cases}
```

and:

```math
NetworkSyncedMemory = \Sigma EnabledSyncedMemory
```

```math
\Sigma EnabledLocalBools =\begin{cases}8 & BallDistance\\8 & BallStrength\\1 & SimpleControl\&SaveControlMode\\1 & ShootToggle\&SaveThrowShootMode\\1 & FBTMode\&SaveFBTMode\\16 & PilotMode\\2 & PilotMode\&BothHands\\1 & PilotMode\&LeftHandedOnly\\1 & PilotMode\&RightHandedOnly\\1 & HideOnIdle\&SaveHideOnIdle\\3 & BallAudio\&SaveAudioMode\\3 & RotationTypes\&SaveRotationType\\1 & AvatarInteractions\&SavePlayerOrbit\\1 & ToggleHUD\\1 & ToggleHUD\&SaveToggleHUD\end{cases}
```

</details>

</details>

<details>

  <summary> <strong> Warnings/Errors </strong> </summary>
​
<blockquote>

<details>

  <summary> <strong> ERROR: No Avatar Descriptor Detected </strong> </summary>
​
<blockquote>

Triggers if no Avatar Descriptor component can be detected in any parents of the current GameObject.

</details>

<details>

  <summary> <strong> ERROR: No Animator Detected </strong> </summary>
​
<blockquote>

Triggers if no Animator component is found on the Avatar Descriptor GameObject.

</details>

<details>

  <summary> <strong> ERROR: An Error Has Occurred And Interrupted The Installation </strong> </summary>
​
<blockquote>

Triggers for various reason, likely due to going in/out of Play Mode, or sometimes Unity recompiling due to a change in project files via import/deletion.

</details>

<details>

  <summary> <strong> ERROR: Previous SleightlyBall Installation Detected </strong> </summary>
​
<blockquote>

Triggers if a remnants of a previous SleightlyBall installation were detected. Please remove it from the Avatar to proceed using **Remove from Avatar**.

</details>

<details>

  <summary> <strong> ERROR: Not Enough Memory </strong> </summary>
​
<blockquote>

Triggers if the Expressions Menu does not have enough available memory to satisfy the features configured in **Main Settings**.

</details>

<details>

  <summary> <strong> ERROR: Not Enough Menu Space </strong> </summary>
​
<blockquote>

Triggers if the Expressions Menu in the Avatar Descriptor already has 8 controls.

</details>

<details>

  <summary> <strong> ERROR: Animator Missing Avatar </strong> </summary>
​
<blockquote>

Triggers if the Animator component on your Avatar Root does not have an Avatar mapped.

![SB Error Animator No Avatar Example png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Error%20Animator%20No%20Avatar%20Example.png)

</details>

<details>

  <summary> <strong> ERROR: Model Not Humanoid </strong> </summary>
​
<blockquote>

Triggers if the model's FBX is not set to Humanoid rig configuration.

</details>

<details>

  <summary> <strong> ERROR: Chest Not Mapped </strong> </summary>
​
<blockquote>

Triggers if the model's humanoid rig configuration does not have the chest mapped.

</details>

<details>

  <summary> <strong> ERROR: Viseme Mesh Not Detected </strong> </summary>
​
<blockquote>

Triggers if no Viseme Mesh is detected on the Avatar Descriptor or if the Viseme Mode is not set to Blendshape, while **Disable Facial Anims** is enabled.

</details>

<details>

  <summary> <strong> ERROR: Duplicate Ball Inputs Set To Move </strong> </summary>
​
<blockquote>

Triggers if multiple Ball Inputs have the same source GameObject, **Move Or Copy** is enabled, and those inputs are set to Move. The same GameObject cannot be moved to multiple locations at once.

</details>

<details>

  <summary> <strong> ERROR: Duplicate Audio Names </strong> </summary>
​
<blockquote>

Triggers if multiple Audios have duplicate names. Each audio requires a unique name.

</details>

<details>

  <summary> <strong> WARNING: Avatar Not At Origin </strong> </summary>
​
<blockquote>

Triggers if the Avatar is currently not at origin (0,0,0 Position and Rotation). If continued, the SleightlyBall system may spazz out for remote players.

</details>

<details>

  <summary> <strong> WARNING: Mixed Write Defaults </strong> </summary>
​
<blockquote>

Triggers if both Write Defaults On and Off are detected in your FX Controller.

Continuing will use whichever value of **Write Defaults** you set under **Advanced Options**.

</details>

<details>

  <summary> <strong> WARNING: The following ball inputs contain constraints </strong> </summary>
​
<blockquote>

Triggers if any ball inputs contain constraint components. These may or may not function properly depending on if they were intended for use with SleightlyBall or not.

</details>

<details>

  <summary> <strong> WARNING: Default Controllers/Expressions Detected </strong> </summary>
​
<blockquote>

Triggers if the FX Controller, Expression Parameters, or Expressions Menu in your Avatar Descriptor is either default or empty.

</details>

<details>

  <summary> <strong> WARNING: Empty Ball Inputs </strong> </summary>
​
<blockquote>

Triggers if any Ball Input fields are left blank. Balls can be added after the hierarchy is generated, but you will not be able to take advantage of any of the positioning/scaling tools.

Press OK to acknowledge this warning and stop disabling the Begin Setup button. If there are any other errors, they will still disable the Begin Setup button.

</details>

<details>

  <summary> <strong> WARNING: Empty Audio Inputs </strong> </summary>
​
<blockquote>

Triggers if any Audio Input fields are left blank. Audios can be added after the hierarchy is generated.

Press OK to acknowledge this warning and stop disabling the Begin Setup button. If there are any other errors, they will still disable the Begin Setup button.

</details>

<details>

  <summary> <strong> ERROR: Found an audio clip with load type 'Decompress On Load' </strong> </summary>
​
<blockquote>

Triggers if any audio clips with load type 'Decompress On Load' don't have 'Load In Background' enabled. This is a VRCSDK error that will prevent upload of the Avatar until it is resolved

Press `Fix Audio Clips` to enabled 'Load In Background' for those clips automatically.

</details>

<details>

  <summary> <strong> ERROR: Double Layer Rig Bug Detected </strong> </summary>
​
<blockquote>

Triggers if your Avatar Descriptor has two FX Playable Layers. Pressing Fix will restore the Action Playable Layer for you, but you will need to re-populate any custom layers you had previously set here.

This is a [known VRCSDK bug](https://notes.sleightly.dev/My-VRC-Avatar-Descriptor-is-not-showing-the-Playable-Layers-properly-Double-FX-Bug-e6a68eca97644ec3896d3bda410cd97e) that occurs when switching the avatar in the root animator or switching the FBX of that avatar between Generic and Humanoid rigs when it already has an Avatar Descriptor in the scene.

![SB Double FC Layer Bug Example png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Double%20FX%20Layer%20Bug%20Example.png)

</details>

</details>

<details>

  <summary> <strong> Remove From Avatar </strong> </summary>
​
<blockquote>

Removes any trace of SleightlyBall out of the avatar's hierarchy and Avatar Descriptor.

![SB Delete Button png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Delete%20Button.png)

<details>

  <summary> <strong> Technical Details </strong> </summary>
​
<blockquote>

Deletes Hierarchy: Any GameObjects with the Prefix "SB".

Deletes Controller Layers: Any Layers with the SB Identifier on the AnyState.

Deletes Controller Parameters: Any Parameters with the Prefix "SB/".

Deletes From Expressions Menu: Any SubMenu whose name contains "SleightlyBall" or leads to a SubMenu with the Prefix "SB".

Deletes From Expression Parameters: Any Parameters with the Prefix "SB".

<blockquote>

</details>

</details>

<details>

  <summary> <strong> Delete from Project </strong> </summary>
​
<blockquote>

Deletes the Generated Resources folder at path `Save File Path/GeneratedSBResources`. This may contain files for more than just the current avatar if you have generated SleightlyBall multiple times in this project.

![SB Delete Button png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Delete%20Button.png)

</details>

<details>

  <summary> <strong> Authorized user </strong> </summary>
​
<blockquote>

Dynamically displays the current Authorized User's discord name and license type. Just a little extra personal touch!

![SB Authorized User png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Authorized%20User.png)

</details>

<details>

  <summary> <strong> Check For Update </strong> </summary>
​
<blockquote>

Click the three lines next to the version number in the bottom left to check for newer versions of SleightlyBall. If a new version is detected, a pop-up window will point you to the changelog.

This will automatically check the first time it is loaded per day.

</details>

<details>

  <summary> <strong> Send Feedback </strong> </summary>
​
<blockquote>

Click the three lines next to the version number in the bottom left to send feedback for SleightlyBall straight from Unity.

</details>

<details>

  <summary> <strong> Verify </strong> </summary>
​
<blockquote>

Click the three lines next to the version number in the bottom left to select when SleightlyBall verifies authentication.

On Display initiates authentication when the window is opened.

On Project Load initiates authentication when the project is opened.

</details>

</details>

### Anchor Positioning

<details>

  <summary> <strong> Edit Anchors </strong> </summary>
​
<blockquote>

<details>

  <summary> <strong> Edit Hand Anchors </strong> </summary>
​
<blockquote>

Adjust the labeled BallRoot anchors in the scene view to each index fingertip using the positioning handles.

If necessary, rotate the anchors so that the large arrow is parallel to your fingers, away from your body.

There is an option to enable/disable moving the Hand Anchors symmetrically in World Space.

![SB Edit Hand Anchors gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Edit%20Hand%20Anchors.gif)

</details>

<details>

  <summary> <strong> Edit Head Anchor </strong> </summary>
​
<blockquote>

Adjust the labeled BallRoot.Head anchor in the scene view to about an arm's length in front of your head using the positioning handle.

If necessary, rotate the anchor so that the large arrow is parallel to your forward view, away from your body.

![SB Edit Head Anchor gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Edit%20Head%20Anchor.gif)

</details>

<details>

  <summary> <strong> Edit Foot Anchors </strong> </summary>
​
<blockquote>

Adjust the labeled BallRoot anchors in the scene view to above each foot/ankle using the positioning handles.

If necessary, rotate the anchors so that the large arrow is parallel to your leg, away from your body straight downwards.

There is an option to enable/disable moving the Foot Anchors symmetrically in World Space.

This option is only visible if **FBT Mode** is enabled.

![SB Edit Foot Anchors gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Edit%20Foot%20Anchors.gif)

</details>

</details>

<details>

  <summary> <strong> Edit Orbit Radius </strong> </summary>
​
<blockquote>

<details>

  <summary> <strong> Edit Chest Orbit Radius </strong> </summary>
​
<blockquote>

Adjust the Chest Orbit Radius in the scene view to the desired size using the radius handle.

This will be the spherical limit the ball orbits along when using the Ball Orbit gesture.

This is typically a bit bigger than your armspan.

![SB Edit Chest Orbit Radius gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Edit%20Chest%20Orbit%20Radius.gif)

</details>

<details>

  <summary> <strong> Edit Feet Orbit Radius </strong> </summary>
​
<blockquote>

Adjust the Foot Orbit Radius in the scene view to the desired size using the radius handle.

This will be the spherical limit the ball orbits along when using the Ball Orbit gesture in FBT Complex Mode.

This is typically up to your knee.

This option is only visible if **FBT Mode** is enabled and set to Complex Mode.

![SB Edit Feet Orbit Radius gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Edit%20Feet%20Orbit%20Radius.gif)

</details>

</details>

<details>

  <summary> <strong> Edit Ball Size</strong> </summary>
​
<blockquote>

Adjust the labeled Ball Sizes in the scene view using the scale handles or the field below.

Alternatively, you can also multi-select balls to scale multiple balls at once.

If you're using Unity 2019, using the center scale handle when the scale is not (1, 1, 1) will exponentially snap initially due to a [Unity 2019 bug](https://forum.unity.com/threads/case-1264038-handles-scalehandle-incorrect-when-center-scaling.933798/), but it can still be used to uniformly scale across all axes.

![SB Edit Ball Size gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Edit%20Ball%20Size.gif)

</details>

<details>

  <summary> <strong> Edit Physics Collider Size </strong> </summary>
​
<blockquote>

Adjust the labeled Ball Collider Sizes in the scene view using the scale handles or the field below.

Alternatively, you can also multi-select balls to scale multiple balls at once.

![SB Edit Collider Size gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Edit%20Collider%20Size.gif)

</details>

<details>

  <summary> <strong> Show/Hide Handles </strong> </summary>
​
<blockquote>

Toggle these options to help manage the clutter in the scene while editing the above steps.

This option is only visible while editing the above steps.

![SB Show Hide Handles gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Show%20Hide%20Handles.gif)

</details>

<details>

  <summary> <strong> Edit Disabled Facial Expressions </strong> </summary>
​
<blockquote>

Deselect any blendshapes that should not be reset to their default values while using the SleightlyBall system, such as body blendshapes.

Additional GameObjects that should be enabled/disabled during facial expressions (such as separate mesh lollipops/tongues/other accessories) can be added at the bottom.

![SB Edit Disabled Facial Expressions gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20Edit%20Disabled%20Facial%20Expressions.gif)

</details>

<details>

  <summary> <strong> Complete Setup </strong> </summary>
​
<blockquote>

Once **Anchor Positioning** is finished, click **Complete Setup** to generate all the required animations and finalize the system and 3.0.

</details>

---

# Usage

### In-Game Usage Tutorial Video

[![SleightlyBall In-Game Usage Tutorial](http://img.youtube.com/vi/XQh3cU5Ttt0/0.jpg)](https://youtu.be/XQh3cU5Ttt0 "SleightlyBall In-Game Usage Tutorial")

For information regarding menu options, please see **Additional Features** under **Main Settings** above.

<details>

  <summary> <strong> Gesture Mapping </strong> </summary>
​
<blockquote>

By default, the gesture control mapping is as follows:

| Hand Gesture Layout | Simple? | Ball Control Mapping| FBT Mode Standard | FBT Mode Complex |
| :------------- | :-------------: | :------------- | :------------- | :------------- |
| `F1 Gesture Idle` | :white_square_button: | Idle | | |
| `F2 Gesture Fist` | :white_square_button: | Head Control | Primary Foot | Primary Trigger* |
| `F3 Gesture Open Hand` | :white_check_mark: | Chest Orbit | | |
| `F4 Gesture Fingerpoint` | :white_check_mark: | Primary Hand Control | | |
| `F5 Gesture Victory` | :white_check_mark: | Release Ball | | |
| `F6 Gesture Rock n Roll` | :white_square_button: | Rigid Return | | |
| `F7 Gesture Handgun` | :white_check_mark: | Secondary Hand Control | | |
| `F8 Gesture Thumbs Up` | :white_square_button: | Between Hand Control | Secondary Foot | Secondary Trigger* |

\* Gesture in opposite hand to switch gesture set of main hand during FBT Mode Complex.

This mapping can be reconfigured under **Advanced Settings** using **Remap Control Gestures**

</details>

<details>

  <summary> <strong> Control Functions </strong> </summary>
​
<blockquote>

| Ball Control | Function |
| :------------- | :------------- |
| `Idle` | No function - Preserves the last used control. |
| `Head Control` | Attracts the ball to the anchor controlled by your head. |
| `Chest Orbit` | Releases the ball and sets a firm limiter at a radius centered around your chest. |
| `Primary Hand Control` | Attracts the ball to the anchor controlled by your primary hand. |
| `Release Ball` | Release the ball from its current position and maintain momentum. / `Shoot Toggle` Shoot the ball in the direction your primary hand is pointing. |
| `Rigid Return` | Quickly recall the ball back to its primary hand anchor. |
| `Secondary Hand Control` | Attracts the ball to the anchor controlled by your secondary hand. |
| `Between Hand Control` | Attracts the ball to halfway point between your primary and secondary hand anchors. |
| `Primary Foot Control` | `FBT Simple` Attracts the ball to the anchor controlled by your primary foot. |
| `Secondary Foot Control` | `FBT Simple` Attracts the ball to the anchor controlled by your secondary foot. |
| `Primary Trigger` | `FBT Complex` Holding this trigger in your opposite hand converts your primary hand gesture set into a primary foot centered one. |
| `Secondary Trigger` | `FBT Complex` Holding this trigger in your opposite hand converts your primary hand gesture set into a secondary foot centered one. |

</details>

---

# Designing a Custom Ball for SleightlyBall

SleightlyBall is designed to work with the majority of GameObjects, as it generates its own physics collision system independent of the ball inputs you use.

With that said, below are a few notes you may want to take into account when building your own ball, whether for yourself or to distribute to others.

<details>

  <summary> <strong> Structure of a Spring Joint Ball </strong> </summary>
​
<blockquote>

When designing a spring joint ball for use with SleightlyBall, below are a few elements you may want to consider for a well-rounded feature set:

1. Spawn Effects - Features that activate only when enabling the ball
2. Idle Effects - Features that are always on and persist
3. Trailing Effects - Features that may be always on but are heavily accentuated by movement
4. Impact Effects - Features that activate upon impact with world collision
5. Post-Impact Effects - Features that leave residual effects at collision points after impact such as decals

Options 4 and 5 above can be tricky to set up without advanced Unity experience, as often times you'll be mixing particle collision with SleightlyBall's physics based collision. I personally use stop-action particle sub-animators to resolve the collision trigger spam.

</details>

<details>

  <summary> <strong> Usable Components </strong> </summary>
​
<blockquote>

The SleightlyBall system handles the physics/movement of the ball inputs on its own, so the system is designed to work with most objects as long as they are largely static and unmoving on their own (such as the default Unity sphere).

As such, there are a few components to be careful of when creating your custom ball.

- Rigidbodies and Joints (Spring/Configurable) are automatically removed during installation
- Unity Colliders (Sphere/Box/Capsule/Mesh) are automatically removed during installation **if they are not set to IsTrigger**
- Constraint components are **NOT** removed but may cause unintended behaviour **in some cases** such as
  - Constraints that reference objects outside the ball or SleightlyBall system
  - Constraints that are self-referenced for damping/spring behaviour and cause non-static movement
- Avatar Descriptors on the ball root object are automatically removed during installation due to the [Animator Pseudo API](https://github.com/JustSleightly/SleightlyBall#animator-pseudo-api)
  - Pipeline Managers are also removed from the ball root if an Avatar Descriptor is detected
  - Animator components are also removed from the ball root if an Avatar Descriptor is detected

</details>

## Animator Pseudo API

For those who want to integrate custom animation systems on their ball without losing the functionality of SleightlyBall, this pseudo API provides additional tools to advanced Unity creators to facilitate the process!

![SB API Highlight gif](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Gifs/SB%20API%20Highlight.gif)
![SB Info API png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20Info%20API.png)

To enable this functionality on your own custom ball, **create an empty GameObject as a new parent/root** to your custom ball and add a `VRCAvatarDescriptor`. SleightlyBall will automatically detect ball inputs with Avatar Descriptors and highlight green.

<details>

  <summary> <strong> Automatic 3.0 Merging </strong> </summary>
​
<blockquote>

SleightlyBall will automatically merge in the FX Controller, Expressions Menu, and Expression Parameters from the Avatar Descriptor of the custom ball. There is no particular naming convention you need to follow, except when using **Aliased Gesture/Dynamics Parameters** *(see below)*.

All parameters across all three files will be prefixed with `SB/` and the ball's index, such as `L1` for Left 1, to avoid conflicts between multiple custom balls in the same system. Native VRChat parameters and the VRLabs IsMirror parameter are ignored.

All animation clips and expressions menu (and submenus) will be duplicated so that they are modified non-destructively.

All animation clips will be repathed with their respective location in the SleightlyBall hierarchy as the new root. Your ball animations should be created with the `VRCAvatarDescriptor` as the root in order to be repathed correctly.

![SB API Path png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20API%20Path.png)

Please be mindful of expression parameter memory usage, as end users most often install balls to both hands rather than just one. See **Individual vs Shared Control** below.

</details>

<details>

  <summary> <strong> Automatic Target Reparenting </strong> </summary>
​
<blockquote>

SleightlyBall will automatically reparent certain GameObjects underneath the custom ball's Avatar Descriptor to various parts of the SleightlyBall system, in case you need to use those targets for your own internal logic.

Only GameObjects that are **direct children** to the Avatar Descriptor will be scanned.

![SB API Reparent png](https://github.com/JustSleightly/SleightlyBall/raw/main/Documentation/Images/SB%20API%20Reparent.png)

GameObjects must start with one of the below naming conventions in order to be reparented:

| Joint | Constraint Targets | Body Targets |
| :------------- | :------------- | :------------- |
| `SB_Joint` | `SB_PrimaryHandJoint` | `SB_PrimaryHand` |
|  | `SB_SecondaryHandJoint` | `SB_SecondaryHand` |
|  | `SB_ChestJoint` | `SB_Chest` |
|  | `SB_HeadJoint` | `SB_Head` |
|  | `SB_PrimaryFootJoint` | `SB_PrimaryFoot` |
|  | `SB_SecondaryFootJoint` | `SB_SecondaryFoot` |

The **Joint** target `SB_Joint` represents the position the ball is attracted to, and automatically moves around to the relevant gesture control target as necessary. This option suffices for most applications.

The **Constraint Targets** represent each individual position the ball is attracted to when performing gesture controls, in the event precise control is desired as opposed to the previous `SB_Joint` when developing logic. Unlike the previous option, these targets ignore Simple Sharing, as they are used for both Left/Right sets of balls, while Simple Sharing is on a Left/Right basis.

The **Body Targets** represent each individual position the previous **Constraint Targets** follow around the user's body. Unlike the previous two options, these targets continue to follow the body and ignore SleightlyBall's other features that manipulate the ball's position, including Ball Distance, World Constraints, and Simple Sharing.

Since Primary/Secondary Foot are only available when FBT Mode is enabled in the installer by the end user, it is highly recommended to multi-condition your logic with the `SB/FBT Mode` bool parameter or use **Aliased Gesture Parameters** to prevent unintended behaviour.

These targets are not intended to be used for animation clips themselves, but rather as component sources such as for constraints.

Each reparented GameObject will have its name modified to include the index of the ball it's associated with.

</details>

<details>

  <summary> <strong> Aliased Gesture Parameters </strong> </summary>
​
<blockquote>

SleightlyBall offers two aliased parameters you can use in your custom ball's FX controller in place of VRChat's native GestureLeft/GestureRight parameters.

By using these parameters in your FX controller instead of VRChat's, you can accommodate for end users who remap their SleightlyBall gesture controls to different gestures using the installer. These should **only** be added to your controller and not to your Expression Parameters.

`SB/Hidden` is a bool that is **true** when the ball is currently hidden by gesture via the **HideOnIdle** feature.

`SB/Gesture` is an integer with values ranging from 0 to 15 and corresponds to each of the possible SleightlyBall gesture controls.

SleightlyBall will automatically change `SB/Hidden` and `SB/Gesture` to `SB/HiddenLeft`/`SB/HiddenRight` and `SB/GestureLeft`/`SB/GestureRight` according to the mode the ball is installed to by the end user. You can also directly use the Left/Right variants if you need specific hand conditions.

It is recommended to multi-condition all of your transitions using `SB/Gesture` with `SB/Hidden = false` so that they only activate while the ball is visible.

*`SB/Gesture` is not properly supported with Shared Control (see below) and will default to SB/GestureLeft. Avoid using `SB/Gesture` on balls intended for Shared Control or inform your users accordingly.*

| Int Value | Gesture Control | Feature Requirement |
| :-------------: | :------------- | :------------- |
| 0 | `Primary Hand Control` |  |
| 1 | `Secondary Hand Control` |  |
| 2 | `Head Control` |  |
| 3 | `Chest Orbit` |  |
| 4 | `Chest Constraint Control` | World Constraint |
| 5 | `Release Ball` |  |
| 6 | `Shoot Ball` | Shoot Toggle |
| 7 | `Rigid Return` |  |
| 8 | `Between Hand Control` |  |
| 9 | `Primary Foot Control` | FBT Mode |
| 10 | `Secondary Foot Control` | FBT Mode |
| 11 | `Primary Foot Orbit` | FBT Mode: Complex |
| 12 | `Secondary Foot Orbit` | FBT Mode: Complex |
| 13 | `Primary Foot Rigid Return` | FBT Mode: Complex |
| 14 | `Secondary Foot Rigid Return` | FBT Mode: Complex |
| 15 | `Between Feet Control` | FBT Mode: Complex |

</details>

<details>

  <summary> <strong> Aliased Dynamics Parameters </strong> </summary>
​
<blockquote>

SleightlyBall offers `SB/AD/` as a parameter prefix that you can use in your custom ball's Avatar Dynamics components, FX controller, and Expression Parameters.

By using this prefix in your parameters, you can accommodate for PhysBones or Contact Receivers per custom ball to avoid conflicts between multiple custom balls in the same system.

SleightlyBall will automatically change `SB/AD/` according to the mode the ball is installed to by the end user, such as `SB/L1/` for Left 1.

*Avoid having Aliased Dynamics Parameters and regular parameters named identically with or without the prefix, as regular parameters will also be prefixed with `SB/` and their respective index. Example: `SB/AD/Test` and `Test` will both end up being `SB/L1/Test`.*

*`SB/AB/` is not properly supported with Shared Control (see below). Avoid using `SB/AB/` on balls intended for Shared Control or inform your users accordingly.*

</details>

<details>

  <summary> <strong> Individual vs Shared Control </strong> </summary>
​
<blockquote>

SleightlyBall offers a variety of ball configurations, including Left/Right/Both Hand configurations as well as **Separate Balls per Hand**.

By default, SleightlyBall will merge all custom ball animation systems on an individual per-ball basis. In both hand configurations, this means the left and right hand ball will each have their own independent custom animation system that you can control individually.

If you have the **Ball Configuration** set to *Both Hands* and **Separate Balls per Hand** is *disabled*, an option to select between `Individual Control` vs `Shared Control` appears. Selecting `Shared Control` will cause SleightlyBall to merge that ball's custom animation system in to affect both the left and right hand at the same time, and halving Expression Parameter memory used.

Please note that these options are all-or-nothing for the entire animation system, and SleightlyBall does not support setting individual/shared control on a per-layer/parameter basis.

It is recommended to add to your custom ball instructions/description whether or not your custom ball is compatible with `Shared Control`.

</details>

*If you have any questions about this API, or would like to develop for this API but don't own SleightlyBall, feel free to reach out to me!*

---

# Frequently Asked Questions

<details>

  <summary> <strong> Is SleightlyBall compatible with VRChat Quest Avatars? </strong> </summary>
​
<blockquote>

**No**, as [VRChat Quest Avatars](https://docs.vrchat.com/docs/quest-content-limitations) do not support Physics Objects (Rigidbodies, Joints, Colliders) nor Constraints at this time. Other spring joint ball systems shouldn't be compatible either.

</details>

<details>

  <summary> <strong> Is SleightlyBall compatible with Optimized Avatars? </strong> </summary>
​
<blockquote>

**Depends**. The most limiting restrictions are easily the RigidBodies, Colliders, and Audio Sources. It is possible to pull your Avatar down to at least [Medium/Poor](https://docs.vrchat.com/docs/avatar-performance-ranking-system). Below is a table describing all the stat-influencing components that are generated according to what options you enable. Any other stat reductions are dependent on what balls you choose to use alongside this system.

| Options | Components |
| --- | --- |
| `Base` | 1 Rigidbody + 2 Rigidbodies per Hand |
| `World Physics` | 2 Sphere Colliders per Hand |
| `Shoot Toggle` | 1 Rigidbody per Hand |
| `Pilot Mode` | 1 Rigidbody per Hand |
| `Ball Audio` | 1 - 8 Audio Sources per Hand |
| `Avatar Interactions : Sharing Standard` | 1 PhysBone per Hand + 6 Contact Receivers per Hand |
| `Avatar Interactions : Sharing Complex` | 4 PhysBones (+ 2 PhysBones if FBT Mode) + 6 Contact Receivers per Hand |
| `Avatar Interactions OR ToggleHUD` | 1 Skinned Mesh Renderer + 1 Material Slot (+1 Material if ToggleHUD) |
| `Demo Mode` | 1 Mesh Renderer per Hand + 1 Material Slot per Hand + 1 Material per Hand |

</details>

<details>

  <summary> <strong> Why can't other players see my SleightlyBall system in game / Why is it spazzing out?</strong> </summary>
​
<blockquote>

Make sure your Avatar is uploaded at world origin (0,0,0 Position and Rotation)!

</details>

<details>

  <summary> <strong> Why does the ball jitter when I move during Player Sharing?</strong> </summary>
​
<blockquote>

This is local only, and other players will not see this. Unfortunately this is a limitation of VRChat and how PhysBones work.

</details>

<details>

  <summary> <strong> None of my toggles work anymore! HELP?</strong> </summary>
​
<blockquote>

If you are using the original version of SleightlyBall, if you have included World Physics, this may occur if you rearrange the layers in your Gesture Playable Layer of your Avatar Descriptor. If these layers' order is shifted, you must run **VRLabs' [Layer Weight Tool](https://github.com/VRLabs/Layer-Weight-Tool)** to resolve the sub-animator. Alternatively, you can re-generate the **SleightlyBall** system, or better yet, **update SleightlyBall**.

</details>

<details>

  <summary> <strong> Can I edit/swap the balls after I generate SleightlyBall? </strong> </summary>
​
<blockquote>

**Yes**, expand the SB_SleightlyBall hierarchy until you reach the Left/Right Ball Modes. You can replace any child to the Ball Mode objects, just remember to leave those child objects enabled, as your animations toggle the Ball Modes on/off. You should also remove any pre-existing spring/configurable joints, rigidbodies, or sphere/box/capsule/mesh colliders on your balls that would usually be auto-removed by the SleightlyBall installer.

</details>

<details>

  <summary> <strong> How do I fix Disable Facial Anims to also disable non-blendshapes (Tongues/Eyes)? </strong> </summary>
​
<blockquote>

Navigate through your project files to your Avatar's GeneratedSBResources folder and locate the animation clip for *Disable Facial Animations* in the Animations folder. You can add extra properties to this clip to account for resetting your non-blendshape animations. This is usually handled during the **Anchor Positioning** step of the installer.

</details>

<details>

  <summary> <strong> How do I fly up/down in Pilot Mode? How do I reset the ball after using Pilot Mode? </strong> </summary>
​
<blockquote>

If you do a **Thumbs Up gesture** in either hand while the puppet menu is open, the axes swap to XY controls, replacing Forward and Backward with Up and Down.

Closing the puppet menu will have the ball maintain its position in world space, until you activate your **Rigid Return gesture** while the menu is closed.

</details>

<details>

  <summary> <strong> How do I export SleightlyBall with my commercial package? </strong> </summary>
​
<blockquote>

Assuming you have a **commercial license** for SleightlyBall, the script generates everything from scratch, making it easy to export without worrying about conflicting with other packages.

You can find these generated resources at `Save File Path/GeneratedSBResources/`. By default, this is `Assets/JustSleightly/SleightlyBall/GeneratedSBResources/`.

The folder with your avatar's SleightlyBall under Generated Resources is the only one you need to export, aside from the files of the actual balls you used with the tool. The only exception to this is if you did not have an FX controller, Gesture controller, Expression Parameters, or Expressions Menu by default, in which those will be generated in your `Assets/` folder.

**You may not** export or redistribute the *SleightlyBall.dll* file and other contents under `Packages/JS - SleightlyBall/`. Please refer to the full Terms and Conditions on my [store](https://store.sleightly.dev/).

</details>

<details>

  <summary> <strong> Why is my project crashing after importing SleightlyBall? </strong> </summary>
​
<blockquote>

Remove SleightlyBall via Windows File Explorer and check your project to see if it currently contains Cinemachine. You can locate this by clicking on `Window > Package Manager` from the top toolbar, and browsing the packages currently in your project. If Cinemachine is added, remove it. It is sometimes added through the VRChat Worlds SDK, so you may need to remove any remnants of the Worlds SDK from your project and this package manager window before removing Cinemachine.

</details>

<details>

  <summary> <strong> Can I change the computer my license is registered to? </strong> </summary>
​
<blockquote>

**Yes**, in the event you change hardware, you can use the **Transfer License** option when trying to verify your license key in Unity on the new hardware. There is a cooldown period to prevent abuse, and these logs will be monitored for misuse. If you need to re-transfer sooner than this transfer period, open a support ticket on [discord](https://discord.sleightly.dev/).

</details>

<details>

  <summary> <strong> Can I upgrade my personal license? </strong> </summary>
​
<blockquote>

**Yes**, open a support ticket on [discord](https://discord.sleightly.dev/) and we can get that process started for you.

</details>

<details>

  <summary> <strong> My license key isn't working! </strong> </summary>
​
<blockquote>

Open a support ticket on [discord](https://discord.sleightly.dev/) or check the SleightlyBall support channel for known issues if you are a validated customer.

</details>

<details>

  <summary> <strong> Where do I report a bug? </strong> </summary>
​
<blockquote>

You can add issues to this github repository, or post it in the support channel for SleightlyBall on [discord](https://discord.sleightly.dev/).

</details>

<details>

  <summary> <strong> Where can I request features/make suggestions? </strong> </summary>
​
<blockquote>

Feel free to leave these in the support channel on [discord](https://discord.sleightly.dev/) and we can discuss them in more detail.

</details>

<details>

  <summary> <strong> I need more help! </strong> </summary>
​
<blockquote>

If you need help with using SleightlyBall, reach out in the designated support channel on [discord](https://discord.sleightly.dev/) so me or a community member can help. If you have private issues involving purchase details, open up a support ticket instead.

</details>

---

## Special Thanks

To my early alpha customers/testers for waiting up to nearly a year for this release - LeBUBBLES/ksivl/mango/KeepItBlank/Zen/Squirtles/PrimeSlav/Ember/Ronin/IMPACT/Once

**[PF_Cactus](https://discord.gg/FJKB768)** - For the original inspiration of making a custom inspector multi-step setup script with his original drone

**[Joshuarox100](https://github.com/Joshuarox100)** - Whose logic in [Inventory Inventor](https://github.com/Joshuarox100/VRC-Inventory-Inventor) is directly used for the memory optimization in this system

**[Lin](https://github.com/oofdesu)** - Who coincidentally released [World Physics](https://github.com/VRLabs/VRChat-Avatars-3.0#world-physics) while I was tackling getting this system to have collision in Nov 2020

**[hfcRed](https://github.com/hfcRed)** - For support with the Avatar Interaction aspects regarding player sharing

and **especially [Dreadrith](https://github.com/Dreadrith/DreadScripts)** - For basically helping me learn C# for Unity/VRC and directly implementing the licensing system on the script
