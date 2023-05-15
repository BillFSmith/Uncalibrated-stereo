# Uncalibrated-stereo
Comparison of stereo matching approaches for uncalibrated photos<br>

These techniques are generally designed to be used for depth map generation from two calibrated cameras, on a fixed rig. <br>
However, it can be useful to take photos with handheld uncalibrated cameras. The images may be taken sequentially with the same camera or simultaneously with two different cameras. <br>
This allows for hardware to be reused and for wide baselines (multiple metres) to be used. <br>

Leaderboard used:<br>
https://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=stereo

Libraries with available code: <br>
>Library,          GPU needed<br>
>IGEV-Stereo,      Yes<br>
M-FUSE,            Yes<br>
SF2SE3,            Yes<br>
LEAStereo,         Yes<br>
ACVNet,            Yes<br>
ACVNet (v2),       Yes<br>
PCWNet,            No<br>
LaC+GANet,         Yes<br>
PSNN,             No<br>
CREStereo,         Yes<br>
UCFNet,           No<br>
LaC+GwcNet,        Yes<br>
GMStereo,          Yes<br>
....<br>
RAFT-Stereo,          Yes<br>


I've colated some Colab files and written others to test them with uncalibrated stereo matching:

CREStereo<br>
https://colab.research.google.com/drive/1sc08zw-SdHbKvWMliTJ1pafO7yPRoIQn<br>

IGEV-Stereo<br>
https://colab.research.google.com/drive/1HzksbEualnL2YBI75t4Eh9qtWLwq9Xi4<br>

Fast ACVNet<br>
https://colab.research.google.com/drive/1AVdWLoZA36B1kfEE2-kvqN5bG89huAzy<br>

RAFT-Stereo<br>
https://colab.research.google.com/drive/1PIdOOVdhC0or9kmWhe32uqtZQ3s5jXIW<br>
