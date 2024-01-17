# Variational Autoencoder for Clothing Image Generation

## Introduction

In this repository, we embarked on the exciting journey of training a Variational Autoencoder (VAE) using a manually collected dataset of clothes. Our dataset includes a diverse collection of clothes, and the ultimate goal is to leverage the trained VAE to generate novel and aesthetically pleasing images of these clothing items.

## Data Collection

Our data collection process was meticulous, ensuring a rich diversity within the dataset. We prioritized capturing various styles, colors, and textures, aiming for a comprehensive representation of clothing items. Each clothing item within the dataset is thoughtfully labeled with a unique class. To augment the dataset size and enhance variability, we incorporated techniques such as rotation, flipping, and adjusting lighting.

## Implementation of Variational Autoencoder

The heart of our project lies in the design of the VAE architecture, meticulously crafting the encoder, sampling layer, and decoder. This thoughtful design is instrumental in facilitating effective learning and the generation of meaningful latent representations, ensuring that the VAE captures the essence of the diverse clothing items in our dataset.

## Generation of Acceptable Images

Post-training, team members can marvel at the fruits of their labor by using the trained VAE to generate fresh images from the latent space. Our success metric is simple but crucial: the generated images must, at a minimum, capture the distinctive shape and features of the clothing items. We anticipate and demand that the generated images accurately represent various styles and details.

## Acceptance Criteria

We've established clear acceptance criteria for the generated images:

- The generated images must capture the distinct shape and features of the clothing items.
- The acceptance criteria emphasize the importance of the generated images accurately representing various styles and details of the clothing items.

## Bonus Achievements

In our pursuit of excellence, we didn't stop at the basics. Here are some bonus features we've proudly incorporated:

1. **Conditional Variational Autoencoder**
   - We went above and beyond by implementing a Conditional Variational Autoencoder. This empowers the model to generate images with a specific class label, offering even more control over the creative process.

2. **GUI Interface with Slider**
   - Elevating user interaction, we implemented a graphical user interface (GUI) featuring a slider. This handy tool allows users to easily determine the number of images they wish to generate. Conveniently, this feature is seamlessly integrated, especially for users on platforms like kaggle or collab.
