# image-stitching
Stitching 2 images to create a wide view
# Brief introduction 

* First we try to match points from both images.to do that we have to use scale invariant feature transform to descibe points.
This is due to the nature of warrping that might change the feature of the point.
* Then we deduce the homography matrix after finding matching point between both images.
* We proceed by warping the image so it can be "stitched" properly creating a panoramic/wide view 
<!-- ![Alt text](./images/disparity.png?raw=true "Title") -->
<!-- ![alt](./images/disparity.png?raw=true "Title") -->
<p align="center">
  <img src="./images/matchingPoints.png"  >
</p>

# Example 1


<p align="center">
  <img src="./images/MountainLeft.png" width="350" title="left image">
  <img src="./images/MountainRight.png" width="350" alt="right image">
</p>

<p align="center">
  <img src="./images/stitchingResults1.png" width="700" title="result">
</p>

# Example 2

<p align="center">
  <img src="./images/Left.png" width="350" title="left image">
  <img src="./images/right.png" width="350" alt="right image">
</p>

<p align="center">
  <img src="./images/stitchingResults2.png" width="700" title="result">
</p>


# Extra resources and ref


* [illinois university lecture](https://courses.engr.illinois.edu/cs498dwh/fa2010/lectures/Lecture%2017%20-%20Photo%20Stitching.pdf)
