Generate Pokemon Using GAN (Generative Adversarial Network) in MATLAB.

The credit for the code go to moxiegushi (google this name with pokemon GAN). Or you may google Siraj Raval - Generating pokemon with GAN in youtube. They are using Python for the training,however, for latest version of MATLAB R2019b, GAN is officially supported in MATLAB.

With 1xK80 GPU virtual machine in azure, it took around 8 hours to complete 2800 epochs with 128 mini batch size and ADAM optimizer. Now the azure NC6 instance (1xK80) is still under promotion rate (usd 0.672/hour).


Now i got the new pokemon. This is also how you generate fake images when you don't have enough data.
