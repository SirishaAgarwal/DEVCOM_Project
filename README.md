On March 27, 2018, a four-liter bottle of dichloromethane was spilled in a lab at Texas
Tech University. The unnoticed spill exposed researchers to high vapor concentrations, causing
poisoning and hospitalization. This incident emphasizes how dangerous an undetected liquid
spill can be in a controlled environment like a laboratory, which, at its worst, can lead to
containment breaches and life-threatening situations. However, the problem is not confined to
research labs. Unknown liquid and chemical spills are common in manufacturing facilities,
hospitals, military bases, and even public areas. To reduce this risk, this project developed a
prototype liquid-detecting computer vision model. To generate masks, bounding boxes, and
labels, the model used the Mask R-CNN architecture, which extends Faster R-CNN by adding a
parallel mask prediction branch. Using training functions from Meta’s Detectron2 library, the
model was trained for 12,500 iterations at learning rates of 0.01 and 0.001, resulting in a
segmentation mask precision of 45.17 and a bounding box precision of 47.21. The fine-tuned
model detected liquid spills and distinguished them from other objects with moderate accuracy,
underscoring the potential of computer vision as an early-warning system for hazardous spills
and a means to ensure safety.
