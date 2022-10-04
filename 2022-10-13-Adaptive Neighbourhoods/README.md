# Adaptive Neighbourhoods for the Discovery of Adversarial Examples

Machine Learning, in particular Deep Learning, has most recently
provided the state-of-the-art results for many tasks such as object
recognition, text-to-speech processing, and credit-card fraud
detection. In many cases, Deep Learning has even out-performed human
performance on these very same tasks. Despite this advance in
performance, however, the existence of so-called adversarial examples is
well known within the community. These adversarial examples are the
metaphorical 'blind-spot' of Deep Learning models, where very small
(often human-imperceptible) changes to model's input can result
catastrophic miss-classifications. These adversarial examples then pose
a great safety risk, especially in systems where safety is critical such
as fully-automotive vehicles.

To defend against and attempt to eradicate the existence of adversarial
examples in Deep Learning models, principle works have sought to search
for their existence within fixed-sized regions around training points,
and use the found adversarial examples as a criterion for
learning. These works have demonstrated how the robustness of Deep
Learning models against adversarial examples improves through these
training regimes.

Our work means to compliment and improve on these existing approaches by
adapting the size of the searchable regions around training points,
based upon the complexity of the problem and data sampling density. The
result is each training point has an adapted region around it to which
adversarial examples can be searched for and found.

We demonstrate how, through the development of uniquely-adaptive
searchable regions, existing methods can help to further improve the
robustness of Deep Learning models, and also make the existing methods
applicable to non-image related tasks by providing an upper bound for
discovering adversarial examples.

In this presentation, we will explore how adversarial examples can be
determined through the use of existing approaches. Further to these
approaches, how our method allows us to generate unique and adapted
region sizes for all training points in a dataset.
