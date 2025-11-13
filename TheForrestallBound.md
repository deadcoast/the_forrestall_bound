# The Forrestall Bound
THE HURDLES OF SCALING COMPUTATIONAL INTELLIGENCE

The computational and financial scaling required for advancing AI towards AGI (Artificial General Intelligence), juxtaposing it with the complexity of the human brain. The problem represented in these ideas are supplied mathematically, incorporating symbolic variables to capture the essence of the growth in compute requirements and financial investments.

## Symbolic Representation

Let:

- $C_n$ represent the cost of running generation $n$ of a GPT model.
- $P_n$ denote the number of parameters in generation $n$ of a GPT model.
- $G$ denote the generation number of the GPT model.
- $R$ represent the required multiplier for computing effectiveness between generations.
- $S_{human}$ denote the estimated number of synapses in the human brain, encapsulating the complexity we're comparing against.

Given the conversation, we can symbolically express the following:

1. **Cost Growth Model**:
   - $C_G = 100^{G-4} \times 10^8$ USD,
     Where $G = 4$ for GPT-4 with a baseline cost of $C_4 = 10^8$ (or $100 million).
   - This model shows the exponential cost increase with each GPT generation, assuming that each new model generation requires significantly more financial investment, following a 100x pattern mentioned in the discussion.

2. **Parameter Growth and Computational Effectiveness**:
   - $P_G = R^{G-4} \times 10^{12}$,
     Assuming $R = 100$ (as a 100x increase in compute effectiveness is required between model generations) and $P_4 = 10^{12}$ (1 trillion parameters for GPT-4).

3. **Comparison to Human Brain Complexity**:
   - $S_{human} \approx 3 \times 10^{13}$ to $3 \times 10^{14}$ (synapses),
     representing the lower and upper estimates of the human brain's complexity.

### Discussion Representation

Using these definitions, the underlying mathematical conversation can be formulated as exploring the bounds of $G$ under which:

- The cost $C_G$ remains feasible for private or national consortium funding.
- The parameter count $P_G$ approaches or exceeds $S_{human}$ as a proxy for achieving AGI.

### Symbolic Inquiry into AGI Feasibility

One might inquire if there exists a $G_{AGI}$ such that $P_{G_{AGI}} \geq S_{human}$ within a feasible $C_{G_{AGI}}$. This inquiry encapsulates the essence of the discussion, probing whether the financial and computational scaling pathways can plausibly lead to AGI before hitting insurmountable barriers.

### Reflection

This symbolic representation abstractly models the conversation's core, framing it within the broader context of AI development challenges. It encapsulates the nuanced interplay between computational growth, financial investments, and the ultimate quest to reach or surpass human-level cognitive complexity.

I'll express the scaling problem as a symbolic mathematical model according to the given data and context. The goal is to capture the essence of the scaling needed to approach AGI, with computational and financial requirements far exceeding current technological capabilities.

### Symbolic Mathematical Representation

#### Variables

- $C_n$: Cost to run generation $n$ of a GPT model (in USD)
- $P_n$: Number of parameters in generation $n$ of a GPT model
- $G$: Generation number of the GPT model
- $R$: Required multiplier for computing effectiveness between generations
- $S_{human}$: Number of synapses in the human brain representing cognitive complexity

#### Formulas

1. **Cost Growth Model**:
   - $C_G = 100^{G-4} \times 10^8$ for $G \geq 4$

2. **Parameter Growth and Computational Effectiveness**:
   - $P_G = R^{G-4} \times 10^{12}$

3. **Comparison to Human Brain Complexity**:
   - $S_{human} \approx 3 \times 10^{13}$ to $3 \times 10^{14}$ synapses

### Representation of the Scaling Challenge

The challenge translates into finding a generation $G_{AGI}$, which signifies the achievement of AGI such that:

- $C_{G_{AGI}}$ is below or within the maximum feasible investment threshold.
- $P_{G_{AGI}}$ approaches or surpasses $S_{human}$ to represent the AGI level complexity.

### Symbolic Inquiry into AGI Feasibility

Mathematically, the inquiry is to determine whether there exists a $G_{AGI}$ such that:

- $P_{G_{AGI}} \geq S_{human}$ within a computationally and financially feasible realm,
- $C_{G_{AGI}}$ is sustainable by existing or projected economic capabilities.

This can be represented by the set of inequalities and equalities to be satisfied:

$$\exists G_{AGI} : \left\{
  \begin{array}{l}
    P_{G_{AGI}} \geq S_{human} \\
    C_{G_{AGI}} \leq \text{Max Feasible Funding}
  \end{array}
\right.$$

### Reflection on the Symbolic Model

This mathematical expression serves as a framework for analyzing the trajectory and feasibility of reaching AGI through scalable technology. It acknowledges the exponential growth required in computational resources and financial investment, comparing it against a quantifiable target that proxies the complexity of the human brain. The symbolic model does not account for qualitative factors but rather provides a quantitative baseline for considering the immensity of the challenge ahead.
