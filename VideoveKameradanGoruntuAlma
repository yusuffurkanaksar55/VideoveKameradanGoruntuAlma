import cv2
import numpy as np


#0->BİLGİSAYARDAKİ KAMERAYI KULLANACAK
#1->USBYE BAĞLI OLARAK KAMERA KULLANACAK
#2->BİLGİSAYARDAKİ VİDEOYU KULLANIR
kamera=cv2.VideoCapture(0)







while True:
    ret,kare=kamera.read()
    bolge=kare[0:200,0:200]
    
    print(kare)
        
    
    cv2.imshow("Video",kare)
    cv2.imshow("Kamera",bolge)
    if cv2.waitKey(25) & 0xFF ==ord('q'):
        break

kamera.release()
cv2.destroyAllWindows()
