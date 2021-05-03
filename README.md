# Traffic_sign_Retinanet
In this project i will use Retinanet in Keras for Multi Object Detection in traffic sign dataset.
The dataset from 'https://challenge.zalo.ai/portal/traffic-sign-detection'.
The reason why I choose Retinanet because when i saw the dataset i found that the dataset has imbalance in classes. 
Another model usually use Cross Entropy loss.

![image](https://user-images.githubusercontent.com/57851053/116907249-8a7f2a80-ac6b-11eb-8855-f560c7ceaadd.png)

![image](https://user-images.githubusercontent.com/57851053/116907294-98cd4680-ac6b-11eb-947c-045cbd96ba20.png)

But Retinanet use Focal loss by add one focusing parameter γ .

![image](https://user-images.githubusercontent.com/57851053/116907575-f5306600-ac6b-11eb-9c64-478cfd1be530.png)

Architecture of Retinanet 

![image](https://user-images.githubusercontent.com/57851053/116907668-142ef800-ac6c-11eb-8c06-034456c1235a.png)


This is a result of my model

![image](https://user-images.githubusercontent.com/57851053/116884238-b50fba00-ac50-11eb-9132-af33f536927c.png)




References:
https://www.miai.vn/2021/04/01/xay-dung-he-thong-nhan-dien-bien-bao-giao-thong-bang-retinanet/
https://medium.com/@tabdulwahabamin/an-introduction-to-implementing-retinanet-in-keras-for-multi-object-detection-on-custom-dataset-be746024c653
https://github.com/fizyr/keras-retinanet
