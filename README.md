# New_Pokemon_Generation_GANs
Highlights:
*1)Making Use Of a GAN Structure to generate entirely new pokemon faces using an existing pokemon dataset downloaded from kaggle
*2)The Generator in the GAN Network uses a sequential layers of Conv2dtranspose which is reverse of convolution and it generates an 3*64*64 fake image from an initial random 128*1*1 tensor
3)The Discriminator which gets the fake images compares it with the set of original images and displays it to be real or fake it uses a CNN Architecture which ends with a binary classification layer.
4)Thus The generator is optimized the fake images to "fool" the discriminator and the discriminator also is optimized i.e both keep getting better and better
5)At the end of 40 epochs an entirely new pokemon images are generated
6)As of current current the visual clarity is still low and am seeking to get a better images by tuning the hyperparameters
