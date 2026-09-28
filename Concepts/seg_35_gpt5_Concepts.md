
---
<!-- Total tokens: 0 -->
# Chapter: seg_35 Heading：chapter 3: probability topics




---
<!-- Total tokens: 6429 -->
# Section: seg_37 Heading：3.1 terminology

- **Probability**: A measure of how certain we are of outcomes of a particular experiment or activity.
- **Experiment**: A planned operation carried out under controlled conditions.
- **Chance Experiment**: An experiment whose result is not predetermined.
- **Outcome**: A result of an experiment.
- **Sample Space**: The set of all possible outcomes of an experiment; denoted by S and representable by a list, tree diagram, or Venn diagram.
- **Event**: Any combination of outcomes, typically denoted by uppercase letters such as A or B.
- **Probability Range**: Probabilities lie between zero and one, inclusive.
- **Equally Likely Outcomes**: Each outcome of an experiment occurs with equal probability.
- **Probability For Equally Likely Outcomes**: P(A) is computed as the number of outcomes in event A divided by the total number of outcomes in the sample space.
- **Long-Term Relative Frequency**: The probability of an outcome interpreted as its long-run relative frequency.
- **Law Of Large Numbers**: With increasing repetitions of an experiment, the observed relative frequency approaches the theoretical probability.
- **Biased (Unfair) Outcomes**: Situations in which outcomes are not equally likely due to bias in the device or process.
- **Or Event**: The event containing outcomes in A or in B or in both A and B.
- **And Event**: The event containing outcomes that are in both A and B at the same time.
- **Complement Of An Event**: The set of all outcomes not in event A; denoted A′.
- **Complement Rule**: P(A) + P(A′) = 1.
- **Conditional Probability**: The probability of A given B, written P(A|B), calculated as P(A AND B) divided by P(B) where P(B) > 0; the condition reduces the sample space to B.


---
<!-- Total tokens: 8083 -->
# Section: seg_39 Heading：3.2 independent and mutually exclusive events

- **Independent Events**: Two events for which P(A|B) = P(A), P(B|A) = P(B), or P(A AND B) = P(A)P(B); knowing one occurs does not affect the chance the other occurs.
- **Dependent Events**: Two events that are not independent; the occurrence of one affects the probability of the other.
- **Sampling With Replacement**: A sampling method where each selected member is replaced before the next pick, allowing members to be chosen more than once and making selections independent.
- **Sampling Without Replacement**: A sampling method where selected members are not replaced, so each can be chosen only once and later probabilities are affected, making selections dependent.
- **Mutually Exclusive Events**: Events that cannot occur at the same time; they share no outcomes and satisfy P(A AND B) = 0.
- **Default Assumption About Independence**: If it is unknown whether events are independent or dependent, assume they are dependent until shown otherwise.
- **Default Assumption About Mutual Exclusivity**: If it is unknown whether events are mutually exclusive, assume they are not mutually exclusive until shown otherwise.
- **Showing Independence**: Demonstrating independence requires verifying only one condition: P(A|B) = P(A), or P(B|A) = P(B), or P(A AND B) = P(A)P(B).


---
<!-- Total tokens: 4635 -->
# Section: seg_41 Heading：3.3 two basic rules of probability

- **Multiplication Rule**: For events A and B, P(A AND B) = P(B)P(A|B); if A and B are independent, P(A AND B) = P(A)P(B).
- **Conditional Probability**: The probability of A given B is P(A|B) = P(A AND B) / P(B).
- **Addition Rule**: For events A and B, P(A OR B) = P(A) + P(B) - P(A AND B); if A and B are mutually exclusive, P(A OR B) = P(A) + P(B).
- **Independent Events**: A and B are independent if P(A|B) = P(A), which implies P(A AND B) = P(A)P(B).
- **Mutually Exclusive Events**: A and B are mutually exclusive if P(A AND B) = 0.


---
<!-- Total tokens: 6858 -->
# Section: seg_43 Heading：3.4 contingency tables

- **Contingency Table**: A tabular display of sample values for two variables that facilitates calculating probabilities, including conditional probabilities, for variables that may be dependent.
- **Conditional Probability**: A probability evaluated under a stated condition by reducing the sample space to outcomes that satisfy the condition.
- **Intersection (And) Of Events**: The probability that two events occur together, denoted P(A AND B).
- **Union (Or) Of Events**: The probability that at least one of two events occurs, computed as P(A) + P(B) − P(A AND B).
- **Independence Of Events**: Two events are independent if P(A AND B) equals P(A)P(B).
- **Multiplication Rule For Joint Probability**: A joint probability equals a conditional probability times the probability of the given event, P(A AND B) = P(B|A)P(A).
- **Probability Contingency Table**: A contingency table with probability entries whose row/column totals are consistent and whose grand total equals 1.


---
<!-- Total tokens: 8957 -->
# Section: seg_45 Heading：3.5 tree and venn diagrams

- **Tree Diagram**: A special graph to determine and visualize all outcomes of an experiment, consisting of branches labeled with frequencies or probabilities.
- **With Replacement**: Returning the first selection to the pool before making the next selection.
- **Without Replacement**: Not returning the first selection to the pool before making the next selection.
- **Branch Multiplication In Tree Diagrams**: The value at an outcome node is obtained by multiplying the probabilities on the corresponding branches.
- **Conditional Probability**: The probability of an event given that another event has occurred, evaluated on the reduced sample space where the given event holds.
- **Conditional Probability Notation**: P(A|B) denotes the probability of event A given event B.
- **Venn Diagram**: A picture representing the outcomes of an experiment; the rectangle represents the sample space S and circles or ovals represent events.
- **Event Intersection (AND)**: The set of outcomes common to both events; represented by the overlap of event regions in a Venn diagram.
- **Event Union (OR)**: The set of outcomes that are in either event; represented by the combined area of event regions in a Venn diagram.
- **Addition Rule For Two Events**: P(A OR B) = P(A) + P(B) − P(A AND B).
- **Neither Event Region**: The area inside the sample space but outside all event regions, representing outcomes in neither event.


---
<!-- Total tokens: 19542 -->
# Section: seg_47 Heading：3.6 probability topics

- **Conditional Probability**: The likelihood that an event will occur given that another event has already occurred (P(A|B)).
- **Contingency Table**: A table with rows and columns displaying a frequency distribution to show possible dependence between two variables and to facilitate calculation of conditional probabilities.
- **Dependent Events**: Events that are not independent.
- **Equally Likely**: Each outcome of an experiment has the same probability.
- **Event**: A subset of the sample space (set of all outcomes) of an experiment.
- **Experiment**: A planned activity carried out under controlled conditions.
- **Independent Events**: Events where the occurrence of one has no effect on the other; equivalently, P(A|B) = P(A), P(B|A) = P(B), or P(A AND B) = P(A)P(B).
- **Mutually Exclusive Events**: Events that cannot occur at the same time; P(A AND B) = 0.
- **Outcome**: A particular result of an experiment.
- **Probability**: A number between zero and one, inclusive, indicating the likelihood an event occurs; axioms include 0 ≤ P(A) ≤ 1, P(S) = 1, and for mutually exclusive A and B, P(A OR B) = P(A) + P(B).
- **Sample Space**: The set of all possible outcomes of an experiment.
- **Sampling With Replacement**: After selection, a member is replaced and may be chosen more than once.
- **Sampling Without Replacement**: Each member may be chosen only once.
- **And Event**: Outcomes that are in both A and B at the same time.
- **Complement Event**: All outcomes that are not in event A.
- **Or Event**: Outcomes that are in A, in B, or in both A and B.
- **Tree Diagram**: A visual representation of a sample space and events using branches marked by outcomes with associated probabilities (frequencies, relative frequencies).
- **Venn Diagram**: A visual representation of a sample space and events using circles or ovals showing their intersections.
- **Multiplication Rule**: P(A AND B) = P(A|B)P(B).
- **Addition Rule**: P(A OR B) = P(A) + P(B) − P(A AND B).

