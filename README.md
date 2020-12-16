# StyleTransfer
**Deep Learning End Semester Project - Done By Raj Uttam (ru388) and Neeharika Vangavaragu (nv911)**\
\
In this project we've tried to implement neural style transfer using 2 techniques\
  i. Gaty's et al Implementation \
  ii. Instance Normalization Technique 

You'll find code for both these techniques in the form on Jupyter Notebooks

We've used google colab environment for developing this project and we suggest you to use the same.\
Please checkout Gaty's_method notebook first followed by Instance normalization notebook

**Description of Files and Folders**\
  i. Gaty's_Method.ipynb -: Jupyter Notebook File for Gaty's Method\
  ii. instance Normilization.ipynb -: Jupyter Notebook for the instance normalization Technique\
  iii. Gaty's output -: Output Images generated using Gaty's technique\
  iv. Instance Normalization - Input Images -: The input image files that are required for the Instance Normalization Notebook\
  v. Instance Normalization - Outputs :- Some Output Images generated using the Instance Normalization Technique\
  
**Note:**\
Its possible that you could face some problems when you try to run the Instance Normalization Notebook, we're importing torchfile package\
and when you compile and run our code, you could get an error saying "xrange is not defined". If you get this error then here are 3 simple steps that will help you resolve this error

i. Click on the file name in which the error is coming (torchfile.py)\
![Error](https://user-images.githubusercontent.com/60336372/102344847-7bbd0300-3f6a-11eb-9dc4-97ea2cd980c4.PNG)
ii. Edit Line number 228(torchfile.py) from for i in xrange(n) to for i in list(range(n) and save the file\
![Error-2](https://user-images.githubusercontent.com/60336372/102344863-811a4d80-3f6a-11eb-875b-9285010bd3cd.PNG)

iii. Restart the runtime and start executing from cell 3 of the notebook ( Running cell 1 and 2 will download the package again and replace the change you just made)

You should be able to see our outputs provided you've uploaded the input image files from Instance Normalization - Input image folder to google colab
