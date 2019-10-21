# minimal-adversarial-ml-example
cleverhans fgsm + iris dataset example

# Minimal adversarial attack example
## with cleverhans and the iris dataset
#### by August Karlstedt
Most adversarial examples are shown in images where a normal, unmodified image is displayed as the input. An adversarial noise is crafted, and is shown being added to the original input image. The reader can then see how this noise modifies the image in a nearly unnoticeable way, while the classifier output is changed significantly.

While this is good for a visual understanding, it complicates some things when thinking about the actual happenings of adversarial attacks. Therefore, I have constructed a simple example using the infamous iris dataset. One can clearly see the small changes to the input will change the predicted class. It is easy to modify parameters and see how it affects the adversarial algorithm.