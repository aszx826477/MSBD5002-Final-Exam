# Q3 Readme

I have some thoughts on this question. Actually this dataset is used for action recognition and detection and the final exam in the last year also did utilize this dataset to do this task. Howerver, in this year, the same dataset is used for different purpose and this is the reason I was stuck in the beginning. All the video is real instead of fake so how to train a classifier without any negative samples?

All the supervised learning methods were dead so I had to seek help for un-supervised learning. GAN (Generative Adversarial Networks) is a method I think might solve the problem. We can train a pair `Generator` and `Discriminator` at the same time. The Generator generate image by adding some noise or some distributions. The discriminator is responsible for detecting the fake image. 

Finally, The discriminator is what we want, a kind of fake video detection model.

However, I had no time to do this so I just wrote down my thought about this question.