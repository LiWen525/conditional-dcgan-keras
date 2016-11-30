## KERAS-CONDITIONAL GAN ##Implementation of conditional GAN https://arxiv.org/abs/1411.1784 with [keras](https://github.com/fchollet/keras).Implements the improvements and architecture of https://arxiv.org/pdf/1611.07004v1.pdf.Code borrows from the Keras non-conditional GAN https://github.com/jacobgil/keras-dcgan and the Torch conditional GAN https://github.com/ppwwyyxx/tensorpack/blob/master/examples/GAN/Image2Image.py.---This assumes theano ordering.---## Usage**Training:** `python dcgan.py --mode train --batch_size <batch_size>`  python dcgan.py --mode train --path ~/images --batch_size 128**Image generation:**`python dcgan.py --mode generate --batch_size <batch_size>``python dcgan.py --mode generate --batch_size <batch_size> --nice` : top 5% images according to discriminatorpython dcgan.py --mode generate --batch_size 128---## Result**generated images :** ![generated_image.png](./assets/generated.png)**train process :**![training_process1.gif](./assets/0_0.gif)![training_process2.gif](./assets/13_0.gif)![training_process3.gif](./assets/99_0.gif)---