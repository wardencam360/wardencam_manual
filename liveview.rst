.. _liveview:

Live View
=========

| After signing in as viewer, the live view is opened.
| The viewer shows the **live streaming from your other Wardencam connected devices that are in "camera" mode,**
| The Viewer also displays the frame rate and resolution, a list of other wardencam connected devices, and control buttons**.
|
| |liveview|
.. |liveview| image:: img/liveView.png
   :width: 640pt
|

Motion detection button |motiondetecticon|
-------------------------------------
.. |motiondetecticon| image:: img/motiondetect.png
   :width: 30pt
| The first button is the motion detection button.
| It allow the viewer to remotely turn on & off the motion detection
  function.
| If motion detection is already enabled, the button will turn red.

Low light button |lowlight icon|
---------------------
.. |lowlight icon| image:: img/lowlight_icon.png
   :width: 30pt
| For low light conditions, use this feature to increase constrast to see streaming images better

Flashlight button |flashlight icon|
---------------------
.. |flashlight icon| image:: img/flashlight_icon.png
   :width: 30pt
| Turns on the LED light on the camera device remotely.
| Only the rear camera has the flash light.

Video Log |videologicon|
-----------------------------------
.. |videologicon| image:: img/videolog_icon.png
   :width: 30pt
| If a Dropbox account is linked, the cloud button opens the cloud view
  and shows all the video logs.
| Video logs are different from motion detection recording.
| Motion detection recording is triggered by a motion event; while video
  logs are enabled by “24/7 recording” in settings. Once enabled, the
  camera will continue logging nonstop.
  
Talk button |talk icon|
--------------------------------------
.. |talk icon| image:: img/talk.png
   :width: 30pt
| Hold the audio button and talk.
| Release the button to send the voice to the camera device.

Reverse Cam button |reversecam icon|
--------------------------------------
.. |reversecam icon| image:: img/reversecam_icon.png
   :width: 30pt
| Hold the audio button and talk.
| Release the button to send the voice to the camera device.

Motion detection flag button |motion flag|
------------------------------------------
.. |motion flag| image:: img/motionflag.png
   :width: 20pt
| This button shows the number of detected motion events.
| If a Dropbox or Google Drive account is linked, the motion flag button opens the cloud
  view and shows all the motion detection recordings.
  
Battery icon |battery1| |battery2|
----------------------------------
.. |battery1| image:: img/battery_6.png
   :width: 24pt
.. |battery2| image:: img/battery_c3.png
   :width: 24pt
| Shows the battery power percentages and charging status.
| The right icon shows the device is being charged.

P2P connection icon |p2p1| |p2p2|
---------------------------------
.. |p2p1| image:: img/p2p.png
   :width: 24pt
.. |p2p2| image:: img/p2p_warning.png
   :width: 24pt
| Shows the peer to peer connection status.
| Red exclamation mark indicates peer to peer connection has failed.
| Additional precautions are required if P2P connection failed.

Vistapoints
-----------
.. |vistapoints| image:: img/vistapoints.png
   :width: 320pt
| |vistapoints|
|
| Vistapoints shows a list of available camera devices.
| Clicking on a camera name to connect to a different camera device.
| To add another camera, just sign in with the same google account.

fps, kbps, & resolution
-----------------------

| fps = frames per second
| kbps = kilo bytes per second
| resolution = image resolution in pixels

Developer tips
--------------
1. Live video are normally streamed via peer to peer connection. No
   third party is involved to handle the video stream.
2. Pay extra attention to the P2P connection icon. P2P failure is
   normally due to mobile data carrier blocking P2P connection.
3. Depending on the image settings and camera device hardware speed,
   viewer may expereince a couple seconds of delay. This should not be
   an issue if motion detection recording is enabled.








