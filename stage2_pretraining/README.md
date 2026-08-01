# Stage 2: Pretraining

## Previous Module

In the previous module, we understood the concepts and implemented:

**Data Preparation**
- Tokenization
- Vector embeddings
- Positional embeddings

**Attention Mechanism**
- Self attention with no trainable weights
- Self attention with trainable weights (query, key and value weight matrices)
- Causal attention
- Multi-head attention

**LLM Architecture**
- Transformer Block Architecture
    - Layer normalization
    - Dropout
    - Feed forward neural networks
        - Expansion and Contraction
        - GELU activation function
    - Shortcut connections
- GPT Architecture
    - Output head
    - Logits

By the end of the previous module, we implemented the whole GPT architecture, which can return the Token Ids with the best probability. But, our parameters are still random and untrained so the output tokens are random as well.

## This Module

In this module, the aim is to train the parameters so that the model can give accurate outputs.