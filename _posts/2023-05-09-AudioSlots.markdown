---
layout: post
title:  "AudioSlots: A slot-centric generative model for audio separation"
date:   2023-05-09 13:00:53 +00:00
image: /images/audioslots.png
categories: research
author: "Pradyumna Reddy"
paper: https://arxiv.org/abs/2305.05591
authors: "Pradyumna Reddy, Scott Wisdom, Klaus Greff, John R. Hershey, Thomas Kipf"
venue: "ICASSP(SASB)"
---
In a range of recent works, object-centric architectures have been shown to be suitable for unsupervised scene decomposition in the vision domain. Inspired by these methods we present AudioSlots, a slot-centric generative model for blind source separation in the audio domain. AudioSlots is built using permutation-equivariant encoder and decoder networks. The encoder network based on the Transformer architecture learns to map a mixed audio spectrogram to an unordered set of independent source embeddings. The spatial broadcast decoder network learns to generate the source spectrograms from the source embeddings. We train the model in an end-to-end manner using a permutation invariant loss function. Our results on Libri2Mix speech separation constitute a proof of concept that this approach shows promise. We discuss the results and limitations of our approach in detail, and further outline potential ways to overcome the limitations and directions for future work.
