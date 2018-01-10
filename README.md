# Generate-Human-Faces
Utilizes a generative adversarial network (or GAN) to generate unique human faces. GAN's allow us to generate new images based on prior images, and is made up of two networks that work together: the Generate Network and the Discriminator Network. The generator is trained to produce increasingly more realistic images in order to "fool" the discriminator, which is charged with determining if an image fed to it is real (from the dataset) or fake (from the generator).

## The Data

#### Data Sample:
![alt text](https://github.com/SrahSrah/Generate-Human-Faces/blob/master/Face-gen%20dataset.png)

#### Results:
![alt text](https://github.com/SrahSrah/Generate-Human-Faces/blob/master/Face-gen%20results.png)

## Creating New Human Faces
This was my favorite project thus far. It allowed me to build my own generator and discriminator networks and train them on two datasets to prove its versatility. The generated faces look realistic in nature, even showing a few faces at a slight angle, which is promising. The center rightmost face does admittedly look less human, however, signaling that additional training may be required. 
