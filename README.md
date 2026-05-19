Credits

Main Developer: P373R
Side Developer: SGEO
Quality Of Life Dev: Bloom Peters
Winxtropia Viewer VR: Bloom Peters — Winxtropia Grid

Presenting the Winxtropia Viewer VR — the project has finally reached a stable enough state to deliver a usable VR setup experience, but there are still several major goals that must be achieved in the next update.

What Changed?
1. Native VR Feed Rendering

The VR feed is no longer rendered the old way. The image is now significantly clearer and more native to the headset itself, resulting in a sharper and more immersive experience.

2. New Debug Options

Added several debug tools, including RegionBlocker (enabled by default).

This feature prevents surrounding regions from rendering and only draws the region you are currently inside. For VR, this dramatically improves performance — often resulting in overall FPS boosts of around 50%.

3. Adjustable VR Render Scale

You can now reduce the VR render scale below 1.0 for lower-end systems and weaker GPUs, allowing better performance tuning for a wider range of hardware.

4. VR Privacy Filter

When entering VR mode, the viewer now automatically enables a privacy filter that hides the world while keeping the UI visible.

This will become toggleable in the next update.

5. Proper Aspect Ratio Restoration

Previously, entering VR mode permanently changed the viewer’s aspect ratio and zoom settings.

Now, when entering or exiting VR — whether through TAB or disabling the VR driver — the viewer correctly restores the original desktop aspect ratio and default zoom levels. Transitioning between Desktop and VR mode is now seamless and hassle-free.

6. Basic VR Controller Support

Basic movement, flight, and camera controls are now functional through VR controllers.

(3D controller models are not yet visible in-world.)

7. Automatic Lens Scaling

The VR view now automatically scales itself correctly to the headset lenses instead of requiring repeated CTRL+8 adjustments.

Manual adjustment is still available if desired.

8. Clean Immersive VR View

The viewer UI is now removed entirely from the VR display to provide a much cleaner and more immersive experience.

This also disables:

Name tags
Hover text
Other overlay clutter

A toggle for this behavior will be added later.

For now, you can use the SteamVR desktop view to control the viewer while inside VR.

9. Anti-Sickness Horizontal Lock

Horizontal Lock is now enabled by default to help reduce motion sickness and disorientation.

This keeps your in-world horizon stabilized while moving.

The lock automatically disables itself:

While seated
During rides such as roller coasters
When holding CTRL to freely move the camera with the mouse

This allows natural movement where appropriate while still protecting against unnecessary VR discomfort.

Features Disabled (For Now)
VR Laser Pointers

VR laser pointers have been temporarily disabled until proper VR interaction systems and mouse/controller integration are completed.

Goals For The Next Update
Full Tracked VR Controllers

True tracked VR controllers capable of interacting with BENTO bones and avatars in real-time.

Because science.

This functionality must remain LOCAL ONLY.

Full VR Interface Mode

A complete VR-native mode where the entire viewer operates inside VR from startup.

The goal is to:

Put on the headset before launching the viewer
Be presented with a full 3D VR environment
Access login screens and virtual keyboards directly inside VR
Never require desktop interaction
Clean Firestorm-Based VR Fork

The Winxtropia Viewer VR remains a clean fork of Firestorm focused strictly on VR functionality.

It does not bypass or interfere with existing security protocols.

This viewer is designed specifically for immersive VR experiences — nothing more, nothing less.
