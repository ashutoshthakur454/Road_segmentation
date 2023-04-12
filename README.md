# Road_segmentation

In a road segmentation problem, given an input image we have to identify where the roads are in that image. For this problem there exist a number of computer vision tasks that we can apply. The older computer vision techniques required us to hard code different parameter values in order to segment the roads present in the image. Now this method is prone to errors and also does not generalize well. Like it would work for one image but could completely fail for another image. For instance if we develop a technique to segment roads in an image, then even a shadow on the road could completely ruin our parameter tuning. With the advent of deep learning we got rid of such hand crafting techniques wherein the computer will automatically learn the parameters given a diverse set of data. We will be using Fully Convolutional Networks (FCNs) for road segmentation.FCNs were one of the first techniques that introduced a method of segmentation end to end. This means, given an input image, if we feed the image to the FCN model, it will directly output the segmentation that it is trained for. Although some pre and post processing would be required on the images.

Some sample segmented masks predicted by the model are:
![image](https://user-images.githubusercontent.com/105798962/231578349-c88ab0c1-8143-486e-8f4b-283592517970.png)
![image](https://user-images.githubusercontent.com/105798962/231578430-16706b16-4edd-4b5b-b4b4-9aad055ce6f1.png)
![image](https://user-images.githubusercontent.com/105798962/231578479-a34da7a4-75df-43df-82f2-b4087fcb1980.png)
![image](https://user-images.githubusercontent.com/105798962/231578509-b2cdcf05-4e2c-4632-8a2a-d79386e95154.png)
![image](https://user-images.githubusercontent.com/105798962/231578535-412d7e76-eff2-4f36-b25f-64176a26e76e.png)
![image](https://user-images.githubusercontent.com/105798962/231578561-2dca3ed5-a866-498e-8213-276c258d98ca.png)
![image](https://user-images.githubusercontent.com/105798962/231578593-78410c47-0762-4d4c-b727-783538da8889.png)
![image](https://user-images.githubusercontent.com/105798962/231578632-08bce950-dd57-49d2-806c-f68b39eadb25.png)
![image](https://user-images.githubusercontent.com/105798962/231578683-ff635a3e-b3ac-4ab3-8b64-62b6e8b69ad2.png)
![image](https://user-images.githubusercontent.com/105798962/231578710-cfb004b6-e20f-48c9-a8a8-344437843c34.png)
![image](https://user-images.githubusercontent.com/105798962/231578775-b5ecf66c-4a2f-4de0-a2e8-68d93969788d.png)
![image](https://user-images.githubusercontent.com/105798962/231578796-7e03ea36-37ed-4218-add6-e4bbb2793c02.png)
![image](https://user-images.githubusercontent.com/105798962/231578828-90d38281-6f74-4b79-82fb-dc3283c09a69.png)
![image](https://user-images.githubusercontent.com/105798962/231578870-4a27fb2d-7746-4702-a47f-801ad259c2be.png)
![image](https://user-images.githubusercontent.com/105798962/231578894-81b74f5a-f8c5-4d8f-b051-d6ed699808b8.png)
![image](https://user-images.githubusercontent.com/105798962/231579042-ff0351ea-9440-413d-adb7-adc4c40cd50d.png)
![image](https://user-images.githubusercontent.com/105798962/231579101-e56c4ab1-334b-4c51-8234-3096d562e0c1.png)
![image](https://user-images.githubusercontent.com/105798962/231579186-f56c0928-6b6c-451f-9562-e248e535a7c0.png)
![image](https://user-images.githubusercontent.com/105798962/231579213-6162c539-8e0e-4e11-84b3-f818abef24f9.png)
![image](https://user-images.githubusercontent.com/105798962/231579258-3fe49b63-17a1-4461-87b1-577b56cf21bc.png)

Road segmentation was also done on this video:


https://user-images.githubusercontent.com/105798962/231580134-a371706e-0170-4d4a-995a-da0b007609f6.mp4

And the result obtained was as follows:


https://user-images.githubusercontent.com/105798962/231580624-c8a5a674-eba0-4075-8c21-05464cedeccd.mp4


