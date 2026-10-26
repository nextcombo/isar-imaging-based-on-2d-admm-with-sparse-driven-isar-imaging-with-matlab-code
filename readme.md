# ISAR Imaging based on 2D ADMM with Sparse Driven ISAR Imaging [with MATLAB Code]

Introduction 
Inverse Synthetic Aperture Radar (ISAR) is an effective signal processing tool capable of acquiring high-resolution images of moving targets throughout the day and night. The Accounting Standards Committee has widely applied ISAR in various military and civilian applications, including target recognition and classification, as well as air/space surveillance [1], [2]. To obtain high-resolution ISAR images in both range and cross-range directions, respectively, broadband signals and long coherent processing intervals (CPI) are required. However, with the increase in radar bandwidth and CPI, the data volume also significantly increases, posing significant challenges to the data acquisition and storage systems. On the other hand, under long CPI conditions, the assumption that targets rotate at a constant rate does not hold true, which leads to a degradation in the quality of ISAR images obtained by traditional range-Doppler algorithms (RDA).
Compressed Sensing (CS) is a novel technique in signal processing that can reliably reconstruct high-dimensional unknown sparse or compressible signals from limited measurements with overwhelming probability, by solving optimization problems driven by sparse drivers [3]-[6]. Due to the inherent sparsity of Inverse Synthetic Aperture Radar (ISAR) images, CS has been extensively developed and applied in radar imaging, achieving high-resolution images even with limited measurements [7]-[13]. In [7], a method based on CS was proposed for achieving high-resolution pulses. The problem of ISAR imaging also considered the impact of incomplete data on CS in [9]. The issue of sparse vector recovery can be addressed through several methods, including basis pursuit [14], matching pursuit [15], and smooth L0 (SL 0) [16]. Although these methods cannot be directly applied to solve sparse matrices, a 2D-SL 0 algorithm has been introduced in [17] which can be directly applied to 2D signals. Based on the 2D-SL 0, a 2D Compressed Sensing (2D-CS) algorithm for high-resolution ISAR imaging was proposed in [10]. In [11], a Gradient Projection Sequence One-Order Negative Exponent (GP-SOONE) method was introduced to solve constrained non-convex problems and reconstruct sparse signals. This method has been further developed for matrix recovery, and the 2D-GP-SOONE algorithm has been used for high-resolution ISAR imaging of maneuvering targets [12]-[13].
The Alternating Direction Method of Multipliers (ADMM) is an approximate splitting algorithm that can solve non-smooth and large-scale optimization problems [18]-[20]. ADMM uses auxiliary variables and divides the problem into separate convex subproblems, which are easily solvable based on proximity operators. On this basis, a one-dimensional ADMM (1D-ADMM) ISAR imaging method was first proposed, followed by a generalized two-dimensional ADMM (2D-ADMM) algorithm that directly reconstructs sparse matrices. The proposed 2D method has lower computational complexity compared to the 1D-ADMM method and requires less memory storage for computation. Moreover, the 2D-ADMM is more robust to noise than the 2D-SL 0 and 2D-GP-SOONE algorithms. This paper also proposes a two-dimensional inverse synthetic aperture radar image reconstruction algorithm based on distance-weighted and cross-correlation data. Simulation results and real measurement data from the Yak 42 aircraft validate the effectiveness of the algorithm under both full sampling and undersampling conditions.
Figure Caption:
MATLAB Simulation Results
Conclusion:
This paper introduces a two-dimensional ADMM method for sparse matrix recovery and high-resolution ISAR imaging, which has higher computational efficiency and lower computational memory requirements compared to solving 1D optimization problems. In addition, compared to 2D-FFT, 2D-GP-SOONE, and 2D-SL 0, the performance of this method improves under different signal-to-noise ratios and undersampling rates. Theoretical analysis and real-world results indicate that the method is reliable and superior. However, phase errors were not considered in this work. Therefore, future work will focus on developing automatic focusing algorithms for ISAR.

## Images

![(ISAR Imaging)Sparse-Driven ISAR Imaging Based on 2D ADMM [with MATLAB Code]](01.jpg)
![(ISAR Imaging)Sparse-Driven ISAR Imaging Based on 2D ADMM [with MATLAB Code]](02.jpg)
![(ISAR Imaging)Sparse-Driven ISAR Imaging Based on 2D ADMM [with MATLAB Code]](03.jpg)
![(ISAR Imaging)Sparse-Driven ISAR Imaging Based on 2D ADMM [with MATLAB Code]](04.jpg)
![(ISAR Imaging)Sparse-Driven ISAR Imaging Based on 2D ADMM [with MATLAB Code]](05.jpg)
![(ISAR Imaging)Sparse-Driven ISAR Imaging Based on 2D ADMM [with MATLAB Code]](06.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
