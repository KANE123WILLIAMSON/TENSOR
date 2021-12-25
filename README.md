# TENSOR
Tensor basics
Steps to check version of a tensor:-
import tensorflow as tf
print(tf.__version__)
2.6.0
x = tf.constant([[7.8,12,13,14],[1,2,4,5]])
<tf.Tensor: shape=(2, 4), dtype=float32, numpy=
array([[ 7.8, 12. , 13. , 14. ],
       [ 1. ,  2. ,  4. ,  5. ]], dtype=float32)>
x=tf.constant([[1,2,5],[1,3,8],[4,5,1]])
print x
<tf.Tensor: shape=(3, 3), dtype=int32, numpy=
array([[1, 2, 5],
       [1, 3, 8],
       [4, 5, 1]], dtype=int32)>
