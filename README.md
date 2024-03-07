# Seminar "Computational Aspect of Machine Learning" from TUM

Quantization techniques are methods applied to use low-precision datatypes to speed up inference time and reduce energy
consumption for operations performed in a computer. In Machine Learning, they have been applied to different situations,
such as Gaussian Processes, Kernel approximation, and (specially) Neural Networks. This paper provides an overview of the
current quantization techniques applied in the mentioned situations, identifying the features, challenges, and benefits achieved.
In Gaussian Processes, a low precision approach is used to efficiently compute the gradient for a Gaussian Process model.
In Kernel approximation, a direct parameters quantization is performed, as well as an approximation to kernel using quantized
values. In Neural Networks, general quantization techniques are explained (per channel/tensor quantization and quantization-aware
training/post-training quantization), as well as specific structures. Quantization in neural network can be applied by mixing a low
precision and full precision according to its role while training and inferring. That could narrow down into 4 bit level or even
extremely binary stage. Although quantization has provided successful results in specific use cases (discussed in this paper),
several challenges remain to be solved. Quantization ideas for Gaussian Processes and Kernel methods are still in premature state,
and a general method for quantizing Neural Networks is still in development. Therefore, although promising, different challenges
still remain for reduced/mixed precision in Machine Learning, as discussed in the conclusion.


paper: <https://github.com/jaykim1409/CAML/blob/master/reduced_mixed_precision_ml.pdf>

presentation: <https://github.com/jaykim1409/CAML/blob/master/reduced_mixed_precision_presentation.pdf>
