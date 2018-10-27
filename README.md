# cv
This research is published in IEEE Transactions on Instrumentation and Measurement. The title of paper is Automatic Visual Detection System of Railway Surface Defects With Curvature Filter and Improved Gaussian Mixture Model. 

If you find any useful in your research, please consider citing:
@article{zhang2018automatic,
title={Automatic Visual Detection System of Railway Surface Defects With Curvature Filter and Improved Gaussian Mixture Model},
author={Zhang, Hui and Jin, Xiating and Wu, QM Jonathan and Wang, Yaonan and He, Zhendong and Yang, Yimin},
journal={IEEE Transactions on Instrumentation and Measurement},
volume={67},
number={7},
pages={1593--1608},
year={2018},
publisher={IEEE}
}

#Abstract<br>  
Rails are among the most important components of railway transportation, and real-time defects detection of the railway is an important and challenging task because of intensity inhomogeneity, low contrast, and noise. This paper presents an automatic railway visual detection system (RVDS) for surface defects and focuses on several key issues of RVDS. First, in view of challenges such as complex condition and orbital reflectance inequality, we put forward a region-of-interest detection region extraction algorithm by vertical projection and gray contrast algorithm. In addition, a curvature filter equipped with implicit computing and surface preserving power is studied to eliminate noise and keep only the details. Then, an improved fast and robust Gaussian mixture model based on Markov random field is established for accurate and rapid surface defect segmentation. Additionally, an expectation-maximization algorithm is applied to optimize the parameters. The experimental results demonstrate that the proposed method performs well with both noisy and railway images, which enables identification and segmentation of the defects from rail surface, achieving detection performance with 92% precision and 88.8% recall rate on average, and is robust compared with the related well-established approaches.
Experiment and Analysis
To evaluate the performance of the proposed algorithm, it was implemented in the MATLAB R2017a programming environment on a PC with Intel(R) Core(TM) i5–7200 CPU at 2.50-GHz running Windows 10. The system adopts a DalsaSpyder3 line-scan camera with a resolution of 1024 pixels for image capture. Its maximum line rate is 68 000 lines/s, which can capture a set of frames and finally generates a panorama.
