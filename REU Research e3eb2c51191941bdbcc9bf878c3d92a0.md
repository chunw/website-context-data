# REU Research

Client: https://www.nsf.gov/
My Role: Researcher
Project Category: Data Platform, Data Website, Data-Intensive
Skills: Algorithmic, Research

### AUTOMATIC DETECTION OF EPILEPTIFORM EVENTS IN EEG RECORDINGS [](https://chunweb.wordpress.com/author/chunjennywang/)

![https://chunweb.files.wordpress.com/2016/06/6922173_orig.png](https://chunweb.files.wordpress.com/2016/06/6922173_orig.png)

An electroencephalogram (EEG) is the most important tool in the diagnosis of seizure disorders. Between seizures, epileptiform neural activities in EEG recordings occur in the forms of spikes or spike-and-slow wave complexes. Seeking for an automated EEG interpretation algorithm that is well-accepted by clinicians has been a research goal stretched for decades. As a participant in an NSF-funded [Research Experience for Undergraduates (REU)](https://en.wikipedia.org/wiki/Research_Experiences_for_Undergraduates) program hosted at Clemson University School of Computing, I continued on this endeavor to develop an automated system that detected epilepsy-related events, in real-time, from scalp EEG recordings.

In finding the optimal algorithm for this purpose, I constructed a multi-stage processing pipeline. In the first stage, I cleaned up the clinic data gathered from 100 epileptic patients and treated them with cross-validation. Next, I used wavelet transformations to generate the features for study from EEG signal in a “sliding window” approach. I then applied machine learning algorithms and analyzed their performances in classifying data patterns into epileptiform activities versus other activities. For this stage I also explored the use of hidden Markov model to fit the time sequence in which epileptiform events occurred. In the final step, I further separated target eplieptiform events from noise signals, by applying a statistical model locally, and stitched outputs from different signal windows together. – [source code](https://github.com/chunw/eegNet-pattern-recognition)

The automation results were highlighted these findings in realtime on the [eegNet](http://eegnet.clemson.edu/) (standardized EEG database developed by Clemson) web interface.

### 📎 **Automatic detection of epileptiform events in EEG recordings** – [poster](http://chunw.github.io/uploads/automated_eeg_detection_poster.pdf)

![Screenshot 2023-03-15 at 5.35.14 PM.png](Screenshot_2023-03-15_at_5.35.14_PM.png)