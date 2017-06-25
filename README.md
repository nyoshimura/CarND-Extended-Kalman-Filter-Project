[//]: # (Image References)

[image1]: ./img/test2.png "test_near"
[image2]: ./img/test.png "test_far"

# Extended Kalman Filter Project
#### Self-Driving Car Engineer Nanodegree Program

In this project utilize a kalman filter to estimate the state of a moving object of interest with noisy lidar and radar measurements.
![alt text][image1]

Passing the project requires obtaining RMSE values that are lower that the tolerance outlined in the project [rubric](https://review.udacity.com/#!/rubrics/748/view).

There are 7 criterias:
---

1. My code should compile. (done)
2. px, py, vx, vy output coordinates must have an RMSE <= [.11, .11, 0.52, 0.52] (failed)
3. My Sensor Fusion algorithm follows the general processing flow (done)
4. My Kalman Filter algorithm handles the first measurements appropriately. (not sure)
5. My Kalman Filter algorithm first predicts then updates. (done)
6. My Kalman Filter can handle radar and lidar measurements. (done)
7. My algorithm should avoid unnecessary calculations. (done)

### Remained issue
Kalman filter is implemented and the result looks not bad, but rmse does not meets the requirement. I cannot find the reason now, so please give me any feedback...
