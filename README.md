# awesome-efficient-computation
List of related articles about how-to-achieve equal/similar accuracy with less memory consumption in DL

### Store Less Activations
The Reversible Residual Network: Backpropagation Without Storing Activations 
> the activation storage requirements are independent of depth.

### Via Approximation
Reformer : REFORMER: THE EFFICIENT TRANSFORMER
> Approximate attention computation based on locality-sensitive hashing 
  > Use same Q, K projected from draft embedding A for Attention. (So called shared-QK Transformer)

> Since reformer recalculate its tensor when it's required for backpropagation, we might need different framework from conventioinals - such as pytorch or tf.
