
# Agricultural Field Boundary Delineation using Unet(CNN) on Sentinel-2 Images with GapLoss and Graph-Based segmentation for Polygonization   

Agricultural Field Boundary (AFB) delineation is beneficial for estimating incentives as part of
farming schemes. AFB delineation can help formulate innovative micro-agricultural finance programs,
agricultural field statistics calculation, crop yield estimation, and other applications of precision
agriculture practice(Enclona et al., 2004). Traditional methods used to monitor AFB are
time-consuming and labor-intensive since they are based on human field surveys. Furthermore,
the diversity of Earth Observation (EO) technology allows for data collection via a wide range of
sensors with varied spatial, spectral, and temporal resolutions. Combined with the recent advancements
in computer vision and machine learning algorithms, it is convenient to perform the delineation
of agricultural field boundaries. Despite the obvious advantages, it is still the abundance of
data created by EO sources can cause a variety of problems in processing. Through this research,
we create a tailoredworkflowthat efficiently delineates the AFB from pre-processed Sentinel-2EO
data built with seasonal statistic-based composites such as geometric median, median, and medoid
with the help of CNN (U-Net) and a post-processing method based on graph-based segmentation
and contour extraction for polygonization of boundary predictions.

# Study Areas Cambodia & Vietnam 
![image](https://github.com/ashikbharishivaprasad/AFB_Delineation/assets/100797850/8581a1f2-b2e6-470f-90d0-695068ceab03)

# Methodology of Research

![image](https://github.com/ashikbharishivaprasad/AFB_Delineation/assets/100797850/824f6480-4084-43f3-b20a-43cc65b43c45)

# Methodology for Graph-Based Segmentation

![image](https://github.com/ashikbharishivaprasad/AFB_Delineation/assets/100797850/3e173a33-d931-413d-bbea-1407693f5081)

# Results of Contour-Loss(Gap Loss) Vs Binary Cross Entropy

![image](https://github.com/ashikbharishivaprasad/AFB_Delineation/assets/100797850/aa5a3bbe-b86e-4224-b094-b30c5520b14f)


![image](https://github.com/ashikbharishivaprasad/AFB_Delineation/assets/100797850/1ed4cafc-2bf9-4382-8313-d81ddd722bd4)

