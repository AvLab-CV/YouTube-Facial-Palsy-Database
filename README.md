# YouTube-Facial-Palsy-Database ([Website](https://sites.google.com/view/yfp-database/))

By Gee-Sern Jison Hsu, Jiunn-Horng Kang, Wen-Fong Huang

YouTubeFacial Palsy (YFP) database, which is the first public database that we made for the study on the visual inspection of facial palsy symptoms. It contains 32 video clips of 22 facial palsy patients collected from YouTube. We convert the videos into sequences of images, and have the images labeled by facial palsy clinicians.As the number of patients is limited, we adopt the Leave-One-Person-Out (LOPO) protocol for performance evaluation.

The patient in each video speaks to the camera and the camera records the facial expression variation across time. Depending on different patients at different time of recording, some images show the syndrome of the palsy-caused deformation with high intensity and some with median or low intensity, justified by the severity revealed by the deformation pattern. Then images with very low intensity may appear similar to a normal face, and in some cases, even the clinician can hardly tell whether the face is with the palsy syndrome if only looking at one single image without referencing other frames. For some patients, the palsy-induced facial asymmetry is easy to observe even when the patient stops talking and keeps neutral in the expression.The proposed database were collected by the following characteristics:

- 32 videos of 21 patients from YouTube, and  a few patients have multiple videos.
- As the shortest facial palsy session lasts for a second, we convert each video into an image sequence with 6FPS;
- Manually labeled local palsy regions when the deformation intensity was considered sufficiently high by clinicians. 
- The palsy regions were labeled by three independent clinicians, and we used the intersection of the independently cropped regions as the ground truth.
- We labeled the intensity observed in each palsy region as 0.5 for low or 1.0 for high.
- In addition to the syndrome intensity, we also labeled the palsy regions into Classes Eyes or Mouth. 

We hope that the YouTube Facial Palsy (YFP) Database could revolutionized the landscape of facial palsy research. A detailed introduction of YFP can be found in the [paper](https://ieeexplore.ieee.org/document/8558494).

Here are some examples from the dataset.

![Alt text](YFP_Samples.PNG?raw=true "Title")


Update
--
|Date|Updata|
|----|------|
|2018-12-04|YFP dataset is composed and made available to the research community.|


Data Download 
--
 1. [Get a password](#how-to-get-a-password)
 2. [Restriction](#restriction)
 3. [Download Link](#download-link)
 
How to get a Password
-
Please send an e-mail to the database administrator and cc. to Prof. Gee-Sern (Jison) Hsu to receive the passcode to unlock the zipped database. Your Email MUST be sent from a valid University account and include the following [request forms](./RequestForms.txt):

```
Subject: Application to download the YFP database
Name: <your first and last name>
Affiliation: <University where you work>
Department: <your department>
Current position: <your job title>
Email: <must be the email at the above mentioned institution>
Postal Address:
Phone number:
I have read and agreed to follow the restrictions specified in the YFP database webpage. This database will only be used for research purposes. I will not make any part of this database available to a third party. I'll not sell any part of this database or make any profit from its use.
<your signature>
```
In general, a password will take 3-7 workdays to issue. To avoid problems with our spam filter, make sure that your email is sent from an .edu (or similar) address. Failure to follow the instruction may result in no response. 

Database administrator: qunc85@gmail.com

Prof. Hsu's e-mail: jison@mail.ntust.edu.tw



Restriction
-
To guarantee the proper use of this database, the following restrictions must be followed by any person who has downloaded the database.
 1. All submissions, publications, and works that use or talk about the YFP database must cite the paper. 
 2. Permission is NOT granted to reproduce or distribute the database. 
 3. Written permission must be approved by Prof. Gee-Sern Hsu if a faculty member desires to share the database with her/his co-workers or students. Even then, the database cannot be posted on a webpage accessible from outside the faculty research group. 
 4. No economical profit can be made from this database. 
 
No country or institution is excluded of any of the above restrictions. Failure to follow the restrictions will be legally prosecuted.

Download Link
-
[YFP Download Link](https://drive.google.com/open?id=1D0bMXESiVafB4bSsxi7zPK4hUoPxXDHv)

Citation and Contact
--
If you like our work or find YFP dataset useful, please cite the following paper：
```
@article{hsu2018deep,
  title={Deep hierarchical network with line segment learning for quantitative analysis of facial palsy},
  author={Hsu, Gee-Sern Jison and Kang, Jiunn-Horng and Huang, Wen-Fong},
  journal={IEEE Access},
  year={2018},
}
```
Any suggestion or comment would be valuable. Please send an email to corresponding author (Gee-Sern Hsu) or Database administrator.
