# shr0ud_kill3r
Generative model to produce optical satellite images from SAR images.

We selected ~12,000 images, evenly distributed over 4 different types of major
terrain/regions. Barren land, further divided into 2 classes, pure barren land and
mixture of barren and urban land; grasslands, further divided into 2 classes, pure
grasslands and a mixture of grasslands and urban areas; grid, which is agricultural
land; and urban land, which are images majorly showing rooftops, roadways, narrow
paths, boundaries etc. This gave us ~2, 000 images per class.

As can be seen from the images, the model learns and generates images with
a smaller number of features (barren land, grassland) easily, but highly complex
images i.e., images with a greater number of features or information per unit area,
such as urban areas and agricultural land, have not been learnt accurately.
