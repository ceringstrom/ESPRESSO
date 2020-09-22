# ESPRESSO
Entropy and ShaPe awaRe timE-Series SegmentatiOn for processing heterogeneous sensor data

Shohreh Deldari, Daniel V. Smith, Amin Sadri, Flora D. Salim

Link to the paper : https://arxiv.org/abs/2008.03230

Presented at UbiComp/ISWC 2020 : [Teaser](https://www.youtube.com/watch?v=na4Cuh4Egko) ,  [Presentation](https://www.youtube.com/watch?v=caXP8WdEAS8)

## Source code
Source code is availabe in Matlab. Also the Python version of ESPRESSO will be available soon.

## Abstract
Extracting informative and meaningful temporal segments from high-dimensional wearable sensor data, smart devices, or IoTdata is a vital preprocessing step in applications such as Human Activity Recognition (HAR), trajectory prediction, gesture recognition, and lifelogging. In this paper, we propose ESPRESSO (Entropy and ShaPe awaRe timE-Series SegmentatiOn), a hybrid segmentation model for multi-dimensional time-series that is formulated to exploit the entropy and temporal shape properties of time-series. ESPRESSO differs from existing methods that focus upon particular statistical or temporal properties of time-series exclusively. As part of model development, a novel temporal representation of time-series was introduced along with a greedy search approach that estimate segments based upon the entropy metric. ESPRESSO was shown to offer superior performance to four state-of-the-art methods across seven public datasets of wearable and wear-free sensing. In addition, we undertake a deeper investigation of these datasets to understand how ESPRESSO and its constituent methods perform with respect to different dataset characteristics. Finally, we provide two interesting case-studies to show how applying ESPRESSO can assist in inferring daily activity routines and the emotional state of humans.



# Bibtex
If you find this code or the paper useful, please consider citing:

          
    @inproceedings{deldari2020espresso,
        title={Entropy and ShaPe awaRe timE-Series SegmentatiOn for processing heterogeneous sensor data}, 
        author={Deldari, Shohreh and Smith, Daniel V. and Sadri, Amin and Salim, Flora D. },
        journal={Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT)},
        volume={4},
        number={3},
        articleno={77},
        year={2020},
        url = {https://doi.org/10.1145/3411832},
        doi = {10.1145/3411832}
    }

    
