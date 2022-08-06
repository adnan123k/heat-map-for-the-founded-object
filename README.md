# heat-map-for-the-founded-object
our application will be draw a heating map on the founded object by using pre-trained model weights.<br/>
we used resnet model, we took the output of the final layer before the flatten layer and take the weights of the last layer in the resnet.<br/>
that being said we take the output of the final layer before the flatten layer and multiple it with weights as weights for finding the object.
# how to run it
there is two ways to use it:<br/>
1-colab<br/>
2-locally<br/>
if you're using colab just upload the ipynb file and run it<br/>
locally:<br/>
1-you have to install python 3<br/>
2-the recommended libraries<br/>
3-install ide and open the .py file or .ipynb<br/>
4-run it<br/>

# the recommended libraries:
1-tensorflow<br/>
3-numpy<br/>
5-matplotlib

# reference:
https://tree.rocks/get-heatmap-from-cnn-convolution-neural-network-aka-grad-cam-222e08f57a34?gi=d97bc2245045
