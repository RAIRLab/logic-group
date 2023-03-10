# NY Capital Region Logic Group

Generally occurs on Wednesdays, we talk about areas within and surrounding computational logic.

## Upcoming Talk

Title: Reasoning with Cognitive Likelihood for Artificially-Intelligent Agents: Formalization & Implementation 

Time: Wednesday March 15th @ 2PM

Location: RAIR Lab, Winslow

Speaker: Michael Giancola

Abstract: Human beings routinely encounter situations containing informal,
non-quantitative uncertainty. Consider for example the following
scenario: Driving toward a four-way intersection, you stop at a red
light. Eventually, the light turns green, but you perceive a driver
approaching from your left, their light having turned red moments ago,
and subsequently perceive their car accelerate. What can we say about
this situation? It certainly seems likely that the driver will drive straight
through the light. Of course, it's entirely possible that the driver will change
their trajectory at the last second and slam on the brakes. How can we
quantify this uncertainty (assuming this is what we desired)?

We could compute a probability over all recorded instances of drivers
accelerating toward red lights and either going through or stopping. But
clearly humans don’t engage in anything like this computation when they
reason about other drivers on the road. We use likelihoods to express
qualities (as opposed to quantities e.g. probabilities) of the uncertainty of
beliefs. In this way, one may reason that "I believe it's highly likely that the
driver will drive through the red light'' and subsequently come to the conclusion
that, despite having the legal right-of-way, one should wait to avoid an accident.
Autonomous agents, in order to effectively interact with humans that reason this
way, will need to possess and exploit the ability to model reasoning with notions
of qualitative uncertainty.

The present dissertation introduces Cognitive Likelihood, a framework for reasoning
with uncertain beliefs. The framework is implemented within a novel logic --- the
Inductive Deontic Cognitive Event Calculus (IDCEC) --- which includes a formal grammar
and semantics which dictate how agents can reason within the framework. These formalisms
are implemented in an automated reasoner called ShadowAdjudicator in order to enable the
automatic generation of IDCEC proofs. We present the novel algorithm underlying
ShadowAdjudicator which enables this automated proof discovery. Finally, we demonstrate how
these contributions can be utilized to solve autonomous driving problems and to adjudicate=
arguments regarding a notorious probability puzzle, the Monty Hall Problem.


## Prior Talks

03/01/2023: Selmer Bringsjord presented
an original talk titled "A Cognitive Calculi for Attention-and-Perception: APCC*"

02/22/2023: Mike Giancola presented
["Distributed, Decentralized, and Democratized Artificial Intelligence"](https://www.sciencedirect.com/science/article/pii/S0040162518302920) by by Gabriel Axel Montes and Ben Goertzel published in the international journal on Technological Forecasting and Social Change.


02/15/2023: James Oswald presented
[“A Fuzzy Description Logic”](http://www.umbertostraccia.it/cs/download/papers/AAAI98/AAAI98.pdf) by Umberto Straccia published in AAAI 1998. Along with original associated lean proofs.


02/08/2023: Brandon Rozek gave an original talk on "Interactive Theorem Proving with Lean Part 2".


02/01/2023: Brandon Rozek gave an original talk on "Interactive Theorem Proving with Lean Part 1".


12/8/2022: 
Armin Karic gave an original talk “Compiling to Axioms” on equational logic.


11/2/2022: Mike Giancola presented
[Axiomatic Thinking, Identity of Proofs and the Quest for an Intensional Proof-Theoretic Semantics](https://link.springer.com/chapter/10.1007/978-3-030-77657-2_8) by Peter Schroeder-Heister


10/26/2022: Shreya Banerjee presented her research talk given at The University of New Orleans


10/19/2022:
Brandon Rozek presented
[Evaluation of the Moral Permissibility of Action Plans](https://gki.informatik.uni-freiburg.de/papers/lindner-etal-aij2020.pdf)
by Felix Lindner, Robert Mattmuller, and Bernhard Nebel.


09/14/2022:
Brandon Rozek presented
[Planning Modulo Theories: Extending the Planning Paradigm](https://www.aaai.org/ocs/index.php/ICAPS/ICAPS12/paper/viewFile/4693/4715) by Peter Gregory, Derek Long, Maria Fox, and J. Christopher Beck.


9/7/2022: Mike Giancola presented
[Braid: Weaving Symbolic and Neural Knowledge into Coherent Logical Explanations](https://ojs.aaai.org/index.php/AAAI/article/view/21333)


8/17/2022: James Oswald gave a preview presentation of
[PERI.2 Goes to PreSchool and Beyond, in Search of AGI](http://kryten.mm.rpi.edu/PERI2GoesToPreSchoolAGI2022.pdf) by Selmer Bringsjord et al.


8/10/2022: Selmer Bringsjord gave a talk on logic in the documentary film “President”


08/03/2022:
Brandon Rozek presented
[Coming Up with Good Excuses: What To Do When No Plan Can be Found](https://www.aaai.org/ocs/index.php/ICAPS/ICAPS10/paper/viewFile/1453/1532) by Moritz Gobelbecker, Thomas Keller, Patrick Eyerich, Michael Brenner, and Bernhard Nebel.


7/27/2022: James Oswald presented
[Free Will - Even For Robots](http://jmc.stanford.edu/articles/freewill/freewill.pdf) by John McCarthy


06/28/2022: 
Brandon Rozek presented
[Landmark-based heuristic online contingent planning](https://link.springer.com/article/10.1007/s10458-018-9389-9) by Shlomi Maliah, Guy Shani, and Ronen L. Brafman.


6/20/2022: Shreya Banerjee presented her research qualifier. 


6/7/2022: James Oswald presented
[A Net Structure for Semantic Information Storage, Deduction and Retrieval](https://www.ijcai.org/Proceedings/71/Papers/047.pdf) by Stuart C. Shapiro


06/01/2022:
Brandon Rozek presented 
[AI Planning Annotation for Sample Efficient Reinforcement Learning](https://arxiv.org/pdf/2203.00669) by Junkyu Lee, Michael katz, Don Joven Agravante, Miao Liu, Geraud Nangue Tasse, Tim Linger, Shirin Sohrabi.


5/24/2022: John Slowik presented
[Artificial Intelligent Agents Go to School](https://drive.google.com/file/d/1YaZdRZ4SZL1A17ckJOcOTpn6y2lulpOi/view?usp=sharing) by Sergei Nirenburg, Jesse English, and Marjorie McShane


5/18/2022: James Oswald presented
[The Tractability of Subsumption in Frame-Based Description Languages](https://aaai.org/Papers/AAAI/1984/AAAI84-036.pdf) by Ronald Brachman and Hector Levesque.

05/11/2022:
Brandon Rozek presented 
[The Power of Waiting in Social Laws](https://icaps21.icaps-conference.org/workshops/KEPS/Papers/KEPS_2021_paper_14.pdf) by Alexander Tuisov, Alexander Shleyfman, and Erez Karpas.

## Invited Speakers

<style>
  .speakers {
    display: flex;
    flex-wrap: wrap;
  }
  .speaker {
    margin: 10px;
    text-align: center;
  }
  .speaker img {
    clip-path: circle();
  }
  .speaker a {
    display: block;
  }
</style>


<div class="speakers">
  <div class="speaker"><img src="https://brandonrozek.com/img/avatar.jpg" height="250"><a href="https://brandonrozek.com">Brandon Rozek</a></div>  
  <div class="speaker"><img src="https://jamesoswald.dev/images/avatar.png" height="250"><a href="https://jamesoswald.dev/">James Oswald</a></div>  
  <div class="speaker"><img src="https://rair.cogsci.rpi.edu/files/2019/08/Giancola_Headshot-1-180x180.jpg" height="250"><a href="https://mjgiancola.github.io/">Mike Giancola</a></div>
  <div class="speaker"><img src="https://faculty.rpi.edu/sites/default/files/2021-12/Selmer-Bringsjord.jpg" height="250"><a href="https://homepages.rpi.edu/~brings/">Selmer Bringsjord</a></div>
  <div class="speaker"><img src="https://www.uno.edu/sites/default/files/inline-images/Shreya-Banerjee.jpg" height="250"><p>Shreya Banerjee</p></div>  
  <div class="speaker"><img height="250" width="250"><p>John Slowik</p></div>  
  <div class="speaker"><img height="250" width="250"><p>Armin Karic</p></div>  
</div>
