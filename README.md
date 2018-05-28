# Discrete_Math

## Chapter 1

### Section 1.6  
### Rule of Inference

#### Intro
Argument: sequence of statement that ends in a conclusion.  
Premise: statements of truth.  
Vaild: conclusion must follow from the truth from the preceding statements.  
Fallacies: common forms of incorrect reasoning.  

#### Valid Arguments in Propositional Logic

"If you have access to the network, then you can change your grade."  
"You have access to the network."  
"Threrefore, you can change your grade."  
  
Premises P_1, P_2, ... P_n and conclusion is valid, when (P_1 ^ P_2 ... ^ P_n) -> q is a tautology.  

Rules of inference
(p ^ (p->q)) -> q   Modus ponens
(~q ^ (p->q)) -> ~p  Modus tollens  
((p -> q) ^ (q->r)) -> (p -> r)  Hypothetical syllogism  
((p V q) ^ ~q) -> q  Disjunctive syllogism  
p -> (p v q)  Addition  
(p ^ q) -> p  Simplification  
((p) ^ (q)) -> (p ^ q)  Conjunction  
((p v q) ^ (~ p v r)) -> (q v r)  Resolution  

#### Resolution 

Let p be the proposition “It is snowing,” q the proposition “Jasmine is skiing,” and r
the proposition “Bart is playing hockey.” We can represent the hypotheses as ¬p ∨ q and p ∨ r,
respectively. Using resolution, the proposition q ∨ r, “Jasmine is skiing or Bart is playing
hockey,” follows.
