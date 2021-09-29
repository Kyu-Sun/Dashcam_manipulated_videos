# Dashcam_manipulated_videos
*[This page is intended to share the data set used in the paper below.]*   
The dataset is 16 gigabytes, available at https://drive.google.com/drive/folders/1AAJvZis1LNfkmaNs4bM0p54qOc5mLggs?usp=sharing.   
Since personal information such as vehicle number is included, a compressed password is set in the dataset file.   
If you need a dataset for research purposes, please send an email to bluesks@korea.kr in the form below.   
```
[email title] Request the password of dashcam dataset
[contents]
name :
affiliation :
position :
object:
```

## Title : Vehicle Speed Measurement Methodology Robust to Playback Speed-Manipulated Video File 
### Abstract

Concomitant with the virtual ubiquity of dashcams in vehicles, the instantaneous speed of vehicles during accidents can now be measured using dashcam videos to understand the causes of such accidents. In this study, we estimated vehicle speeds using dashcam videos recorded in various road environments and analyzed them by comparing them to ground truth. We also considered various scenarios yielding retaken and re-encoded videos from additional recording devices, depending on the circumstances, wherein the original video can be manipulated in terms of playback speed and/or frames per second. The experimental results revealed that the actual and measured speeds were similar for most user-specific intervals. Moreover, the results suggest that our estimated speed is adequately valid as evidence, regardless of retake and re-encoding states. Furthermore, we adopted a statistical approach (i.e., Pearson's correlation coefficient analysis) to verify the proposed vehicle speed estimation method. The results showed that when playback speed was manipulated in re-encoded or retaken video, the proposed method consistently measured speeds at 99.99 % accuracy. This verified method will play an important role in deriving reliable results from various evidential video sources.

A detailed description of the dataset is available in the journal paper "Vehicle Speed Measurement Methodology Robust to Playback Speed-Manipulated Video File", published on IEEE ACCESS, 2021.


### Dataset
#### 1. iROAD T8
```
Resolution : 1280x720
FPS : 30
Recording duration : 1min 30 sec
Video Codec : H.264/AVC
```
#### 2. iNavi Z500+
```
Resolution : 1920x1080
FPS : 30
Recording duration : 1min
Video Codec : H.264/AVC
```
#### 3. Eyeclone i5
```
Resolution : 1920x1080
FPS : 30
Recording duration : 1min 16 sec
Video Codec : H.264/AVC
```
#### 4. FineVu LX2000
```
Resolution : 1920x1080
FPS : 30
Recording duration : various
Video Codec : H.264/AVC
```
#### 5. Lead I K2
```
Resolution : 1920x1080
FPS : 30
Recording duration : 1min 16 sec
Video Codec : H.264/AVC
```
#### 6. Lead I K2
```
Resolution : 2560x1440
FPS : 30
Recording duration : 30 sec
Video Codec : H.264/AVC
```

### Datasec Configuration
_There are original, Re-encoding, Retake (Record by camera), and retake (Screen Record) folders according to each model._
#### Original
* Downtown video
* Highway Video
#### Manipulated(Re-encode, Retake)
_These are files that have been re-encoded and retaken from the original file._
_**VideoProc and potencoder** were used for re-encoding, **ShareX(ffmpeg)** was used for retake (Screen Record), and **samsung galaxy s8 and sony a5000** were used for retake (Record by camera)._
* Downtown, 0.5x(playspeed), 24fps
* Highway, 0.5x(playspeed), 24fps
* Highway, 0.5x(playspeed), 30fps
* Highway, 0.7x(playspeed), 30fps
* Highway, 1.5x(playspeed), 30fps
* Highway, 1x(playspeed), 10fps
* Highway, 0.5x(playspeed), 24fps
* Highway, 0.5x(playspeed), 60fps
