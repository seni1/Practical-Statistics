# Bayes-Rule
Bayes rule provides us with a way to update our beliefs based on the arrival of new, relevant pieces of evidence. For example, if we were trying to provide the probability that a given person has cancer, we would initially just say it is whatever percent of the population has cancer. However, given additional evidence such as the fact that the person is a smoker, we can update our probability, since the probability of having cancer is higher given that the person is a smoker. This allows us to utilize prior knowledge to improve our probability estimations.

The Rule

The below equation is Bayes rule:

The rule has a very simple derivation that directly leads from the relationship between joint and conditional probabilities. First, note that P(A,B) = P(A|B)P(B) = P(B,A) = P(B|A)P(A). Next, we can set the two terms involving conditional probabilities equal to each other, so P(A|B)P(B) = P(B|A)P(A), and finally, divide both sides by P(B) to arrive at Bayes rule.
In this formula, A is the event we want the probability of, and B is the new evidence that is related to A in some way.
P(A|B) is called the posterior; this is what we are trying to estimate. In the above example, this would be the “probability of having cancer given that the person is a smoker”.
P(B|A) is called the likelihood; this is the probability of observing the new evidence, given our initial hypothesis. In the above example, this would be the “probability of being a smoker given that the person has cancer”.
P(A) is called the prior; this is the probability of our hypothesis without any additional prior information. In the above example, this would be the “probability of having cancer”.
P(B) is called the marginal likelihood; this is the total probability of observing the evidence. In the above example, this would be the “probability of being a smoker”. In many applications of Bayes Rule, this is ignored, as it mainly serves as normalization.
