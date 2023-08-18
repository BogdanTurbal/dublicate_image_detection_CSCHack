# dublicate_image_detection_CSCHack
Dublicate image detection using NN
Our model uses two different blocks:
1. We train autoencoder(U-Net based) for encoding initial pictures to lover dimention(bottleneck)
   ![Autoencoder](https://github.com/BogdanTurbal/dublicate_image_detection_CSCHack/blob/main/resources/Screenshot%202023-08-18%20142423.png??raw=true)
2. We use Siamise network that operates on encoded images from Autoencoder to detect dublicats
    ![Siamise](https://github.com/BogdanTurbal/dublicate_image_detection_CSCHack/blob/main/resources/Screenshot%202023-08-18%20142436.png?raw=true)
