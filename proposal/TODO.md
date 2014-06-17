##1. Project Description

  ~~“Much work has been done focusing on cooperative coevolution as a method
  for producing agents that perform well at this task. Our research will
  focus primarily on the composition and complexity of such robotic agents.”~~

  ~~Replace “Our research will focus primarily on the composition and
  complexity of such robotic agents.” – and the final paragraph with
  something like:~~

  ~~“However, we will study variable sensor-actuator configurations
  (morphology) of individual robots, since the impact of morphology on
  emergent cooperative versus competitive group behaviour has received less
  research attention.”~~

  ~~The rest of the project description is fine.~~

##2. Problem Statement
Replace all mention of “hardware” with the term “morphology” – the former
term applies only to physical robots, the latter can apply to simulated or
physical.

“Our main research topic is the impact of hardware choice and
configuration on the emergence of cooperation in a multi-agent system.
Along those lines, we intend to investigate three important aspects of
this topic:”

This needs to be reworded to emphasize that the emergent cooperation is
necessary for solving a foraging task, and that the multi-agent system is
a simulated multi-robot system.

~~“Along those lines, we intend to investigate three important aspects of
this topic:”~~

~~Should be rephrased to something like: “Specifically, we intend to
investigate three research questions” – the three should then be
enumerated 1, 2, and 3.~~

“Minimal hardware requirements sufficient for the emergence of effective
cooperative behaviour”

-       This question doesn’t say anything about the evolution of a controller
within the constraints of a robot’s morphology – this research question
should be elaborated upon so as to mention that a given robot’s controller
will be evolved given the constraints of experimenter defined (minimal)
morphology.

“Optimal indirect communication method for maximising cooperative behaviour”

As I recall from the presentation this has changed to something about
sensor sensitivity – Given this, the new research question should clearly
state what is meant by this and the relation to controller evolution
versus morphology – i.e. – is it fixed, but hand crafted – with variable
sensor resolutions/sensitivity, like in the first objective?

~~“Optimal sensor configuration/morphology for maximising cooperative
behaviour”~~

~~“sensor configuration” can be used instead of morphology” – instead of
“maximising cooperative behaviour” – rephrase this to say something like
“evolving cooperative behaviour that achieves the highest group task
performance.”~~

###2.1 Minimal Hardware Requirements

“What is the minimal level of agent complexity, in terms of the required
hardware, that is sufficient for the evolutionary emergence of cooperative
behaviour?”

Rephrase this to make it clear that you are evolving individual robot
controllers within the constraints (minimal configuration) of fixed
(hand-crafted) morphologies – Also, will each robot have the same
morphology or can they be different?

[panait] -> [?]

“The question then becomes: is the process of evolution sufficiently
intelligent to
be able to work around the limitations of a minimalistic agent design?”

Get rid of “intelligent” – and simply rephrase this question as something
like – is artificial evolution an effective process for adapting
controller design within the constraints of minimalistic agent (robot)
morphology.

My research topic…” -> “The first research question…”

“…viable set of sensors…” – and actuators or just sensors?

###2.2 Optimal Indirect Communication Type

~~This section needs to be rewritten since the research has changed –
significantly – right?~~

###2.3 Optimal Sensor Morphology

~~“Does evolving both the agent controller and sensor morphology have
advantages over evolving the controller alone in a cooperative coevolution
task?”~~

~~It is not a cooperative co-evolution task, but rather a task that requires
cooperative behaviour, or at least benefits from cooperative behaviour.~~

~~“Ordinarily, the evolutionary algorithm in an evolutionary robotics
simulation is used to evolve the controller for the robotic agents. The
agents sensor configuration (such as the…”~~

~~Rephrase this paragraph to make it clear that morphology is both sensor
and actuator configuration (however, practically you’ll need some minimal
actuator setup, otherwise the robots wont be able to move).~~

~~“Some work has focused on this question but little research has focused on
the application of concurrent controller and sensor configuration
evolution to multi-agent simulations.”~~

~~Clarify this to say controller and morphology co-evolution with respect to
tasks that require cooperative behaviour, or benefit from cooperative
behaviour.~~

##3. Procedures and Methods

###3.1
Remove all personal pronouns – rephrase:
“The goal of the method I will be using,” to something like:
“The method for the first research question will be…”

“The end result of the above method, is a set of task fitness values and
convergence times, for each agent configuration, for each task. The
box-and-whisker plots of these can then be plotted against each other to
clearly indicate the answer to the research question: what is the minimal
viable hardware configuration?”

You don’t need to say what types of plots you’ll be using – this can be
removed – However, you should make it clear how exactly convergence time
will be measured.

###3.2

Given the new research question – are the methods still the same? – At any
rate this section needs to be revised to account for the variable sensor
sensitivity/resolutions? – that will be tested – and how such variation of
sensor sensitivity (if this is what is intended) will be implemented.

###3.3

~~Replace concurrent evolution with co-evolution of robot controller and
morphology.~~

~~“I hope to show” -> “The experimental goal is to show…” (or something
similar)~~

~~Also, note that MASON does not include any implementation of Khepera
robots – so that would have to be implemented.~~

##5. Related Work

Sections 5.1, 5.2 and 5.3 need to be expanded to include more than a
couple of references (5.3 is ok, but needs another paragraph or two
briefly describing other approaches) – Same goes for 5.1 and 5.2 – concise
descriptions of previous approaches are needed – in the case of 5.1, GP
approaches for controller evolution for cooperative behaviour – in the
case of 5.2 – approaches that test different sensor types in a multi-agent
(cooperative behaviour) context – since the related work is no longer
about indirect (stigmergic) communication, right?

~~“The existing work sets out some examples of how to go about sensor
morphology evolution”~~

~~Did this sentence get lost and is looking for a home?~~

##6. Anticipated Outcomes

###6.1

“This particular research question has no clear success or failure criteria;”

Really?

Should mention that agent (robot) designs can be compared with those
evolved (6.3) and that one outcome maybe that it is simply easier to
hand-craft morphologies for simple versions of the task, however as the
task becomes more complex, then co-evolution of controller and morphology
may yield design benefits (that a human design wouldn’t necessarily think
of..).

###6.2

These anticipated outcomes have changed – right?

###6.3

Same comment as for 6.1.

## Addendum
Gantt chart is difficult to read…
