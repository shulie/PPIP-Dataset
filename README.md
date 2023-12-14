# PPIP-Dataset

**Protect Privacy of Irrelevant People Dataset**.

PPIP is a dataset to better evaluate irrelevant individuals recognition in videos, which includes 64 videos, encompassing diverse ethnicities and scenarios. The dataset not only provides annotated coordinates for **141,932 faces in 23,288 frames** but also considers the relevance of individuals to the video. It annotates **101,685 irrelevant individuals** and **40,247 relevant individuals**, facilitating further research in this field.

Due to **copyright** constraints, we are unable to provide the videos directly. However, we do furnish the specific **web addresses** of the videos, along with the designated time segments. Concurrently, we offer the result of individuals detection within each video segment, accompanied by relevance labels.



## Detail Description

Our data annotation refers to the MOT20 dataset, with the specific format as follows:

**[frame], [id], [bounding_box_left], [bounding_box_top], [bounding_box_width], [bounding_box_height], [3D_x], [3D_y], [3D_z], [relevance_label]**

Relevance label equals 1 for relevant personnel, and 0 for irrelevant personnel.





## Citation

Please cite the following paper if you use our dataset.

*Automated Irrelevant Individuals Recognition Algorithm in Video via Motion Trajectories.*
