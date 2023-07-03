# Studying the effect of adjacent internal organs with liver cancer on the quality of PET imaging using Monte Carlo simulation method


![pet-ct-scan-imaging-machine](https://github.com/shabnammlatifian1994/pe/assets/136373724/22437583-7c8f-40bf-ae49-3dffb68f2d83)














 Today, with the expansion of engineering science and its integration with medicine, we are witnessing the emergence of advanced devices and equipment that make it easier and more accurate to diagnose or treat a disease. The PET positron emission tomography device is one of these devices that provides a three-dimensional image of the tissue in question to specialists.0 In this study, we examine the shortcomings, the causes of image quality reduction and crystallization in these images, which can be caused by reasons such as the distance traveled by the positron before From the destruction, the effect of other parts of the body adjacent to the target tissue, especially in the case of liver cancer the liver or the amount of radionuclide absorption by cancerous tissue. Here, we trained using a neural network called DEEP-PRC using Monte Carlo simulation tool to correct and reconstruct PET images. The results show that this neural network can correct images up to 95% without Any significant increase in noise will provide 



. Many errors occur in PET imaging that reduce the quality of the image. One of these errors is the drop error, which is well resolved by combining CT imaging technique with PET. Another error is the scattering error of annihilation gammas and occurs when one or both annihilation gammas are scattered inside the body or other parts due to the Compton event. By placing an energy window for PET detectors, this error can be reduced in a favorable way. This research tries to investigate the effect of loss and scattering from the organs adjacent to the liver in the imaging of a liver tumor using the Monte Carlo simulation method and to optimize the energy window in this imaging. 6 were simulated.Before examining the organs adjacent to the liver in order to further investigate the effect of soft tissue on the scattering and loss of annihilation rays, with the help of a simple geometry of soft tissue and considering two types of spatial distribution for the 511keV gamma source, the effect of soft tissue scattering in PET imaging Checked out. The analysis of the results of the simulations in the third chapter shows that the soft tissue around the point source and the spherical volume with a uniform distribution scatter the gamma rays in such a way that their energy loss is low and almost all of them are within the range of the energy window of PET (-550 350 keV are recorded. The soft tissue surrounding both springs at a distance of 8 cm from the center of the spring has the greatest scattering effect in PET imaging.In the fourth chapter, imaging of a liver tumor was simulated by placing a complete human body phantom with a tumor inside the liver (a spherical gamma source with 511keV energy) and placing it inside the PET ring. To investigate the effect of individual internal organs near the liver, the desired tissue was removed from the full body phantom, and the response function of the PET detector in this case was compared with the response function of the PET detector for the full body phantom. The results showed that the stomach has the most negative effect on liver tumor imaging among the examined organs including heart, kidney, lung and intestine.. Examining the results of all the desired tissues on the energy window of the PET detector showed that the effect of scattered rays can be favorably reduced by setting the energy window to 450-550 keV in liver tumor imaging. In the continuation of this investigation, in order to achieve more accuracy, the distribution of radiopharmaceuticals inside the body was also considered in addition to the tumor. Despite the fact that the effect of the loss and dispersion of the organs adjacent to the liver on the destruction gammas is greater in this case compared to the previous case, but the accumulation of the effect of the investigated organs in the detector ring is still in the same range as before.In the fifth chapter, the investigation of braking radiation in PET imaging in soft tissue was discussed. For this purpose, in one step, the 511keV source inside a sphere of soft tissue (in order to investigate the effect of braking radiation of secondary electrons) and in the next step, the source of positron donor 18F inside the same tissue (in order to investigate the effect of braking radiation of positrons) inside the PET detector ring. it placed. Analysis of the results shows that the bremsstrahlung radiation caused by secondary electrons does not have an effect on the imaging due to being outside the energy window.but on the other hand, the bremsstrahlung radiation caused by positrons causes a slight change in the counts throughout the energy window range, whose adverse effect on image quality can be appropriately reduced by reducing the energy window to 417-550 keV. In the sixth chapter, the scattering effect of annihilation gammas between PET ring detectors was investigated. For this purpose, each PET ring detector was insulated in the simulation so that the gamma ray scattered from a A detector cannot enter another detector. The results showed that the separation of PET ring detectors reduces the number of detectors in the range of the energy window, especially near its lower threshold. This decrease in count was reduced in the presence of a sphere of soft body tissue.









![cancers-15-01975-g002](https://github.com/shabnammlatifian1994/pe/assets/136373724/04bbe7bf-496b-4431-bb32-39243f2534e3)








 Positron emission tomography (PET) is a molecular imaging technique that provides a 3D
image of functional processes in the body in vivo. Some of the radionuclides proposed for PET imaging emit high-energy positrons, which travel some distance before they annihilate (positron range),
creating significant blurring in the reconstructed images. Their large positron range compromises the
achievable spatial resolution of the system, which is more significant when using high-resolution
scanners designed for the imaging of small animals. In this work, we trained a deep neural network
named Deep-PRC to correct PET images for positron range effects. Deep-PRC was trained with
modeled cases using a realistic Monte Carlo simulation tool that considers the positron energy
distribution and the materials and tissues it propagates into. Quantification of the reconstructed PET
images corrected with Deep-PRC showed that it was able to restore the images by up to 95% without
any significant noise increase. The proposed method, which is accessible via Github, can provide an
accurate positron range correction in a few seconds for a typical PET acquisition.


![POS2](https://github.com/shabnammlatifian1994/pe/assets/136373724/8fb43a20-4ee8-4ca8-8bdd-275f81d1d117)











----------my link of videos that i have explained about my main article---------------



1--https://drive.google.com/file/d/1r7Zweb6VdDOWChB4qBmFgM2k8iv6yw73/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/d517aa27-b74e-4887-975d-9e79d1801705)


2--https://drive.google.com/file/d/1yeSWJKHcJx9Cn49gnCZPId2Z6-DRIVK5/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/0c566689-5c6a-450c-aa7a-482d4dd86f03)

3--https://drive.google.com/file/d/1t03lZGCb0ZGu9n_sxx3w-qv7TN83hK2U/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/5160ddab-23c1-4081-b259-6a71cd0d7173)


4--https://drive.google.com/file/d/1AI7Jy-YUsGQCb1J9Nne9gNMmDCBJc0q3/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/e5f6d029-7a7c-41e2-b98a-6d2cb626e7e2)

5--https://drive.google.com/file/d/1VPNuBoVDwCjOi5na6U98hJAVDfojUTd_/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/1736b9dd-c7b0-4d5c-83a0-eada5c746491)

6--https://drive.google.com/file/d/1KfC0p39Pbcc9_J2EvW889WF3PeNaLvUc/view
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/d1af51b0-2044-4075-bf65-8e7e430bb1d8)

7--https://drive.google.com/file/d/1L7oGGHYxHFOyJLrzIR1jKcVIIR_v_2yB/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/75c94e95-c36b-49d3-9471-ea18d441df80)

8--https://drive.google.com/file/d/1Q-ao3wwqdIqASVuzpZ73of8Hp6NT9dGX/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/5510c3f4-7f03-456e-a4c9-4f2048807d52)

9--https://drive.google.com/file/d/1aSPWRqFgOWdSeMoKZHIGTDjluuQiCa3s/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/c3a6b845-8aa8-4b57-ae37-25c89c006d99)

10--https://drive.google.com/file/d/1FeNGkCxkW9IeXFs0_MUW9Vukf804oOXU/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/5473dd20-81ad-4c6d-8b26-3100524318a9)

11--https://drive.google.com/file/d/1LiucsIhv8_BlhRhtr1Doqnu54P6L9Oxa/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/b2ec3454-041f-43e6-bd05-7a744a73c26d)

12--https://drive.google.com/file/d/1qOSmJiBQUdGckiGRzZrQ3elzCkzP6_c7/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/4905e6f4-d5c5-43ea-8627-539981bd1217)

13--https://drive.google.com/file/d/1Igm7cM03d-MHRrnW0ugxnCxfL7ObBbJG/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/fe963e05-7c35-418f-ad2c-14c6dc7af9d0)

14--https://drive.google.com/file/d/1GRZa37Xz_mCPU96JNFj9oidnl67Q2uLX/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/a9afd684-262b-4132-9aef-cb2456b18298)

15--https://drive.google.com/file/d/1WlGjTq6Se1kypoje64sAYEoyBJVJDGSx/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/424ad27c-956a-40db-b447-54c78375127c)

---------------------the link of my videos about my proposal-----------------

https://drive.google.com/file/d/12nFYPvBILieD7J1y1IY6pAqcBNorp_6Q/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/e71fef81-1e23-45e2-b1b8-796b104ac7c6)

------------------------the link of my video about the impact factor of my main article---------
https://drive.google.com/file/d/1y0NQRD4CKhcppf44b2JIbmGs8CvH9byC/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/1b4891c8-2fda-4b15-b555-81810116d949)










--------------------the link of my video about my article base on my main article----------------








1--https://drive.google.com/file/d/1tSeHA4zKySb7lAe7J33nwEf-wj3XeaZX/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/6a607276-b3a9-4ab7-9758-308654614f43)

2--https://drive.google.com/file/d/1BvR7zpkLPO-lUFJtnknZFC7shmb_Olbh/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/de323906-9934-4010-b178-290588d931d0)

3--https://drive.google.com/file/d/16tAJSbxThCDRLZ_XflSb7CAfPO9gD6QR/view?usp=drive_web

![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/1c2e106e-5657-4ea4-9cea-1118689f96a6)

4--https://drive.google.com/file/d/1g1cUAGmPMC6Ee9_PJkdRq8GtOWSxNVHh/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/dc1d1fcc-c3c6-4a89-95de-f3356e6d9503)


5--https://drive.google.com/file/d/15dnM06-HRBBbrjNFZtuUWHZj6WGUrB8N/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/4f307385-ea8c-4848-8329-301f11bca3f4)


6--https://drive.google.com/file/d/1C7iCimFLZ8IopLeHNZQMxrrzL3SVkRhi/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/4e954a9f-273d-4c42-a499-d4e7e398c7b8)


7--https://drive.google.com/file/d/1vn47YNJTGpL__1c6ZiHzqt1nz2LqZ1Zs/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/c3fd3d2a-f44c-42b2-8c34-9593424edbf4)

---------------------the link of my videos about my Project defense-----------------


1--https://drive.google.com/file/d/15agojCgy3uVGLNd_WUgf8v_nL9yevmQQ/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/0848aa41-bdc9-4cfb-a76c-9fbd664713e1)


2--https://drive.google.com/file/d/1Tb9vvNgC6STRTCYcTcPlMJHEAJTvZGZY/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/752d279c-4d79-4390-b166-99b1fab6db09)


3--https://drive.google.com/file/d/1dJuCI5ZpZY1sc04Jf6GI08UVtNjSWkuY/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/3c4ff139-6e20-4e07-9ef0-a24b67f66bc7)
)

4--https://drive.google.com/file/d/1KjUgrGeDnQ3o_Gee639eVU5Jnq3WUQmK/view?usp=drive_web
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/66d730bb-db80-4410-8e93-6c79c480ebfb)


5--https://mail.google.com/mail/u/0?ui=2&ik=08742abf19&attid=0.1&permmsgid=msg-a:r-5577031429781230989&th=18866c2ca8651888&view=att&disp=safe&realattid=f_li8m7e5w0
![image](https://github.com/shabnammlatifian1994/pe/assets/136373724/2124f9b9-f230-4134-b637-b4c32a88ed82)







--------------------------the code of this project  is available in this account---------------------

e: https://github.com/jlherraiz/deepPRC

----------------------The source code and some training data are available in-------------------------------------

https://www.mdpi.com/journal/applsci/special_issues/pet_imaging

https://github.com/jlherraiz/deepPRC

-----------------------------you can whatch all of code in this place------------------

https://github.com/jlherraiz/deepPRC/commit/66b9b04c79f7c2111dd4fecaade3ffc0fdd01bee

---------you can whatch it in google colab-------------------

https://colab.research.google.com/github/jlherraiz/deepPRC/blob/main/PRC_GFN_UCM_UNET-3D_PATCH_FULLY3D.ipynb





-----------------You can find the compatibility matrix in TensorFlow Addon's readme:----------------------



https://github.com/tensorflow/addons


----------the link of my video about my source code in this project---------------------


https://drive.google.com/file/d/17sLsxGe7fmkFA2qoID_1NQeZhUDdrYyF/view?usp=drive_link

![image](https://github.com/mahdeslami11/pe/assets/136373724/3a97fcf7-95f9-413d-bc2d-f617e993e6d5)





tnx all of you 

shabnam latifian 40114140111002































