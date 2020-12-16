# StyleTransfer
**Deep Learning End Semester Project - Done By Raj Uttam (ru388) and Neeharika Vangavaragu (nv911)**\
\
In this project we've tried to implement neural style transfer using 2 techniques\
  i. Gathy's et al Implementation \
  ii. Instance Normilization Technique 

You'll find code for both these techniques in the form on Jupyter Notebooks

We've used google colab environment for developing this project and we suggest you to use the same.\
Please checkout Gaty's_method notebook first followed by Instance normilization notebook

**Description of Files and Folders**\
  i. Gaty's_Method.ipynb -: Jupyter Notebook File for Gaty's Method\
  ii. instance Normilization.ipynb -: Jupyter Notebook for the instance normilization Technique\
  iii. Gaty's output -: Output Images generated using Gaty's technique\
  iv. Instance Normilization - Input Images -: The input image files that are required for the Instance Normilization Notebook\
  v. Instance Normilization - Outputs :- Some Output Images generated using the Instance Normilization Technique\
  
**Note:**\
Its possible that you could face some problems when you try to run the Instance Normilization Notebook, we're importing torchfile package
and when you compile and run our code, you could get an error saying "xrange is not defined". If you get this error then here are 3 simple steps that will help you resolve this error

i. Click on the file name in which the error is coming (torchfile.py)
ii. Edit Line number 228(torchfile.py) from for i in xrange(n) to for i in list(range(n) and save the file
iii. Restart the runtime and start executing from cell 3 of the notebook ( Running cell 1 and 2 will download the package again and replace the change you just made)

You should be able to see our outputs provided you've uploaded the input image files from Instance Normilization - Input image folder to google colab
