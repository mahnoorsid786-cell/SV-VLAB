# SV-VLAB
LAB 3 TASK 3
| Req. ID | Description                                                                                                                                               | Priority |
| ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| **R1**  | The robot shall remain in **IDLE** state until a delivery request is received.                                                                            | High     |
| **R2**  | When a delivery request is received in **IDLE**, the robot shall enter **NAVIGATING** state.                                                              | High     |
| **R3**  | While **NAVIGATING**, the robot shall continuously monitor its surroundings for obstacles.                                                                | High     |
| **R4**  | When an obstacle is detected during navigation, the robot shall enter **AVOIDING_OBSTACLE** state.                                                        | High     |
| **R5**  | After successfully avoiding an obstacle, the robot shall return to **NAVIGATING** state.                                                                  | High     |
| **R6**  | When the destination is reached, the robot shall enter **DELIVERING** state.                                                                              | High     |
| **R7**  | The robot shall enter **RETURNING** state after the package has been successfully delivered or when the battery becomes critically low during navigation. | High     |
| **R8**  | When the robot reaches the warehouse while **RETURNING**, it shall enter **IDLE** state.                                                                  | High     |
| **R9**  | If the battery becomes critically low during navigation, the robot shall stop the delivery journey and enter **RETURNING** state.                         | High     |
| **R10** | The robot shall not transition directly from **IDLE** or **AVOIDING_OBSTACLE** to **DELIVERING**.                                                         | High     |
