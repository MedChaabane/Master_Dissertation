# End-to-end learning framework for circular RNA classiﬁcation from other long non-coding RNAs using multi-modal deep learning.([code available in python](https://github.com/UofLBioinformatics/circDeep))


# Keywords
sequence models, Assymetric convolutional neural network, BLSTM, Feature fusion learning
# Abstract
Over the past two decades, a circular form of RNA (circular RNA) produced from splicing
mechanism has become the focus of scientific studies due to its major role as a microRNA (miR) ac-
tivity modulator and its association with various diseases including cancer. Therefore, the detection
of circular RNAs is a vital operation for continued comprehension of their biogenesis and purpose.
Prediction of circular RNA can be achieved by first distinguishing non-coding RNAs from protein
coding gene transcripts, separating short and long non-coding RNAs (lncRNAs), and finally pre-
dicting circular RNAs from other lncRNAs. However, available tools to distinguish circular RNAs
from other lncRNAs have only reached 80% accuracy due to the difficulty of classifying circular
RNAs from other lncRNAs. Therefore, the availability of a faster, more accurate machine learning
method for the identification of circular RNAs, which will take into account the specific features of
circular RNA, is essential in the development of systematic annotation. Here we present an End-
to-End multimodal deep learning framework, our tool, to classify circular RNA from other lncRNA.
It fuses a RCM descriptor, an ACNN-BLSTM sequence descriptor, and a conservation descriptor
into high level abstraction descriptors, where the shared representations across different modalities
are integrated. The experiments show that our tool is not only faster compared to existing tools
but also eclipses other tools by an over 12% increase in accuracy. Another interesting result found
from analysis of a ACNN-BLSTM sequence descriptor is that circular RNA sequences share the
characteristics of the coding sequences.
