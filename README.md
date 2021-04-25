# Group13_Capstone
Image Colorization using GAN
<br />

So Let's get started.
<br /><br />
This repo has two notebooks.
<br />
Run the gan_img_col notebook using google colab for better performance.
<br />
All versions of libraries used in colab can be found [here](https://github.com/BitsOfPaper/Group13_Capstone/blob/main/requirements)
<br /><br />
For interface use jupyter on local system with anaconda
<br />
All versions of libraries used on local machine can be found [here](https://github.com/BitsOfPaper/Group13_Capstone/blob/main/requirements)
<br /><br />
Since Google Colab uses tensorflow 2.4.x and Anaconda only supports 2.1 for now
<br />saving entire model in colab and loading on local machine is not feasible.
<br />So create the architecture of the model and load the weights to use interface.
<br />Download weights.zip and extract weights into the 'saves' folder.


File structure:
Download the [img_data](https://drive.google.com/file/d/1Mdn2RZhA0CXXLU06KMlq_QCtCKf6D5Rn/view?usp=sharing)
<br />Extract
<br />Main directory 'img_data' (Placed in Goolge Drive, use accordingly or change path)
<br />Sub dirs: 'fimg', 'test'
<br />Create 'saves' directory in img_data(Main Dir) and extract weights from [here](https://github.com/BitsOfPaper/Group13_Capstone/blob/main/weights.zip)
