# Sparse-Transformers
Survey/Problem Statement

Transformer models are commonly used in machine learning for tasks such as natural
language processing, computer vision, and other areas that involve sequential data. While they
are highly effective, their attention mechanism can become very slow and consume a large
amount of memory when working with long sequences. This can make it challenging to process
lengthy documents, extended conversations, or large datasets efficiently.

Sparse Transformers simplify attention by letting each part of the input focus on only a
few other parts, instead of all of them. These selected connections are chosen so the model can
still understand the important relationships in the data. This saves time and memory while
keeping the results accurate.

This survey will focus on Sparse Attention in Transformers for Long Sequences. It will
examine early research on sparse attention concepts as well as more recent studies that improve
or apply these methods in practice. The analysis will categorize approaches by how sparsity is
applied and how efficiently each method performs. It will also discuss how well different
approaches balance speed and accuracy.

Although sparse attention improves efficiency, it can also make it harder for the model to
capture the full context. In this survey we want to understand, how can Transformers process
very long sequences efficiently without losing important information or accuracy? This study
will work to summarize current research, compare different methods, and outline challenges as
well as potential areas for future work.
