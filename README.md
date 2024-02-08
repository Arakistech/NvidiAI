# AI Innovation Challenge
**Using Jetson Orin**

From the [data sheet]( https://www.st.com/resource/en/datasheet/iis3dwb.pdf):
The proposed project aims to address the challenge of superficial damage assessment in bridge structures using a combination of UAV image capture and deep learning-based approaches. At present, manual inspection methods, including visual inspection and the use of professional equipment, are the most commonly employed techniques for identifying and evaluating bridge damage. However, these methods are often costly and may be difficult to implement for remote or hard-to-reach structures.



https://github.com/Arakistech/NvidiAI/assets/107245718/072b1fd0-b5a8-4beb-91b1-f1cb236f1b6a


To overcome these limitations, the proposed project utilizes drones equipped with high-resolution cameras to capture images of bridge structures, which are then analysed using a deep neural network-based approach. Specifically, a convolutional neural network (CNN) architecture is employed to classify and locate four categories of damage, including intact, cracked, effloresced, and spalled surfaces, with an accuracy greater than 90%.

Existing CNN-based damage detection methods have not been specifically designed for the identification of multiple damage types in masonry historic structures. Therefore, the proposed project seeks to develop a novel approach that is specifically tailored to the unique challenges associated with inspecting and monitoring these types of structures. The proposed approach will enable engineers to more efficiently and accurately assess the structural health of bridges, ultimately leading to improved safety and reduced maintenance costs.


*IIS3DWB breakout board sitting atop a Dragonfly STM32L476 development board via female pin headers.*
 
An Artificial Intelligence software that automates the laborious structure damage inspection process, which is currently performed manually. With a variety of features, including real-time damage assessment and damage report generation, this tool can help fasten the post-earthquake recovery and assist first responders and policy makers. Defect assessment can be categorized based on its relevance of directly affecting safety, severity, and urgency to address the defect.

This solution is different to others because it will use multirotor https://www.youtube.com/watch?v=X2e5hvAVYRk technology to get maximum stability in order to get as close as possible to the structure to be analysed and obtain both visible and IR irradiance image and multisensory data. 

Thanks to Machine Learning with NVIDIA Jetson, we will be able to provide almost real time alarms to first responders each time that a structural stability threat is detected. 


