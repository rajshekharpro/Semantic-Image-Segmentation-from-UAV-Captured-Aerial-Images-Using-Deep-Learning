# Semantic-Image-Segmentation-from-UAV-Captured-Aerial-Images-Using-Deep-Learning

#Abstract


Unmanned aerial vehicle (UAV)-captured aerial images have great potential to support
various applications, such as smart urban planning, terrain classification, vegetation
detection, agriculture planning, and environmental surveillance. Semantic image
segmentation, a task that assigns a class label to each pixel in an image, plays a vital
role in these applications. However, existing deep learning-based segmentation models are
often computationally expensive and require a large number of parameters, making them
unsuitable for real-time deployment on edge devices.This research thesis suggests Attention
based LW-AerialSegNet, a lightweight convolutional neural network (CNN) architecture.
for semantic image segmentation of UAV-captured aerial images. LW-AerialSegNet
employs a dense module inspired design to preserve the network’s feed-forward nature and
mitigate the vanishing gradient problem. Additionally, it makes use of Attention based
model and depth-wise separable convolutions to lower the model’s parameter count and
boost its effectiveness. LW-AerialSegNet is evaluated on two UAV image datasets: the
Urban Drone Dataset (UDD) and the NITRDrone Dataset. It achieves an intersection
over union (IoU) of 74% and 88% on UDD and NITRDrone, respectively, outperforming
state-of-the-art methods. Moreover, the experimental results demonstrate that implementing
depth-wise dilated separable convolutions significantly reduces the number of trainable
parameters, without compromising the model’s accuracy. LW-AerialSegNet’s lightweight
and efficient design makes it suitable for real-time deployment on edge devices, such as
UAVs. This can enable various real-life applications, such as vegetation detection and
road-line extraction for urban mapping and agricultural land planning.
Keywords: Convolutional neural network (CNN); depth-wise dilated separable
convolution (DDC); Attention Architecture; Unmanned aerial vehicle (UAV); Deep
learning; Semantic segmentation; Urban mapping.
