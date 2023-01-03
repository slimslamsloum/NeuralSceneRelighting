# NeuralSceneRelighting

This repositery contains work related to my Bachelor Project at EPFL. Please find below indications on where to find what deliverables.

## Report 

The report can be found in project_report.pdf, where the motivation, methods and results of the project can be found.

## PhySG

In this folder can be found the main codebase for the PhySG pipeline. Most of the code was unchanged, but the auto-encoder 
model can be found in codesg_envmap_material.py. Varying the number of Spherical Gaussians used is done in confs_sg\default_conf.

## Mitsuba 

In this folder will be all the work related to the rendering of the ground truth images of the specular component of Hello Kitty. Please refer to 
gt_rendering\rendering_GT.ipynb for the notebook.

## Results

In this folder there are the different results (which contain geometry, specular component, diffuse component, final image) of all our different runs.

## PSNR

In this folder there is the code for the computation of the PSNR metric as well as 6 sets of camera positions with an image for each run, to ease the PSNR computations and
comparisons.
