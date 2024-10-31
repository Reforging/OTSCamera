# OTSCamera
A LuaU OTS Camera Module

module.New(player) -- takes a @player object as a parameter and creates a new camera object

module:EnableCamera(enabled) -- takes @enabled, a boolean value, as a parameter and enables and disables the camera object

module:SetCameraPosition(position, t) -- takes @position, a Vector3 value, and @t (time), a number, to update the camera position/offset in relation to the player.




SETUP:

Occlusion should be parented to the Camera module
A Vector3Value laebled CameraPos should be added to the camera module

Simply require the camera module after setup in whatever controller script needed
