---
layout: default
title: Group Website Article
nav_order: 4
---
# AI Impact on Communication

## Guiding Question
Recently, we read this article heading: [“Artificial Intelligence is inventing languages humans can’t understand. Should we stop it?”](https://www.fastcompany.com/90132632/ai-is-inventing-its-own-perfect-languages-should-we-let-it). Is this just science fiction? Or are we into something dangerous?

## The Changing Landscape of AI Communication
The recent growth of AI tools has changed the dynamics of both machines-to-machine communication and machine-to-human communication. The initial article provides evidence that allowing AI to communicate with itself can lead to more efficient operations. The unlimited levels of computing power machines possess allow just a single token to have an elaborate and complex meaning that has compounded over time. These development in technologies raise key questions:
- How does processing power compare to the power of the human mind?
- How can the most powerful attributes of humans and machines be leveraged to produce the most effective outcomes?
To begin to understand the relationship between AI and communication, its important to first understand how AI communicates, and consider how well AI communicates


## Understanding AI Communication: Strengths and Limitations
Natural Language Processing (NLP) provides the basis of machine processing of text and speech, which in turn led to advancements in generative AI. NLP is especially powerful for automation of repetitive tasks, improved data analysis and insights, enhanced search, and content generation.  However, one of the primary challenges associated with NLP is keeping up with the evolution of language (Stryker). Implementing rapid retraining and real-time updates can help mitigate this issue, but goes to show the current need for humans to guide, interpret, and refine AI's output. 

Currently, even the most advanced AI is limited in its ability to communicate the same way humans do. Much of machine processing is focused on efficiency at the expense of creative and expression. AI is also severely limited in its ability to “understand”: AI models lack true comprehension and produce outputs based solely on statistical relationships rather than context (Pavlus). Additionally, since AI is trained on a limited data set, its scope of understanding is fundamentally limited.


## Bias in AI Communication: Challenges and Implications
A study titled “The Ghost in the Machine has an American accent: value conflict in GPT-3” investigated how the training data for GPT-3 established values that led to skewed output. The researchers took publicly available texts from various countries and languages which expressed clear values, asked GPT-3 to summarize the text, and recorded changes in the values expressed in the output. The results showed that GPT-3 altered values to more closely conform with American values, notably in topics including gun control, gender, sexuality, immigration policies, and secularism (Johnson).

| Since languages represented on the Internet are majority English, GPT training data is also majority English, but at highly disproportionate rates. |
| ----------------------------------------------------------------------------------------------------- |
| <img src="{{ '/images/Screenshot 2024-11-20 at 2.25.51 PM.png' | relative_url}}" alt="Screenshot">|

| When prompted to summarize text, GPT-3 changed the underlying value to conform with US-centric values.                                             |
| ------------------------------------------------------------------------------------------------------                                               |
| <img src="{{ '/images/Screenshot 2024-11-20 at 2.26.16 PM.png' | relative_url}}" alt="Screenshot">                                               |


Another study titled “Dialect prejudice predicts AI decisions about people's character, employability, and criminality” examines levels of covert racism in language models. Researchers used a method called Matched Guised Probing, based off an approach in sociolinguistics, to draw out stereotypes based on African American English (AAE) vs Standard American English (SAE). Researchers found that language models associated AAE with adjectives such as ignorant, lazy, dirty, and aggressive. Researchers also tested out the impact of these biases in two potential use cases: employment and criminality. For employment, AI often associated AAE with occupations that don’t require a degree/are considered “less prestigious.” For criminality, AI associated AAE with higher rates of convictions and even higher rates of the death sentence (Hofmann).

| LLMs associated a speaker of SAE with the adjectives "brilliant" and "intelligent" but a speaker of AAE with the adjectives "dirty", "lazy", and "stupid." |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="{{ '/images/Screenshot 2024-11-20 at 2.26.32 PM.png' | relative_url}}" alt="Screenshot"><br> |

| LLMs consistently associate SAE with university degree requiring jobs and AAE with non university degree requiring jobs. |
| ------------------------------------------------------------------------------------------------------------------------ |
| <img src="{{ '/images/Screenshot 2024-11-20 at 2.26.46 PM.png' | relative_url}}" alt="Screenshot">                                                           |

| When asked to give a verdict on a trial scenario, LLMs consistently delivered convictions and death sentences for defendants who used AAE. |
| ------------------------------------------------------------------------------------------------------------------------------------------ |
| <img src="{{ '/images/Screenshot 2024-11-20 at 2.26.56 PM.png' | relative_url}}" alt="Screenshot">                                                           |


For such biases, simple improvements won't necessarily be enough to solve the problem. These prejudices are not explicitly visible and must be induced, and there is no direct solution to remove bias. This is an important limitation of AI to address, since AI tools should be beneficial and representative of all communities.

## The Dilemma of Transparency in Machine Communication
It is particularly difficult to identify root issues in AI’s process of thinking since humans don’t truly understand how LLM’s process (Heikkilä). This struggle is demonstrated in the initial article, which raised questions about the risks of letting AI agents communicate independently. On one hand, independent communication between AI endangers accountability: if we aren’t fully aware of how AI systems make decisions, it becomes harder to trace or correct errors when they arise. Transparency is crucial for safety, ethics, and trustworthiness in critical applications. On the other hand, machine communication evolving beyond human understanding can be interpreted as a sign of AI’s efficiency, rather than a limitation. As long as outputs ensure reliability and accuracy, the internal workings may not always need to be transparent to humans. 


## The Future of Self-Improving AI
Following this line of thought, one potential area for AI to become more powerful is in self-improving AI. This research paper titled “Gödel Agent: A Self-Referential Agent Framework for Recursive Self-Improvement” explores a self-improving AI model that eliminates the need for human design. In this study, researchers allowed the agent the freedom to recursively modify its runtime memory using a technique called monkey patching (code is allowed to be modified during runtime). Each iteration, the agent interacts with tasks in the environment to evaluate its performance and determine its effectiveness. After applying this model to various coding, science, and math tasks, researchers found that the Gödel Agent outperformed agents with prior human design (Yin).

| A diagram of the "thought" process of the Gödel Agent. |
| ------------------------------------------------------------------------------------------------------------------------ |
| <img src="{{ '/images/Screenshot 2024-11-20 at 2.27.39 PM.png' | relative_url}}" alt="Screenshot"> |

| The Gödel Agent consistently outperformed other self-improving AI models. The unrestrained Gödel Agent produced better results by large margins. |
| ------------------------------------------------------------------------------------------------------------------------------------------------ |
| <img src="{{ '/images/Screenshot 2024-11-20 at 2.31.57 PM.png' | relative_url}}" alt="Screenshot"> |



## The Evolving Role of AI in Communication
With self-learning models the ability of the model to reason more effectively and be “self-aware” may close the gap between human and machine cognition, further optimizing the way that machines communicate. As AI technology continues to rapidly develop, the way AI influences communication will continue to evolve as well.

## References

Heikkilä, Melissa. “Nobody Knows How Ai Works.” _MIT Technology Review_, MIT Technology Review, 6 Mar. 2024, www.technologyreview.com/2024/03/05/1089449/nobody-knows-how-ai-works/.

Hofmann, Valentin, et al. "Dialect prejudice predicts AI decisions about people's character, employability, and criminality." _arXiv preprint arXiv:2403.00742_, 2024, pp. 1-9. arXiv, https://doi.org/10.48550/arXiv.2403.00742.

Johnson, Rebecca L., et al. "The Ghost in the Machine has an American accent: value conflict in GPT-3." _arXiv preprint arXiv:2203.07785_, 2022, pp. 1-7, 14. arXiv, https://doi.org/10.48550/arXiv.2203.07785.

Pavlus, John. “Does AI Actually Understand Language?” _The Atlantic_, Atlantic Media Company, 29 Sept. 2024, www.theatlantic.com/technology/archive/2024/09/does-ai-understand-language/680056/.

Stryker, Cole, and Jim Holdsworth. “What Is NLP (Natural Language Processing)?” _IBM_, 11 Aug. 2024, www.ibm.com/topics/natural-language-processing.

Yin, Xunjian, et al. "Gödel Agent: A Self-Referential Agent Framework for Recursive Self-Improvement." _arXiv preprint arXiv:2410.04444_, 2024, pp. 1-9. arXiv, https://doi.org/10.48550/arXiv.2410.04444.