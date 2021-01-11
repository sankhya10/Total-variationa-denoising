# Total-variation-denoising
Given an image where a specified region is unknown, image inpainting or image completion is the problem of inferring the image content in this region. Traditional retouching or inpainting is the practice of restoring aged artwork, where damaged or missing portions are repainted based on the surrounding content to approximate the original appearance. In the context of digital images, inpainting is used to restore regions of an image that are corrupted by noise or where the data is missing. Inpainting is also used to solve disocclusion, to estimate the scene behind an obscuring foreground object. A popular use of digital inpainting is object removal, for example, to remove a trashcan that disrupts a scene of otherwise natural beauty. Inpainting is an interpolation problem, filling the unknown region with a condition to agree with the known image on the boundary. A classical solution for such an interpolation is to solve Laplace's equation. However, Laplace's equation is usually unsatisfactory for images since it is overly smooth. It cannot recover a step edge passing through the region. Total variation (TV) regularization is an effective inpainting technique which is capable of recovering sharp edges under some conditions 
