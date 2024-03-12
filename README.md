# unet-3dmodel
visualize UNET in 3 dimension with all the layers and connections for adding to Powerpoint presentations and 3d printing

3D UNET Model for Visualization and presentation
![3d model of UNET](/images/Screenshot%202024-03-12%20232941.png)

In this particular model, we have implemented a UNET architecture with the following characteristics:

Four skip connections
One bottleneck layer

To incorporate the 3D UNET model into your PowerPoint presentation, follow these steps:

1.Download the .3mf File: Download the provided file containing the 3D UNET model from the repository.
2.Open PowerPoint: Launch Microsoft PowerPoint and open the presentation where you want to insert the 3D model.

3.Insert the 3D Model: Navigate to the slide where you want to add the 3D UNET model. Then, go to the "Insert" tab and select "3D Models" from the "Illustrations" group. Choose "From File" and select the downloaded .3mf file.

![Insert 3d model in Powerpoint](/images/Screenshot%2024-03-12%234419.png)
4. The model should look like this in the slides:
![Inserted 3d model in Powerpoint](/images/Screenshot%2024-03-12%234419.png)

4.Adjust the Model: Resize and position the 3D model according to your preferences. You can also adjust its orientation and lighting using PowerPoint's 3D model manipulation tool in the centre of the model.
![Insert 3d model in Powerpoint](/images/Screenshot%2024-03-12%234419.png)

5. You can even add morph transition between 2 slides containing the model in different orientation to show a rotating animation
![unet animation](https://github.com/DeepLearningDoctor/unet-3dmodel/assets/140095099/09847241-9bb5-4779-8744-642c9d57c6cc)

6.Present Your Slide: When you present your PowerPoint slide, the 3D UNET model will be displayed, allowing your audience to visualize the architecture of the UNET network in three dimensions.

About UNET
UNET is a convolutional neural network architecture widely used for biomedical image segmentation tasks. It was introduced by Olaf Ronneberger, Philipp Fischer, and Thomas Brox in their paper titled "U-Net: Convolutional Networks for Biomedical Image Segmentation" in 2015. UNET is particularly well-suited for semantic segmentation tasks where the goal is to assign a class label to each pixel in an input image.

The architecture of UNET consists of an encoding path (contracting path) and a decoding path (expansive path). The encoding path captures context information from the input image through a series of convolutional and pooling layers, while the decoding path generates a segmentation map by upsampling and concatenating features from the encoding path through skip connections.

Attribution
This model is free to use for education purpose. If you use this 3D UNET model in your presentations or projects, please provide attribution by mentioning the source in the following format:
Source- DeepLearningDoctor
