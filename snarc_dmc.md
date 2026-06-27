\---

layout: page
title: Modeling decision-making based on numerical information
section\_id: numerical\_cognition
---

\*by Dávid Csúri\*

\*\*According to a well-documented phenomenon in cognitive psychology, called the SNARC effect, it is easier to decide the parity of smaller numbers with our left hand.\*\*



Since the dawn of cognitive science, researchers have wanted to understand how mental representations work. One branch of cognitive psychology, called numerical cognition, is interested in understanding how we process numbers and their attributes, and how we manipulate our numerical mental representations. One way to investigate the underlying cognitive mechanisms of numerical processing is to study so-called numerical interferences.



When we talk about numerical interferences, we refer to situations in which numerical mental representations interact with other factors during number processing. The most documented example of such an interference is the SNARC effect (Spatial-Numerical Association of Response Codes).



To investigate the SNARC effect, we ask participants to sit in front of a computer and decide whether the numbers appearing on the screen are odd or even by responding with their hands. This experiment is called the parity judgment task. This may seem like a very simple task, but in reality, there is a small difference in response time depending on which hand is used. Participants usually respond faster to smaller numbers with their left hand and to larger numbers with their right hand, even though the task does not require them to process the magnitude of the number<sup>1</sup>.



From this, we can conclude that irrelevant spatial information influences the processing of numbers and their attributes. The difference in response time that the interference causes is only a few milliseconds, which may seem very small. Nevertheless, it tells us that seemingly irrelevant mental representations can become active and interact with relevant information within milliseconds, and that our decisions are made remarkably quickly.



\*\*According to cognitive psychology, however, decision-making does not work like a simple switch. Instead, it happens gradually.\*\*



In practice, this means that when we have to make a decision, we begin to accumulate information about the task. According to this theory, the information needed for a decision is gathered gradually and noisily. In other words, many different stimuli can influence the decision-making process. These stimuli may come from within ourselves, such as memories or previous experiences, or from the outside world, such as familiar or distracting sounds.



According to this theory, when participants sit in front of the computer to judge the parity of a number, their brains process much more than whether the number is odd or even. They also process the number's magnitude and the side of space with which it is associated. If the goal is simply to determine parity, then these additional pieces of information are irrelevant. This is why the SNARC effect is considered a numerical interference: irrelevant information interferes with processing the task-relevant attribute of the number.



\*\*With a computational model called drift diffusion modeling, we can simulate how this gradual and noisy decision-making process unfolds.\*\*



According to the model, the brain continuously gathers the information needed to reach a decision. The clearer the information, the faster the decision is made. However, distracting information can slow the process down or make it more uncertain. Such models are particularly useful because they help explain not only how long it takes to make a decision, but also the internal processes that may have produced that decision.



In the scientific literature on drift diffusion modelling, there are many competing models, each aiming to explain the cognitive processes underlying decision-making in different situations. In our study, we investigated two of these models.



According to the first model (Coalescence Model<sup>2</sup>), the distracting information, that is, whether the number is associated with the left or the right side of space, influences the decision with the same strength throughout the entire process.



The second model proposes a more complex explanation (Diffusion Model for Conflict Tasks<sup>3</sup>). According to this account, the distracting effect initially becomes stronger and stronger, but is then gradually suppressed by the brain's inhibitory mechanisms. In other words, the influence of irrelevant information is not constant during decision-making but changes over time. If this is how the process works, then fast and slow responses should show different patterns.



\*\*We wanted to test which of these models explains better the underlying cognitive mechanisms of the SNARC effect.\*\*



To investigate this question, we collected data from real participants using the parity judgement task described earlier. We then generated similar datasets using the two diffusion models. Finally, we compared the simulated data with the human data, focusing on their temporal dynamics. In other words, we examined how the strength of the interference changes across different response times.



Unfortunately, we were not able to clearly determine which model provides the better explanation. Both models generated data that resembled the patterns observed in real participants, but the differences between the two models were not large enough to distinguish them reliably.



\*\*At first glance, this question may seem rather trivial. In reality, however, it involves much more than simply deciding which hand we use to press a button.\*\*



Number processing is one of our most complex symbolic abilities. A better understanding of how the brain processes numbers can also help us understand other higher-order cognitive processes, such as attention, inhibition, and decision-making. Many of these higher-order cognitive processes play an important role in our everyday lives, and are related to certain neuropsychological disorders, such as dysexecutive syndrome or ADHD (Attention-Deficit/Hyperactivity Disorder).



Moreover, drift diffusion models are now widely used in many areas of experimental psychology, including research on attention and memory. The more accurately these models describe human decision-making, the more we can learn about how our minds work in theory.



Overall, our study has not settled the question, but it has opened new avenues for future research and was also able to integrate even more the scientific literature of numerical interferences and drift diffusion modelling. By collecting larger datasets and developing more precise computational models, we may eventually be able to determine which theory best describes what happens in our brains before we press a seemingly simple button to decide the parity of a number.



\*\*References\*\*  
1. Dehaene, S., Bossini, S., \& Giraux, P. (1993). The mental representation of parity and number magnitude. Journal of Experimental Psychology: General, 122(3), 371–396. <https://doi.org/10.1037/0096-3445.122.3.371>  


2. Schwarz, W., \& Ischebeck, A. (2003). On the relative speed account of number-size interference in comparative judgments of numerals. Journal of Experimental Psychology: Human Perception and Performance, 29(3), 507–522. <https://doi.org/10.1037/0096-1523.29.3.507>  


3. Ulrich, R., Schröter, H., Leuthold, H., \& Birngruber, T. (2015). Automatic and controlled stimulus processing in conflict tasks: Superimposed diffusion processes and delta functions. Cognitive Psychology, 78, 148-174. <https://doi.org/10.1016/j.cogpsych.2015.02.005>
