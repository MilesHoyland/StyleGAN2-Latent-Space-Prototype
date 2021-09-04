# StyleGAN2-Latent-Space-Prototype

This project pipelines the creation of a video render of specified latent code 'positions' within the latent space of pre-trained stylegan2 models. 

The project starts by generating a set of latent code seeds from a pre-trained network, to then allow a user to select a set of desired seeds to transition between in the final render.

Once desired locations have been collated transitional lengths can be defined in terms of frames between latent positions. 

The transitions are then carried out through collation of a container of calculated interpolations from seed to seed. 

The processed data is then a collection of transitioned seeds that is fed into the StyleGAN2 networks generator to create the generated image of each frame. 
A final video render is then created from the set of frames.


The code can be found within the python notebook included wihtin the repository.


As the original prototype was developed as an aid for creating music videos of latent space exploations, two provided example videos of outcomes can be seen at the following links:

https://www.youtube.com/watch?v=asWtEElDVRA

https://www.youtube.com/watch?v=6LbgJcaGX-s
