# ai_coding_test

Hello,

All the image files are assumed to be in "images" directory. There is also a file **train.csv** which contains the file names with the class '1' for apple. 
To make the algorithm effectively we can add some images in the directory which are for non-apples and the corresponding lables should be added to the training file with the label '0' for non-apple.

**apple_classifier.ipynb** code file is shared in the repository which shows the ML program used to solve the problem. The solution approach assumes that we have enough RAM to excute the ML program, in the case otherwise it is good to use the approach to process batch of data in one-go and train on that batch.

The program is expected to output class as '1' if the test image is of apple. We assume that the **test.csv** file contains the names of the files whose labels are to be predicted.


Best Regards,

Shishir Jain
