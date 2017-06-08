# Style-Transfer

## Overview

We're going use pre-trained VGG16 convolutional network that won the ImageNet competition in 2014 for image classification to transfer the style of a given image to another. [This](https://arxiv.org/abs/1508.06576) is the original paper on the topic.


## Dependencies

run `pip install -r requirements.txt` to install the necessary dependencies


## Results

- Base Image : ![](https://github.com/Ujjwal-9/Style-Transfer/blob/master/images/me.jpg?raw=true)
- Style Image : ![](https://github.com/Ujjwal-9/Style-Transfer/blob/master/images/styles/wave.jpg?raw=true)
- Result - tyle-Transfer : ![](https://github.com/Ujjwal-9/Style-Transfer/blob/master/images/Result/1.jpg?raw=true)


## Usage

If it doesn't exist, create a file called ~/.keras/keras.json and make sure it looks like the following:

   ````
   {
       "image_dim_ordering": "tf",
       "epsilon": 1e-07,
       "floatx": "float32",
       "backend": "tensorflow"
   }
   ````

Then you can run the code via typing `jupyter notebook` into terminal.


## Credits


The credits for this code go to [hnarayanan](https://harishnarayanan.org/writing/artistic-style-transfer/).




