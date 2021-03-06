# Robust_trajectory_tracking_by_a_multirotor


In this paper, the problem of robust trajectory tracking by a multicopter platform is formulated as a linear-quadratic differential game against unknown external disturbances (nature). The desired trajectory is composed of position and yaw constraint, which is known to be a differentially flat output for multicopter state dynamics. Using this property, a linearized error dynamics is obtained in the vicinity of the nominal states and the nominal control inputs. To avoid singularities, the linearized error dynamics is derived using quaternion representation. Based on it, an optimal saddle point strategy for trajectory tracking is presented, where controller gains are calculated apriori by numerically solving a differential Ricatti equation. A salient feature of this control design is that both the position and the attitude control loops are integrated, and there are only two tuning parameters — one corresponding to the tradeoff between control effort and tracking accuracy and the other corresponding to robustness. Simulations as well as experimental validations are presented to demonstrate the performance and applicability of the controller.

Please see the following video to see the outcome of the trajectory tracking research - 

[![Watch the video](https://img.youtube.com/vi/wwE5pFYG43I/0.jpg)](https://www.youtube.com/watch?v=wwE5pFYG43I)

For more details, please look at the Research_paper_on_multirotor pdf file.
