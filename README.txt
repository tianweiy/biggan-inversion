Use pip install pytorch-pretrained-biggan to download BigGan library. Go to https://github.com/huggingface/pytorch-pretrained-BigGAN/blob/master/requirements.txt if you face any library issue. 

Two main conclusions I have now are 
1. It is hard to invert a BigGAN using Gradient Descent methods
2. DIP with BigGAN weights works really well for reconstruction / denoising. 

I also have some code for using a gan/dip to do some generative tasks(image translation, label change), but these don't work really well. Contact me at yintianwei@utexas.edu if you are interested. 
