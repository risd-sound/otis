# otis
Code, files, and info. for Otis College of Art and Design workshop.
Introduction to audio programming for artists: February 27, 2018

Workshop Description:
Shawn Greenlee (Associate Professor, RISD) will lead a workshop on designing sound-based interactions and experiences with the programming language Pure Data (Pd). The workshop's focus will be on the development of a project for mobile devices (e.g. iOS and Android), incorporating touch-screen interaction and data from onboard sensors. Emphasis will be on manipulating recorded sound (sampling) for live performance or installation contexts.

**For today's session:**

1. You'll need a laptop, a mobile device (iOS or Android), a USB sync cable, and headphones.
2. On your laptop, download and install Pd 0.48-1 (Pure Data) from <a href="http://msp.ucsd.edu/software.html" target="_blank">http://msp.ucsd.edu/software.html</a>.  Put it in your Applications folder (i.e. do not leave in your Downloads folder). On an Mac, you may need to adjust your security settings under System Preferences to allow Pd to open for the first time.  
3. Download the latest MobMuPlat development package: <a href="http://danieliglesia.com/mobmuplat/" target="_blank">http://danieliglesia.com/mobmuplat/</a>. Make a new working folder on your Desktop and move the MobMuPlat package there (get it out of your Downloads folder).  If you have a Windows computer, you'll need Java installed for the editor to work (this could take some time to get properly installed): https://java.com/en/download/help/windows_manual_download.xml
4. For your mobile device, download MobMuPlat either from <a href="https://itunes.apple.com/us/app/mobmuplat/id597679399?mt=8" target="_blank">iTunes store (iOS)</a> or <a href="https://play.google.com/store/apps/details?id=com.iglesiaintermedia.mobmuplat" target="_blank">Google Play store (Android)</a>.  It's a free app.
5. For iOS, you'll need iTunes.  For Mac + Android, you can use Android file transfer:  <a href="https://www.android.com/filetransfer/" target="_blank">https://www.android.com/filetransfer/</a>  
6. You'll need the appropriate sync cable for your device.  Alternatively you can transfer files via AirDrop (iOS), e-mail, or file-sharing apps. On Mac + iOS this is pretty easy.  Windows and Android more complicated.

---

**Agenda 2.5 hours:**

PART 1 (45 min)
* Quick overview of composer-built instruments, NIME (new interfaces for musical expression), Pd as prototyping/development platform for mobile computing (e.g. product sound design, interactive art and music, apps and games)
* Some ready examples running in MobMuPlat
* Check Pd and MobMuPlat installations
* Introduction to programming in Pd
* Patch along: [metro] and making some sound (sound synthesis basics)

PART 2 (45 min)
* Sampling overview (manipulating recorded sound)
* Patch along: making a sample scrubber in Pd

PART 3 (45 min)
* Introduction to GUI design with MobMuPlat editor
* Patch along: receiving messages from GUI (OSC addresses)
* Patch along: receiving system messages for using device sensors (tilt data)
* Patch along: sending messages to GUI (OSC addresses)
* Transferring project files to your mobile device
* Open in MobMuPlat and play
* Troubleshooting

PART 4 (15 min)
* Wrap-up
* Ideas toward modifying sample scrubber

---

**Additional resources:**

* Pd tutorial: http://pd-tutorial.com
* Code from Programming Sound: Performance Systems course at RISD:  <a href="https://github.com/risd-sound/psps" target="_blank">https://github.com/risd-sound/psps</a>  
* YouTube videos by Shawn using Pd-extended (Pd version not currently supported, but most info. applies): https://www.youtube.com/watch?v=HrX5y-vu0j8&feature=youtu.be&list=PLyFjYyw48iUd0MLWarDxpBIqhRaMNID95
* MobMuPlat alternatives Pd Party (iOS): https://github.com/danomatika/PdParty and Pd Droid Party (Android) http://droidparty.net

---
