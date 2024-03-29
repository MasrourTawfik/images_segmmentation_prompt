Transformer Architecture
========================

.. _Introduction:

1. introduction
-----------------
.. raw:: html

   <p style="text-align: justify;">
   Introduced in 2017 and first presented in the groundbreaking paper "Attention is All You Need" (Vaswani et al. 2017), the Transformer model has been a revolutionary contribution to deep learning and, some argue, to computing as a whole. Born as a tool for automatic neural machine translation, it has proven to be of much greater scope, extending its applicability beyond natural language processing (NLP) and solidifying its position as a versatile and generalized neural network architecture.

   In this comprehensive guide, we will dissect the Transformer model down to its fundamental structure, exploring in detail each key component, from its attention mechanism to its encoder-decoder architecture. Not stopping at the fundamental level, we will traverse the landscape of large language models that harness the power of Transformers, examining their unique design attributes and functionalities. Expanding further horizons, we will explore the applications of Transformer models beyond NLP and delve into the current challenges and potential future directions of this influential architecture. Additionally, a curated list of open-source implementations and additional resources will be provided for those interested in further exploration.

   Without frills or fanfare, let's dive in!
   </p>


.. figure:: /Documentation/images/arch.png
   :width: 100%
   :align: center
   :alt: Alternative text for the image
   :name: Architecture


.. _Attention is All You Need:

2. Attention is all you need
------------------------------


.. raw:: html

   <p style="text-align: justify;">
      Attention is all you need is a paper from google brain and google research, which was initially proposed as a replacement for RNN networks in natural language processing. In this blog, we will understand the theoretical idea behind the transformer and later implement it in PyTorch.

      This section gives some basic ideas about how we get feature vectors from the words. If you are familiar with any tokenizer or word2vector you can directly go to the next section.
   </p>







