This project is the final task my group and I implemented as part of a final task 
we were required to finish in the course of "Deep ANNs with TensorFlow" at our university. 
It's about training an advanced ANN to colorize black-and-white images. 
I did implement all the work myself including the python code, training the network using my AWS account and testing 
the performance of it in addition to downloading and preprocessing the LSUN church-outdoor images, that I used for 
the task, myself using my own preprocessing scripts.
Only the documentation pdf file and some checking were done by another member of the group.

Attached to this folder:
- image-colorization-with-CGANs : notebook file of our code.
- Test script : notebook file to restore the network after finishing training to present test phase
on testing data and show performance using generated images based on test data in the notebook.
- Preprocessing : notebook file of preprocessing we did to the LSUN data to fit the network before feeding it through.
- summaries : Summaries of training and validation processes.
- new_data : lsun images of outdoor churches without preprocessing.
- resized_images : preprocessed training LSUN images of churchs outdoor ready for the network to use.
- resized_test_images : test data from LSUN images of churchs outdoor that are already preprocessed for the purpose of 
this project.
- Weights : represent the network design and weights saver files.
- Image-Colorization-using-CGANs : pdf file as documentation of our work.
