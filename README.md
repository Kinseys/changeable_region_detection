# changeable_region_detection

Yolov5 detection for regional detection

###For the environments: <br> <br>
  `pip install -r requirements.txt`  <br> <br>
  
###For running:<br> <br>
The default weight is `yolov5s.pt` you can change it by add `--weights xxx.pt` like:<br>
`python detect.py --source data/images --weights xxx.pt`<br> <br>
run `python detect.py --source data/images` for image detection<br> <br>
run `python detect.py --source xxx.mp4` for video detection<br> <br>
run `python detect.py --source 0` for stream detection use your own camera<br> <br>
The results are saved in `yolov5/results/`<br> <br>

### If you want to change the detection region, go to `detect.py` line 96 to change the four points:
hl1, wl1, hl2, wl2, hl3, wl3, hl4, wl4<br> <br>

or you can further load points for regional detection<br> <br>

  
  
