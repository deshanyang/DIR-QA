
The purpose of this datasets is to provide a new and improved set of benchmark landmark pairs with point-to-point correspondences for accurate DIR evaluation.


Disclaimer: This work is heavily based on R. Castillo et al.'s DIRLAB work (www.dir-lab.com). Please cite and give acknowledgement to their work if you found this datasets helpful. 

DIRLAB 4DCT lung images were used. Please refer to www.dir-lab.com  and the references papers for more details.


Note:
  1. Only landmark pair datasets were shared here. Please go to www.dir-lab.com to download original 4DCT datasets.
  2. When use this datasets, note that the first dimension and second dimention were swapped [y, x, z] compared to original DirLab landmark pairs [x, y, z].
  
  EE represents End-Exhalation phase
  EI represents End-Inhalation phase
  
Images below show the procedures and examples of our method:
1. procedures to detect lung feature points
![figure 1](/images/Fig.1.png)
2. Left: 3D rendering of the detected vasculature probability maps, Middle: Sliced vasculature probability maps with detected landmarks, Right: Sliced original CT image with detected landmarks. 
![figure 2](/images/Fig.2.png)
3. Flow chart to establish landmark pair correspondence
![figure 3](/images/Fig.3.png)
4. The MSPS network architecture. A central-surrounding three-stream network uses a siamese type design for each stream
![figure 4](/images/Fig.4.png)
5. The preserved landmark pairs and rejected landmark pairs were plotted within the lung. 
![figure 5](/images/Fig.5.png)
6. Comparison of the 300 DIRLAB landmark pairs (top) to our dense set of landmark pairs (bottom), deformation vectors are color coded by magnitude
![figure 6](/images/Fig.6.png)
7. Left column: landmark at EI phase, middle column: original DIRLAB corresponding landmark at EE phase, right column: corresponding landmark at EE post MSPS refinement
![figure 7](/images/Fig.7.png)



REFERENCENS:
Please cite original dirlab papers and our paper if you found the datasets useful.

1. Automatic large quantity landmark pairs detection in 4DCT lung images (accepted, online link:  https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.13726)
Yabo Fu, Xue Wu, Allan Thomas, Harold H. Li, Deshan Yang*

2. "A framework for evaluation of deformable image registration spatial accuracy using large landmark point sets,"
R. Castillo, E. Castillo, R. Guerra, V.E. Johnson, T. McPhail, A.K. Garg, T. Guerrero, 
Physics in medicine and biology 54 7, 1849-1870 (2009).


If you have any questions, feel free to contact: yangdeshan@wustl.edu  or  fuyabo@gmail.com.
