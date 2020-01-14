# YouTube-Facial-Palsy-Database ([Website](https://sites.google.com/view/yfp-database/))

By Gee-Sern Jison Hsu, Jiunn-Horng Kang, Wen-Fong Huang

YouTubeFacial Palsy (YFP) database, which is the first public database that we made for the study on the visual inspection of facial palsy symptoms. It contains 32 video clips of 22 facial palsy patients collected from YouTube. We convert the videos into sequences of images, and have the images labeled by facial palsy clinicians.As the number of patients is limited, we adopt the Leave-One-Person-Out (LOPO) protocol for performance evaluation.

The patient in each video speaks to the camera and the camera records the facial expression variation across time. Depending on different patients at different time of recording, some images show the syndrome of the palsy-caused deformation with high intensity and some with median or low intensity, justified by the severity revealed by the deformation pattern. Then images with very low intensity may appear similar to a normal face, and in some cases, even the clinician can hardly tell whether the face is with the palsy syndrome if only looking at one single image without referencing other frames. For some patients, the palsy-induced facial asymmetry is easy to observe even when the patient stops talking and keeps neutral in the expression

- 32 videos of 21 patients from YouTube, and  a few patients have multiple videos.
- As the shortest facial palsy session lasts for a second, we convert each video into an image sequence with 6FPS;
- Manually labeled local palsy regions when the deformation intensity was considered sufficiently high by clinicians. 
- The palsy regions were labeled by three independent clinicians, and we used the intersection of the independently cropped regions as the ground truth.
- We labeled the intensity observed in each palsy region as 0.5 for low or 1.0 for high.
- In addition to the syndrome intensity, we also labeled the palsy regions into Classes Eyes or Mouth. 

We hope that the YouTube Facial Palsy (YFP) Database could revolutionized the landscape of facial palsy research. A detailed introduction of YFP can be found in the [paper](https://ieeexplore.ieee.org/document/8558494).

Here are some examples from the dataset.
