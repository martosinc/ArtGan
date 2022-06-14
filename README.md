# ArtGAN
Generating Abstract Art with Generative Adverserial Networks.

## Examples
### Cherry-picked
(Original) 64x64   
![image](images/exmp.png)
![image](images/exmp_2.png)
![image](images/exmp_3.png)
![image](images/exmp_4.png)
![image](images/exmp_5.png)
![image](images/exmp_6.png)
![image](images/exmp_7.png)
![image](images/exmp_8.png)
![image](images/exmp_9.png)
![image](images/exmp_10.png)
![image](images/exmp_11.png)

(Resized) 256x256  
![image](images/exmp256.png)
![image](images/exmp256_2.png)
![image](images/exmp256_3.png)
![image](images/exmp256_4.png)
![image](images/exmp256_5.png)
![image](images/exmp256_6.png)
![image](images/exmp256_7.png)
![image](images/exmp256_8.png)
![image](images/exmp256_9.png)
![image](images/exmp256_10.png)
![image](images/exmp256_11.png)

### Random (64)

![image](images/64imgs.png)
![image](images/64imgs_2.png)
![image](images/64imgs_3.png)

## Structure
I was using a standard DCGAN with an image size 64x64
Pre-trained models are stored in files GTrain.pt and DTrain.pt for Generator and Discriminator accordingly

## Dataset
I was using a Kaggle [dataset](https://www.kaggle.com/competitions/gan-getting-started/overview) consisting of 300 images of Monet's paintings and 7000 images of real photos.