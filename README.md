[//]: # (Image References)

[image1]: ./img/test2.png "test_near"
[image2]: ./img/test.png "test_far"
[image3]: ./img/result.png "2nd submission"

# Extended Kalman Filter Project
#### Self-Driving Car Engineer Nanodegree Program

In this project utilize a kalman filter to estimate the state of a moving object of interest with noisy lidar and radar measurements
![alt text][image3]

Passing the project requires obtaining RMSE values that are lower that the tolerance outlined in the project [rubric](https://review.udacity.com/#!/rubrics/748/view).

There are 7 criterias:
---

1. My code should compile. (done)
2. px, py, vx, vy output coordinates must have an RMSE <= [.11, .11, 0.52, 0.52] (done)
3. My Sensor Fusion algorithm follows the general processing flow (done)
4. My Kalman Filter algorithm handles the first measurements appropriately. (done)
5. My Kalman Filter algorithm first predicts then updates. (done)
6. My Kalman Filter can handle radar and lidar measurements. (done)
7. My algorithm should avoid unnecessary calculations. (done)

### Changed part
At 4, I forgot to initialize H_laser_, so I added. Then RMSE is drastically improved, and 2 is satisfied. As you can see in the above figure, RMSE is:
```
X: 0.0974 < 0.11
Y: 0.0855 < 0.11
VX: 0.4663 < 0.52
VY: 0.4729 < 0.52
```
