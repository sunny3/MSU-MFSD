# MSU-MSFD dataset for face spoof detection
Dataset from this repo in 'master' branch contains only the first picture frames from videos of the publicy-available [MSU-MSFD dataset](https://ieeexplore.ieee.org/document/7031384).
A branch 'more pics' contains zip arhive in 4 parts wich include, in addition to the first frames, all frames whose numbers are a multiple of 10 from original videos.
<br><br>
Pictures of the real faces are in the `./pics/real` folder, and fake pictures are in the `./pics/attack`<br><br>
The 2 text files in the root directory, train_sub_list.txt and test_sub_list.txt, specify the client IDs chosen in the training set and testing set respectively. Clients that appear in one of the data sets (train or test) do not appear in the other set.<br><br>
The original MSU-MFSD, from which pictures in this repo were extracted, is a presentation attack database which consists of videos of printed attacks, as well as replay attacks generated with a mobile phone and a tablet. The acquisition devices were a laptop and an Android phone. <br><br>
If you want to use data from this repo, please, cite the authors of the original dataset:<br><br>
`D. Wen, A. K. Jain and H. Han: "Face Spoof Detection with Image Distortion Analysis", In IEEE Trans. Information Forensic and Security, 2015.`