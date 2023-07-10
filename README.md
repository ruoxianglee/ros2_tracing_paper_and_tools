# ros2_performance_evaluation

- [iRobot Framework](https://github.com/irobot-ros/ros2-performance)
- [ROS2 Performance](https://github.com/nobleo/ros2_performance)
- [ROS2 Real-time Benchmark](https://ros-realtime.github.io/ros2_realtime_benchmarks/index.html)

- Maruyama, Yuya, Shinpei Kato, and Takuya Azumi. "**Exploring the performance of ROS2.**" Proceedings of the 13th International Conference on Embedded Software. 2016. [PDF](https://web.ics.purdue.edu/~rvoyles/Classes/ROS_MFET642/Maruyama.ExploringROS2.2016.pdf)
- Kronauer, Tobias, Joshwa Pohlmann, Maximilian Matthé, Till Smejkal, and Gerhard Fettweis. "**Latency analysis of ROS2 multi-node systems.**" In 2021 IEEE International Conference on Multisensor Fusion and Integration for Intelligent Systems (MFI), pp. 1-7. IEEE, 2021. [PDF](https://www.barkhauseninstitut.org/fileadmin/user_upload/Publikationen/2021/2021_Kronauer_Latency.pdf)
- Peeck, Jonas, Johannes Schlatow, and Rolf Ernst. "**Online latency monitoring of time-sensitive event chains in safety-critical applications.**" 2021 Design, Automation & Test in Europe Conference & Exhibition (DATE). IEEE, 2021. [PDF](https://leopard.tu-braunschweig.de/servlets/MCRFileNodeServlet/dbbs_derivate_00047947/techreport_monitoring.pdf)


### ros2_tracing (based on [LTTng](https://lttng.org/docs/v2.13/) see also [this](https://lttng.org/man/7/lttng-concepts/v2.13/#doc-_description))
- Bédard, Christophe, Ingo Lütkebohle, and Michel Dagenais. "**ros2_tracing: Multipurpose low-overhead framework for real-time tracing of ROS 2.**" IEEE Robotics and Automation Letters 7.3 (2022): 6511-6518. [Code](https://github.com/ros2/ros2_tracing), [PDF](https://arxiv.org/pdf/2201.00393.pdf)
- Lajoie, Pierre-Yves, Christophe Bédard, and Giovanni Beltrame. "**Analyze, Debug, Optimize: Real-Time Tracing for Perception and Mapping Systems in ROS 2.**" arXiv preprint arXiv:2204.11778 (2022). [Code](https://github.com/christophebedard/ros2-message-flow-analysis), [PDF](https://arxiv.org/pdf/2204.11778.pdf)
- Bédard, Christophe, Pierre-Yves Lajoie, Giovanni Beltrame, and Michel Dagenais. "**Message flow analysis with complex causal links for distributed ROS 2 systems.**" Robotics and Autonomous Systems 161 (2023): 104361. [Code](https://github.com/christophebedard/ros2-message-flow-analysis), [PDF](https://arxiv.org/pdf/2204.10208.pdf)

### ros2_tracing & Convolution Integral
- Li, Zihang, Atsushi Hasegawa, and Takuya Azumi. "**Autoware_Perf: A tracing and performance analysis framework for ROS 2 applications.**" Journal of Systems Architecture 123 (2022): 102341. [PDF](https://pdf.sciencedirectassets.com/271017/1-s2.0-S1383762121X00112/1-s2.0-S1383762121002344/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJGMEQCIBFrJg8hkuEDY8mGst8O8MLlW5Z68uMsRUJtVoxYC09BAiBKpe1yZHILynsMFPXkNhXvKYxuomxXp2txZFqnLB4G8iqyBQgQEAUaDDA1OTAwMzU0Njg2NSIMAChLo69THZrDsJ%2FOKo8F6ciCQLai8v6%2F0lOKrhiokWfdGWVixuTGXvGLS358DXLyBVg4ze5i1u4tyYaC4veoTGkQewQlpEem0vp4bD6BR5euJh9HlPzsWzGqr7k%2BR%2FEKzoSkJK46g4PaXXl%2FFm071nD2gX3cF3VqFM9t3OzsKUxPrL3ta0CsTQyrLg3K3kLwGk%2BMv27tyv2y6u%2Fp6v62iscAaMerbe8a%2BA8v1XSHaM8qr8VQKzUjUB0V7kdXxmX4hWS8WmZBI%2FpxYqmKI9dHBljr1uMFrjI2QnufJevTrw1drpN1FxBr2%2B%2FS1JPbRV5J9bMcMEqzJST31SW00%2FTDqKurBAoZfBtAVS0zoQFU%2BzvxPIKY4rbDW%2Bi1C%2F16jU72RDyQrDMG%2Fr%2F2WW8qsj00QKUOd%2B5kJ46Qs4h13wAmRPRGFMelu5%2Bhgjqpeo3wj3Dwf3HuPi1qbhJnRLj6HZ1eplDh0TK%2BQ%2BAxN5wD%2BKDWpGbycwlGnJXV0J1a1GVQHPhvXi4Tw5KXyIWUZZAVawXA%2F1%2FpAxygy3HVSaVD6h%2BysJIxAi%2FbhE31hbF0lyaFFXDcc1%2BF5I5YM05lzIm4XSOSzajAvmyxbfuOlnygg2EDHKyPxVEWwbu2P4x6DLMwtaofVBUrS6aNL8ElpwcgKmE61elfVvcbvK3mkUW%2Fsavd97LmH9Ya1qCK31EDDNnqHK7vtZaqAc%2B0tIIlBTcDAPUNql9pRxufM%2FZMUqS7CZY3gQUNQfnP7dPy34jxJi2wVZ0dNHEQ0zxhNPUwyNpqp1NAaKw%2FfvM%2BXqYTzs7DMD2M6yXxidIMxbjCNwrLTegTdwwIYMHL9K%2BmcLX10SZ33TGBL4lBmT0DIZz0WQ2xCD6tD1BLoggO1yJDPgnY6rUXzTC2gY%2BlBjqyATsYXyZuemBjvlFPyZ1IVonh%2BLr2RWvLNbrBpXyjfFFN%2FQdiiHfQKDejHSPMHMT5k0X3LOdjCbJ3NNAxjCadQnXTY1UzGVrFISwj%2BElCUXsFg6CmrKGUc2a2teq8G9CMUs8Z6Wkw254cpy9r2vyJTHAC%2Fs6yoMYXZWn3pKW4gXuVjS7x5mka4EcLNg6LAj1DcZplaJ5Xhi1akreE1uw2QjFqv82d6WrA%2B9qkEfh551ke%2BDQ%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230704T074247Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYUXGZKJOJ%2F20230704%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=4dad132368e5f38c3172d5c2a519113d059f7405adc0502abe957b0126862072&hash=741a1bb41038867ee0d8ec4091e6f273d1468eee1919514eb36df62711d5ad2e&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S1383762121002344&tid=spdf-120ae24e-1257-4ce7-b139-d18e0af947bc&sid=15354a76866ab94c8c191004f1663ec3695egxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=1204560a5e5b0404025e&rr=7e15bbc86e5604c5&cc=hk)
  
  <img width="400" alt="截屏2023-07-04 18 18 47" src="https://github.com/ruoxianglee/ros2_performance_evaluation/assets/36948139/8bb18484-9b3a-4003-b79a-9136d01ddedf">

### ros2_tracing & Clang-based Static Code Analysis
- Betz, Tobias, Maximilian Schmeller, Andreas Korb, and Johannes Betz. "**Latency Measurement for Autonomous Driving Software Using Data Flow Extraction.**" [Code](https://github.com/TUM-AVS/ros2_latency_analysis), [PDF](https://www.researchgate.net/profile/Tobias_Betz4/publication/371576750_Latency_Measurement_for_Autonomous_Driving_Software_Using_Data_Flow_Extraction/links/648ae767712bd8296223e06f/Latency-Measurement-for-Autonomous-Driving-Software-Using-Data-Flow-Extraction.pdf)
- Betz, Tobias, Phillip Karle, Frederik Werner, and Johannes Betz. "**An Analysis of Software Latency for a High-Speed Autonomous Race Car—A Case Study in the Indy Autonomous Challenge.**" SAE International Journal of Connected and Automated Vehicles 6, no. 12-06-03-0018 (2023). [PDF](https://www.researchgate.net/profile/Tobias_Betz4/publication/368369298_An_Analysis_of_Software_Latency_for_a_High-Speed_Autonomous_Race_Car-A_Case_Study_in_the_Indy_Autonomous_Challenge/links/63e6694cc002331f726b9051/An-Analysis-of-Software-Latency-for-a-High-Speed-Autonomous-Race-Car-A-Case-Study-in-the-Indy-Autonomous-Challenge.pdf)

### CARET
- Kuboichi, Takahisa, Atsushi Hasegawa, Bo Peng, Keita Miura, Kenji Funaoka, Shinpei Kato, and Takuya Azumi. "**CARET: Chain-Aware ROS 2 Evaluation Tool.**" In 2022 IEEE 20th International Conference on Embedded and Ubiquitous Computing (EUC), pp. 1-8. IEEE, 2022. [Code](https://github.com/tier4/CARET), [Library to add tracepoints for CARET](https://github.com/tier4/CARET_trace/tree/main), [Homepage](https://tier4.github.io/CARET_doc/refs-tags-v0.4.11/), [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10086380), [Slides](http://download.ros.org/downloads/roscon/2022/Chain-Aware%20ROS%20Evaluation%20Tool%20(CARET).pdf)
  
  <img width="600" alt="截屏2023-07-04 18 20 29" src="https://github.com/ruoxianglee/ros2_performance_evaluation/assets/36948139/5ad27a50-fe95-4d9e-85b2-9188b5da3f9a">

- Peng, Bo, Atsushi Hasegawa, and Takuya Azumi. "**Scheduling performance evaluation framework for ros 2 applications.**" 2022 IEEE 24th Int Conf on High Performance Computing & Communications; 8th Int Conf on Data Science & Systems; 20th Int Conf on Smart City; 8th Int Conf on Dependability in Sensor, Cloud & Big Data Systems & Application (HPCC/DSS/SmartCity/DependSys). IEEE, 2022.

## ROS 1
- [H(igh) A(ssurance) ROS - Static analysis of ROS application code](https://github.com/git-afsantos/haros)

  <img width="400" alt="image" src="https://github.com/ruoxianglee/ros2_performance_evaluation/assets/36948139/b629c10b-87ef-479e-bec7-c3a70d370e49">

- [ros_test_generator](https://github.com/tecnalia-advancedmanufacturing-robotics/ros_test_generator)
- [rostest](https://github.com/tecnalia-advancedmanufacturing-robotics/rostest_node_interface_validation)
