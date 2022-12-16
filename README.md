# Color Transfer <img src="https://github.com/AissamDjahnine/Search-Algorithms-in-AI/blob/master/files./Matlab_Logo.png" width="25">

Color Transfer between Images in a correlated colour space ( RGB )

## Getting Started & Prerequisites :

**Matlab Versions and Libraries :** 

* You need a MATLAB license and an install of MATLAB (No Matlab toolboxes should be required for this program). 
           
## Execution & tests

* The main program **ColorTransferDemo** uses :

           function est_im = Color_Transfer_CCS(source,target)

**Arguments :**

- Source Image

- Target Image

**Output :**

- Result Image

**Test folders :**

* Uses some examples files in Example folders : 

           Im_target = imread('Example1/target.jpg');
           Im_source = imread('Example1/source.jpg');
                      
## Test & Results :

**FLower color Transfer :**

Target         |  Source          |      Result        
:-------------:|:----------------:|:-------------------:
<img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./target.jpg" width="250"> |  <img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./source.jpg" width="250"> | <img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./result.jpg" width="250">

**Autumn House color Transfer :**

Target         |  Source          |      Result        
:-------------:|:----------------:|:-------------------:
<img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./target_1.jpg" width="250"> |  <img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./source_1.jpg" width="250"> | <img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./result_1.jpg" width="250">

**Autumn-spring color Transfer :**

Target         |  Source          |      Result        
:-------------:|:----------------:|:-------------------:
<img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./target_2.jpg" width="250"> |  <img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./source_2.jpg" width="250" height="250"> | <img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./result_2.jpg" width="250">

**Joy Garden color Transfer :**

Target         |  Source          |      Result        
:-------------:|:----------------:|:-------------------:
<img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./target_3.jpg" width="250"> |  <img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./source_3.jpg" width="250"> | <img src="https://github.com/AissamDjahnine/ColorTransfer/blob/master/files./result_3.jpg" width="250">
## Documentation & ressources : 

- You can find the article supporting this work in files : [Color Transfer By Aissam Djahnine](https://github.com/AissamDjahnine/ColorTransfer/blob/master/Djahnine_Aissam_Color_Transfer_in_Correlated_color_space.pdf) explaining the color transfer algorithm.
