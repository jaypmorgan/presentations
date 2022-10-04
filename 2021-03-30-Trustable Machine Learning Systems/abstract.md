# Trustable Machine Learning Systems

Date: 2021-03-30
Presented at: British Colloquium for Theoretical Computer Science (BCTCS) 2021

Machine Learning (ML) has had a remarkable impact on
society. Everything from the phones in our pockets, to the cars that
we drive, are being increasingly outfitted with this progressively
sophisticated suite of algorithms. But while many of the most basic
and fundamental algorithms from ML can be formally verified and tested
for safety without much trouble, the same may not be said for Deep
Learning (DL) – a prominent forerunner in the state-of-the-art for ML
research. These DL models, while performing simple matrix-to-matrix
operations at a micro-level, have evolved in scale far past what is
tractable for current formal verification methods – all in the pursuit
of improving accuracy and performance. This issue of tractability is
unsettling considering that the existence of adversarial examples is
well known in the ML community. These adversarial examples occur when
very small changes to the input space result in a large change in the
output space and cause a miss-classification made by the DL model. In
the context of self-driving vehicles, small defects and visual
artifacts in the sensor input of the DL model, could lead the vehicle
to wrongly conclude a stop sign indicates to continue driving where it
should have stopped. While the manufacturers will need to put
safe-guards in place to prevent this from happening, we should
formally prove the (non)-existence of these adversarial examples in
the DL model itself. In this presentation, I present the foundational
knowledge for understanding adversarial examples, how we can use the
input space to dictate the search space for the existence of these
examples, and demonstrate their presence with the use of
SAT-solving. This work, as a free and open-source project, provides a
framework for ML practitioners to verify their own architectures.
