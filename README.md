# face-detection-issue


error                                     Traceback (most recent call last)
Cell In[28], line 9
      6     continue
      8 gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
----> 9 face = face_clsfr.detectMultiScale(gray, 1.3, 5)
     11 for x, y, w, h in faces:
     12     offset_y = int(h * 0.50) 

error: OpenCV(4.10.0) D:\a\opencv-python\opencv-python\opencv\modules\objdetect\src\cascadedetect.cpp:1689: error: (-215:Assertion failed) !empty() in function 'cv::CascadeClassifier::detectMultiScale'
