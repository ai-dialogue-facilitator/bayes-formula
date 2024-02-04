# Human Nature

<b>Human:</b> I need to take into account the consequences of actions when I'm calculating the probabilities of a decision being successful. Apparently it should be an iterative process if the initial situation repeats and there are results of the previous events available. I am trying to understand what should be the course of action. What would be your recommendations?<br>
> <b>machina:</b> Consider incorporating feedback from previous actions into your probability calculations. Use an iterative approach, updating probabilities based on past outcomes. Apply principles from game theory to analyze decision-making in strategic interactions. Explore meta-induction for insights into adapting strategies over repeated situations.<br>

<b>Human:</b> I need more detailed recommendations including the formulas.<br>
> <b>machina:</b> Utilize Bayesian probability for iterative updates:

$$ P(A | B) = \frac{P(B | A) \cdot P(A)}{P(B)} $$

Incorporate feedback with Bayes' rule:

$$ P(A | B_1, B_2, ..., B_n) \propto P(A) \cdot \prod_{i=1}^{n} P(B_i | A) $$

For game theory, Nash equilibrium guides strategic choices:

$$ \text{NE:} \quad \pi_i(s_i^*, s_{-i}^*) \geq \pi_i(s_i, s_{-i}^*) $$

Explore meta-induction by adapting strategies based on opponents' past behaviors:

$$ s_i(t+1) = f(s_i(t), h_{-i}(t)) $$

Iteratively update strategies considering historical outcomes and opponents' strategies.<br>

<b>Human:</b> Thank you.<br>
> <b>machina:</b> You're welcome. If you have further questions, feel free to ask.<br>
