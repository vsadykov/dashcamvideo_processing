# dashcamvideo_processing
Glue and speed up the dash (car) camera video.
The code is dependent on cv2 (OpenCV) Python library. There are many parameters accross the code, so the code is not very user-friendly. However, the parameters are easily-understandable. Please make sure that you check the input data dimensions and make XSCALE and YSCALE parameters according to them: the video writer is very sensitive to them and does not resize the video automatically.
