# Uncalibrated-stereo
Comparison of stereo matching approaches for uncalibrated photos

These techniques are generally designed to be used for depth map generation from two calibrated cameras, on a fixed rig. 
However, it can be useful to take photos with handheld uncalibrated cameras. The images may be taken sequentially with the same camera or simultaneously with two different cameras. 
This allows for hardware to be reused and for wide baselines (multiple metres) to be used. 

Leaderboard used:
https://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=stereo

Libraries with available code:
Library           GPU needed
IGEV-Stereo       Yes
M-FUSE            Yes
SF2SE3            Yes
LEAStereo         Yes
ACVNet            Yes
ACVNet (v2)       Yes
PCWNet            No
LaC+GANet         Yes
PSNN              No
CREStereo         Yes
UCFNet            No
LaC+GwcNet        Yes
GMStereo          Yes
....
RAFT-Stereo


I've colated some Colab files and written others to test them with uncalibrated stereo matching:
