# Welcome to the Cloudinary challenge

As part of this challenge you are going to assume the role of a frontend developer who has recently joined a prominent startup in the e-commerce space. After joining the business, you learn that the company is struggling with serving images to their end users in an efficient manner and as such the site has a very high bounce rate (a lot of visitors leave the site, without purchasing anything). This has been identified as a crucial issue and you are now part of the team that is tasked to resolve it.

After a handful of meetings, the main issues have been gathered which are:
- The marketing and design team are overloaded with work to create “web ready’ images - they are tasked with resizing and cropping
- The images are not served in modern formats for the users
- Sometimes the design team needs to create a crop around a particular object or recolour images and they also struggle with automation. For the purposes of this exercise you need to create a crop around the person’s face and for the second image, you will need to recolour the bag. (Currently your company sells brown, black and orange bags)

After doing your research diligently you find a tool called Cloudinary which seems to be able to tick all the necessary boxes based on the requirements set out above.
Now your task is to test out Cloudinary and present your findings to the engineering managers in hopes that this solution will be the one! 

Please note that for this task, you won’t need a Cloudinary account.

## Apply the necessary transformations and optimisations

The requirement is simple. You have the following image URLs that you have to change, in order to achieve the sample outputs.

1st image:
https://res.cloudinary.com/balazs/image/upload/photo-1495366691023-cc4eadcc2d7e_eolq2v.webp

2nd image: 
https://res.cloudinary.com/balazs/image/upload/gabrielle-henderson-IuGQoHIp8LY-unsplash_xv4jr3.jpg

For the first image we need to create a crop around the face of the person in the center, in a 400X400 square, and for the second image we need to recolour the bag, as the company sells three versions but there won’t be time to take photos of those so you must use this one image. (The recolour should be done to both green and gray colors).

Furthermore, we also need to save bandwidth so apply automatic quality optimisation and make sure to serve the image up in a next-gen image format.

Sample output for the transformed images:

Output of the first image:\
![First image output](https://res.cloudinary.com/balazs/image/upload/v1713441346/Cloudinary%20Challenge/photo-1495366691023-cc4eadcc2d7e_eolq2v_rzaekf.webp)

Output of the second image with grey bag:\
![Second image output with grey bag](https://res.cloudinary.com/balazs/image/upload/c_fit,w_400,h_400/v1713441347/Cloudinary%20Challenge/gabrielle-henderson-IuGQoHIp8LY-unsplash_xv4jr3_iyq7a6.jpg)

Output of the second image with green bag:\
![Second image output with green bag](https://res.cloudinary.com/balazs/image/upload/c_fit,w_400,h_400/v1713441346/Cloudinary%20Challenge/gabrielle-henderson-IuGQoHIp8LY-unsplash_xv4jr3-2_dppbes.jpg)


Useful links:
- [Cropping and resizing](https://cloudinary.com/documentation/resizing_and_cropping)
- [Cropping position](https://cloudinary.com/documentation/resizing_and_cropping#example_3_crop_an_image_to_keep_only_the_face)
- [Recolor](https://cloudinary.com/documentation/effects_and_artistic_enhancements#generative_recolor)
- [Optimization](https://cloudinary.com/documentation/image_optimization)

## Submit your work

Go to [this form](https://forms.gle/XAJEgTvKL4tjKh9w8) and add the transformed URLs. Please note that you need to submit both URLs in order to successfully complete the challenge and you need to make sure to add all transformations and optimisations to the final URL so please double check your work before submitting the form


