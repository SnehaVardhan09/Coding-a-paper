"What i cannot create, I do not understand" - Richard Feynman

-Pre-requisites
    -Python/PyTorch
    -Transformers



Framework for implementing research paper, step by step
1. Pick a paper.
    - I'm interested in: this will probably take a while.
    - Choose something that has an existing implementation.
2. Identifying papar idea, how they will implement it, how they will test it.
3. Identifying the components of the paper.
4. Have a (rough) pseudocode understanding of how things work and fit together.
5. build the individual components.
6. Assemble them into a model.
7. Run and test the model.

github - Lucidrains

**Checklist questions:**
1. What's the idea in a sentence or two?
    - Authurs envision language models that can simply read and memorize new data at inference time. Approximate KNN lookup into non-differentiable memory if recent keu-value pairs improve language modeling.

2. What's the motivation as framed by the authors? whats the problem that they are solving?
    - Attending to far-away tokens is important in many situations. However, transformers perf is limited by context window size: transformers is a quadratic (O(n^2)) time and space complexity, so doubling the context window quadraples the compute requirements. This is why we cannot just naively make the context window bigger. There are many solutions that try to resolve this problem and create long- range attention.

* How do they attempt to solve it?
* What is the main contribution of the paper?
* How do they measure success?
* Were they successfull?
* Keep a running list of questions and knowledge gaps for yourself



 