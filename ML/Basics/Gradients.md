Is needed to update the weights of our output from our input.

That is if the error measure of our prediction of the output from the input is bad. 

The goal of updating the weights is to have a better output prediction from our input. 


# Steps

By default [[Tensor]] don't require gradients. This can be changed the following:

`x.requires_grad(True)

	Only float tensors can have gradients

