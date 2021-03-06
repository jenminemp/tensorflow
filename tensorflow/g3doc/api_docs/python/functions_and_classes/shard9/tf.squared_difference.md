### `tf.squared_difference(x, y, name=None)` {#squared_difference}

Returns (x - y)(x - y) element-wise.

*NOTE*: `SquaredDifference` supports broadcasting. More about broadcasting
[here](http://docs.scipy.org/doc/numpy/user/basics.broadcasting.html)

##### Args:


*  <b>`x`</b>: A `Output`. Must be one of the following types: `half`, `float32`, `float64`, `int32`, `int64`, `complex64`, `complex128`.
*  <b>`y`</b>: A `Output`. Must have the same type as `x`.
*  <b>`name`</b>: A name for the operation (optional).

##### Returns:

  A `Output`. Has the same type as `x`.

