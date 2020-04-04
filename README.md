# silver-captcha
 Generates captcha text
 
 Installation instructions:
 
 pip install silver-captcha
 
 Usage example:
 
 from silver_captcha import captcha
import cv2

obj = captcha.SilverCaptcha()

img = obj.generate_captcha()

cv2.imshow("result",img)
cv2.waitKey(0)
