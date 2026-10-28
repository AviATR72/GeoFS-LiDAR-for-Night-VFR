# GeoFS-LiDAR-for-Night-VFR
LiDAR-style addon for night VFR
------
GeoFS LiDAR
------

This addon allows night VFR in GeoFS 4.0 by projecting LiDAR (light detection and ranging)-like dots onto terrain features near the user aircraft. 
<img width="1348" height="486" alt="Screenshot 2026-10-28 14 12 08" src="https://github.com/user-attachments/assets/d9beea90-1ddd-4f89-b1a2-52d8abea534f" />
LiDAR dots are projected on the terrain around the aircraft, updating every few seconds with the aircraft's position and an increasing number of LiDAR points before resetting and repeating. 

<img width="242" height="379" alt="Screenshot 2026-10-28 14 42 41" src="https://github.com/user-attachments/assets/33646386-c749-462f-98c9-51b606629cf3" />

Lower altitude terrain is projected with different coloured LiDAR points. Near-sea-level terrain is projected with blue LiDAR points. By 5000 ft the LiDAR points turn green. By 8000 ft the LiDAR points turn yellow. By 12000 ft the LiDAR points turn orange. By 17000 ft the LiDAR points turn red, and above 20000 ft, the LiDAR points appear on the terrain as deep red.
<img width="905" height="499" alt="Screenshot 2026-10-28 14 46 42" src="https://github.com/user-attachments/assets/d4525ff1-3122-46ad-909f-ca87455500cf" />

Installation is currently done with the Console function. I am working to implement Tampermonkey support as well. To install the LiDAR script, copy the code from the "LiDAR Script" file, go to GeoFS, click "FLY", and open the Console. Paste the code into the console and click "Enter". 

Updates are to be expected. Likely updates include sliders to change point density or brightness, transparency support (H on GeoFS) and work to make it only function at night (During the day it looks bad) 
Any suggestions for updates, I can be reached at the Discord handle "aquila_atr72". 
