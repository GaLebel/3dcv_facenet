# 3DCV Project - FaceNet Paper implementation

In this project, We implemented the FaceNet architecture, which had achieved state-of-the-art results in the task of Face Recognition. For comparison, we trained three CNN models with different parameters and also demonstrated the effects of a class imbalanced dataset.


## Usage
Both facenet and the CNN models need to be downloaded from our mirror. <br />
- Checkpoints models can be found here for the different models:
    - CNN:
      - 800,000 parameters model : [download here](https://nx29079.your-storageshare.de/s/QFe5spQKAx4s26E)
      - 6,000,000 parameters model : [download here](https://nx29079.your-storageshare.de/s/nGfDL4g5ssaPirq)
      - 13,000,000 parameters model (imbalanced classes): [download here](https://nx29079.your-storageshare.de/s/iCiywWicPwb4CYz)
    - FaceNet
      - MNIST model: [Demo link](https://github.com/GaLebel/3dcv_facenet/blob/main/models/MNIST%20Toy%20Example/MNIST_Toy.ipynb)
      - LFW model: [Demo link](https://github.com/GaLebel/3dcv_facenet/blob/main/models/FaceNet/FaceNet_Demo.ipynb)
    the checkpoints [checkpoint link](https://github.com/GaLebel/3dcv_facenet/blob/main/models/FaceNet/data/cv_exp8.zip) and the embeddings [embedding names link](https://github.com/GaLebel/3dcv_facenet/blob/main/models/FaceNet/data/embed_list_names_exp8.csv), [embedding values list](https://github.com/GaLebel/3dcv_facenet/blob/main/models/FaceNet/data/embed_list_np_exp8.csv) fro the experiment 8 in the report can be downloaded and then used with the demo notebooks.

The model file should be placed in its corresponding model folder.<br />
To use the models, there are demo notebooks for facenet with faces, and facenet with the mnist dataset, and also a 'use model' notebook for each CNN model.
The usage of those notebooks requires having both Keras and PyTorch in your python's enviroment.
## Project Report
Here one can find the project report describing the project and its background in detail [report link](https://nx29079.your-storageshare.de/s/bKykp5N9KbHxZNz).
