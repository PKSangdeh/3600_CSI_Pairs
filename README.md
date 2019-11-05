O Objective

This test measures the channel gain difference for 3600 users pairs. We have measured 
the average channel gain of users on 2.485 GHz with 5MHz bandwidth. The ultimate goal 
of this test is measuring the statistics of delta_q=norm(strong_ch)^2/norm(weak_ch)^2.
However, the measured gains can be used for a variety of purposes.

O Specs:

+ The center freq. is 2.485 GHz and sampling rate of USRPs is 5MHz.
+ We have used USRP N210 with SBX board.
+ The AP has two antennas and users have a single antenna.

O Deployment

+ The picture of floor plan is available at floor_plan.pdf
+ The AP is fixed at the middle of the floor plan marked by a blue spot.
+ The STA is located at one of 120 different locations marked by red circles.


O Location of the test

+ This test has been conduct at second floor of W. S. Speed building at the University
  of Louisville.


O How to use data:

+ The measured channel pairs are available at pairs.mat. Each column is one pair. The first 
two elements of a column are the CSI of the weak user, and the last two elements are for 
the strong users.

O Report

+ The report shows our objective and the way we conducted the experiment with more details.

# 3600_CSI_Pairs
CSI for 3600 user pairs: two users and one two-antenna BS/AP at 2.4GHz and 5MSps 
