# Cycling Sounds Project

This repo contains all of the raw data, processed data and code used to generate the results for the Cycling Sounds Project.

Please note that some of the notebooks contain rough processing code that, running the notebooks top to bottom may not produce the same results as in the final data. Some file paths may also need to be changed to run the notebooks.

Folder structure:
 - `Audio Data/` - Contains the processed audtio files and analysis notebook
 - `Original audio (with stops)/` - Contains the original audio files, which incude stops in the ride. It includes the audio files from the ride from Hyde Park to Mile End and the audio files from the dictaphone none of which were used in the final analysis.
 - `Original video (with stops)/` - Contains the original video files, which incude stops in the ride. These clips are split into 5 minute segments.
 - `Route data/` - this contains csv files with well-known text (WKT) representation of the route taken. The WKT data can be used to plot the route in GIS software. It also contains the a notebook with the code used to generate the WKT data and map the audio and video data on to timed segments of the route.
 - `Vibration data/` - Contains the the code and data for the optical flow analysis of the video data.

 Note that at the time of submission, the final video file (`MileEnd-Hyde-Park-iPhoneAudio.mp4`) is not present in the repo as it is 4,48 GB and would take to long to upload using Git Large File Storage. It can be found on [cloud storage here](https://www.icloud.com/iclouddrive/085KKFuzxcoAcHNufAjX0grgQ#MileEnd-Hyde-Park-iPhoneAudio).
