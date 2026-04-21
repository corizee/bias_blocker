# bias_blocker
Balance LLM prompts against known cognitive biases. Bias blocker teaches your agent to give better advice, resulting in better decisions.

Humans exhibit over [200 documented cognitive biases.](https://medium.com/thinking-is-hard/4-conundrums-of-intelligence-2ab78d90740f)
Unfortunately, LLMs exhibit many, too–and even show some biases at amplified rates. See these papers for evidence:
* [Large language models show amplified cognitive biases in moral decision-making](https://www.pnas.org/doi/10.1073/pnas.2412015122) (Cheung 2025)
* [The Bias is in the Details: An Assessment of Cognitive Bias in LLMs](https://arxiv.org/abs/2509.22856) (Knipper 2025)

## What's the Problem?
Decision quality suffers from biased advice. If employees are using LLMs and LLM-powered agents to help make decisions, the degraded decision quality becomes an issue at scale. 

That's a governance issue, and CIOs should be concerned.

<img width="4200" height="2811" alt="image" src="https://github.com/user-attachments/assets/d67bd657-0706-4339-9973-72f032cd9ed2" />


## What's a Solution?
NOT educating employees how to ask better questions. That's slow and very hard. Changing human behavior is one of the hardest things on earth.
Enter BIAS_BLOCKER.md. 

Employees can type their questions as they naturally would–but the agent knows to translate their prompts into more neutral questions, catching bias upstream. 

Another solution is coaching the LLM to behave differently. But coaching the answer is downstream. You're asking the model to recognize and correct for a bias that has already influenced its processing. The Cheung et al. paper showed that models often can't do this reliably, and when they do self-correct, it can look like reasoning even when it's just masking.

