# Rust-Detection-using-Mask-RCNN #

I trained using 15 samples. You have increase the no. of samples in order to achieve good results. I took images from https://github.com/anirbankonar123/CorrosionDetector/tree/master/download/rust .

Use http://www.robots.ox.ac.uk/~vgg/software/via/via-1.0.6.html to get a JSON file of corroded regions and make changes to the code accordingly.

I have used transfer learning approach using MASK RCNN to detect corrosion in any image.
I got this as result. It can get better after proper training with large dataset.
![Screenshot](test_result.jpg)
