# R in Ministry

Author: Piotr Nowosielski (Ministry of Health Republic of Poland)

Co-authors: Michal Walczynski, Mariusz Zieba, Klaudiusz Witczak, Filip Wojciechowski

# Description

The R language was introduced in the Analyses and Strategies Department of the Ministry of Health in 2015.
Since then MS Excel is no longer used as an analytic tool.

1. Why R?
    a) Short transition description from Excel to R
        i. Big data handling
        ii. Dierent data sets
    b) Short transition description from classical statistics to machine learning methods
        i. Basic analyses already shown on the online platform .
        ii. More complex problems waiting for being solved

2. Implementation examples:

a) Patient's paths analyses

Deriving care pathways for a specic disease from administrative data might be troublesome due to the
abundance of non-informative entries in patients' long-term history. Therefore, such data necessitates
an aggregation method that provides a comprehensive overview of individuals' progression through the
public healthcare system accompanied by a compelling visualization. The data for consecutive years were
aggregated using stochastic processes with the underlying assumptions:
  * the process does not acknowledge individuals' history except the last visit in the healthcare system, i.e. it is memoryless (also known as the Markov property);
  * care pathways are modelled in form of state transition probabilites, whereas exclusive events in history such as a visit in primary care, ambulatory care, an undergone medical procedure etc. constitute the states;
  * state transition probabilites are non-zero which accounts for the fact that the patients can move between each and every state, inclusive of recurrent visits to the same state;
  * transition matrices are transformed into directed complete graphs wherein the vertices correspond to particular states and the edges to state transition probabilites.

These simplifying assumptions can be treated as neglibile in view of an extensive sample size.

b) Stroke departments prediction model

In order to receive thrombolysis (life saving service), the patient who underwent the stroke should arrive
within 4 hours of the incident on a stroke unit. The Ministry of Health data shows the patient's place of
residence at the commune (Polish gmina) level. Due to a low population density in some areas of Poland
the model structure must take more aspects into consideration.
This model contains approximately 6.5 thousand linear restrictions by 6.5 millions of decision variables. In
addition, the objective function has been dened to minimize the distance between a patient (in a straight
line) to a unit. Hence, naturally, linear programming methods are applied. 

