# FaceNet
This is simple implement of FaceNet with pytorch, first use MTCNN to get facial feature of image, then input to pretrained resnet to get image embeddings.Finally we compute cosine similarity between all of the embedding.<br\>
*It seems the image with same size work better than different size <br\>
*Resize will lead to lower accuracy

## Image with same size (top-4)
![image](https://github.com/AppleHank/FaceNet/blob/main/output_without_resize.png)

## Image with different size
![image](https://github.com/AppleHank/FaceNet/blob/main/output.png)
