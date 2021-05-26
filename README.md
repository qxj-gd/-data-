# -data-
# 识别人脸运用的是open cv技术 和dlib
将图片转变为灰度图片
 gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
 检测出人脸并保存为vector：
  faces = face_cascade.detectMultiScale(gray, 1.3, 5)
 
