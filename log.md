# Thesis log

In this markdown file i'll be briefly logging the day to day progress on the thesis.

## March - April

The general goal of this period is to get a good understanding of the "representation" and "disentanglement" concepts in the context of deep learning. I'll be reading papers and books on the topic, while also brushing up on multivariate statistics and some probability theory.

- March 5 - March 24: 
    I reviewed many core math, machine learning and deep learning concepts from the following sources:

    - Probability and some measure theory from my uni courses books.
    - Chapter 6 and 7 of Goodfellow's Deep Learning book.
    - Introductory chapters on Elements of Statistical Learning.

- March 25:
    - Incorporated simple information theory intuition, such as what "entropy" and "information" mean, and the relationship between cross-entropy and log-likelihood estimation.

- March 26 - April 17:
    - I've read (skimed over some, properly read others) countless papers on superposition, disentanglement and concept probing on llms. The ones that I found most interesting are:
        - https://transformer-circuits.pub/2022/toy_model/index.html#motivation 
        - https://transformer-circuits.pub/2023/monosemantic-features/index.html
        - https://arxiv.org/html/2411.11296v1
        - https://arxiv.org/html/2410.06981v1
        - https://arxiv.org/abs/2305.01610
        - https://arxiv.org/abs/2409.04185

    - Also, i've ran into kolmogorov arnold networks, which have like no work done on them. If I find interesting results on them, it could lead to a publication or something.

    - Finally, I decided on doing an overview of disentanglement techniques for concept probing as my thesis. Comparing them on a smallish model such as LLama 7B. As a "new" technique, I am very curious on seeing how well sparse KAN autoencoders work on this task. I'll possibly also be investigating on some theoretical justification and connections for each technique, but I strongly believe the thesis should be mostly empirical. 
