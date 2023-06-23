# Experimental Design

## Introduction

Researchers must carefully consider the design of their study before
initiating experiments or collecting observational data. After
formulating a hypothesis, researchers should answer the following
questions: what type of data will need to be collected to assess the
hypothesis, what are the spatial and temporal dimensions of the study,
what treatments (if any) will be used and how will they be applied, how
will study areas or individual animals be selected for study, what
sample sizes will be required, what are the potential sources of error
which could affect the data collection process, how can these potential
sources of error be accounted for, and what are the appropriate
statistical methods for analyzing the data. The process of experimental
design is critical for ensuring that inferences generated from the
collected data will properly assess hypotheses. Inappropriate
statistical methods are relatively easy to rectify if the study design
and data collection are sound; however, there may be little that can be
done statistically to rectify a flawed study design. After designing
your study, solicit review from peers with expert knowledge of your
methods or study system. Consulting a statistician when designing a
study may also be helpful. Soliciting advice and review from experts can
help to improve the design of a study and rectify any overlooked
methodological issues before data collection starts. During this
process, researchers should carefully consider the three cornerstones of
experimental design (Johnson 2002): 1) Randomization, 2) Replication,
and 3) Controls.

## Randomization

Randomly assigning treatments to units is a fundamental cornerstone of
experimental studies. Indeed, it is the ability of the researcher to
randomly assign treatments that separates experimental studies from
observational studies. Randomly applying treatments to units is
important for preventing conscious or unconscious researcher bias from
affecting the results. Imagine a study testing the hypothesis that
providing corn at feeding stations will increase overwinter survival of
eastern gray squirrels (*Sciurus carolinensis*). We have 20 study plots
available, 10 of which will be continuously supplemented with dried corn
throughout the winter while the other 10 will not. Some study plots are
far off the road and require a substantial hike through the woods to
reach, while others are situated along the road. Because carrying bags
of corn through the woods is difficult, we decide to supplement corn at
the 10 plots nearest to roads. The problem with this design is that we
have introduced bias by selecting experimental plots nearest to the
roads instead of at random. Squirrels living near the road may naturally
suffer higher rates of mortality from car collisions irrespective of
food abundance. Our data may actually show lower survival in treated
plots and we may erroneously conclude that corn supplementation
decreases survival of squirrels; however, these results are a
consequence of poor study design. A more appropriate design would be to
randomly select plots for food supplementation, regardless of difficulty
of access. Treatments can be randomly selected using a random number
table or random number generator, which are widely available online and
are included in many software packages.

True randomization is not possible for observational studies, as
treatments cannot be applied to units. Surveying abundance of western
capercaillie (*Tetrao urogallus*) across an elevational gradient would
be an observational study because researchers cannot randomly assign
some locations to be at a high elevation and some to be at a low
elevation. This is not to say that randomization is unimportant for
observational studies; other aspects of randomization can be
incorporated into the design of both observational and experimental
studies to reduce bias. We may not be able to randomly assign the
elevation of potential study locations in the grouse example; however,
if we have a pool of potential survey areas at high and low elevations,
we could randomly select a subset of study locations within each
elevation band.

## Replication

Replication is the process of conducting experimental manipulations or
observations on multiple, independent units. Appropriate levels of
replication must be enacted within all combinations of treatment groups
(or other explanatory variables) relevant to the research hypotheses.
For example, if a researcher is interested in studying the interaction
between food supplementation and predator removal on population growth
rates of northern bobwhites (*Colinus virginianus*), they would need to
establish multiple study plots for each of the four combinations of food
and predator control treatments (food supplemented/predators removed, no
food supplemented/predators removed, food supplemented/no predators
removed, no food supplemented/no predators removed). Replication is an
essential component of both experimental and observational studies for
several reasons. Replication allows researchers to assess the variance
among units within a treatment group, which is a prerequisite for all
statistical analyses. Moreover, replication reduces the effects of
random chance on the response variable. Researchers are generally not
able to measure every individual in a population, or every potential
study area across the landscape. Instead,researchers generally sample a
subset of the available units and use the measurements from this subset
to estimate the mean of the entire population. Environmental systems are
complex and variable over space, time, and between individuals, so
single observations may represent unusual outcomes rather than the
population mean. Imagine that we are interested in estimating the
juvenile survival and sources of fawn mortality for a mule deer
population (*Odocoileus hemionus*) and we deploy a radiocollar on a
single fawn. If we found that this fawn was killed by a predator, we
would not conclude that all fawns in this population are killed by
predators. If instead we collared 100 fawns and found that 55 survived,
31 were killed by predators, 6 were killed by vehicle collisions, and 8
died from starvation or disease, the higher number of replicates would
allow us to more confidently conclude that our results are
representative of the actual population values.

Increasing the number of replicates will increase the precision of
population estimates; however, increasing the sample size comes with
increased costs and effort. An important question when designing
experiments is then: what is the sufficient level of replication that
balances precision of estimates with the cost and effort of conducting
the study? The minimum sample size will vary by study, though it may be
estimated by performing a prospective power analysis during the design
phase. Power analyses estimate can estimate the minimum required sample
size for a study based on two parameters: 1) the desired or expected
magnitude of the difference between treatment groups, and 2) the
expected variance between units within treatment group. See Steidl &
Thomas (2001) for a detailed description of power analyses. The
question, then, is how to estimate the expected variance and difference
between treatment groups before collecting any data. Researchers can use
estimates derived from published literature in a similar study system
with the same or similar species. For example, researchers designing a
study on the effects of predator removal on the survival of northern
bobwhites in Iowa may be able to estimate the minimum number of
radiotransmitters to deploy based on published estimates of the variance
and survival of bobwhites in high-predator and low-predator habitats
from Georgia. If time and funds are sufficient, researchers could also
perform a small-scale test of the methods and data-collection procedures
before the main study. These pilot studies are valuable for power
analyses, as they collect preliminary data on the group means and
variance that are likely to be observed in the main study. In addition
to informing prospective power analyses, pilot studies also allow
researchers to assess the feasibility of the study design and identify
previously-overlooked methodological issues before the main study
commences.

    **Comment: I tried to keep the discussion of the power analyses simple here so I omitted discussing type I and II error rates (since those are set by the researcher in the design phase). I could bring them up, but would require a much more in-depth discussion. Are error rates brought up anywhere else? Also, I could add a section discussing how retrospective power analyses are not really valid, though this would require discussion of power.**

Though replication is imperative in scientific studies, researchers must
be careful to avoid pseudoreplication. True experimental replicates are
independent of each other; however, pseudoreplication occurs when
measurements which are not independent are treated as independent in
statistical analyses (Hurlbert 1984). The consequences of
pseudoreplication include overestimating precision and falsely
concluding that there is a treatment effect when there is none (Heffner
et al. 1996). Preventing pseudoreplication requires correctly
identifying the experimental unit of a study, which is the lowest
experimental level in which units are independent from others. The
experimental unit is the level at which the treatment is applied in
experimental studies, though care must be taken when identifying the
experimental unit in studies with multiple levels of treatments. Imagine
a study where different herbicides are sprayed on a series of forest
patches, and 4 study plots are established within each patch. Each study
plot is then selectively logged at a different thinning rate. The logged
plots within each forest are not independent, as they are exposed to the
same broad herbicide application. The individual forest patches are the
experimental unit of analysis while the logged plots are considered
subunits. Importantly, increasing the number of subunits will not
increase the levels of replication nor the statistical power of a study;
replication is increased only by increasing the number of experimental
units.

In some cases, non-independence between observations may be readily
apparent. The locations of individual bison (*Bison bison*) in the same
herd would clearly not be independent of one another, and treating them
as independent would constitute pseudoreplication. In other cases,
pseudoreplication may be less obvious. Imagine that we are designing a
study to assess the effects of selective logging on the body mass of
ruffed grouse (*Bonasa umbellus*). We identify a forest stand which has
recently been logged and a forest stand which has not been logged, and
in each stand we capture and weigh 30 grouse. We find that the average
mass of the 30 grouse in the logged stand is 377 g and the average mass
of the 30 grouse in the logged stand is 363 g. Doing a t-test with a
sample size of 30 for each treatment, we get a p-value of 0.03 and
conclude that grouse are heavier in selectively-logged stands. The issue
is that, even though we weighed 60 grouse, the treatment (presence or
absence of logging) is applied at the level of the forest stand. Grouse
within a stand are exposed to the same logging application and so are
not independent. The individual forest stands are the experimental units
of analysis while individual grouse are subunits. Even though we have
measured 60 grouse, we only have one forest stand in each treatment. We
have no replication at the level of the experimental unit, and applying
a statistical analysis is inappropriate. We have vastly overestimated
our sample size by treating each of the 60 grouse as independent.
Capturing and weighing more grouse in each patch will not help to
resolve this issue; the only way to increase the number of replicates is
expand our study area to weigh grouse in more logged and unlogged
stands. An appropriate method to avoid pseudoreplication would be to
identify 10 stands which have been recently logged at similar thinning
rates and 10 stands which have not been logged. In each one, we capture
and weigh 30 grouse. We then average the weights across grouse in each
stand to get a single weight value for each experimental unit. We can
then perform a t-test between the average weights of grouse in the 10
logged stands and the 10 unlogged stands.

Though subunits should not be treated as independent replicates,
increasing the number of subunit measurements provides other benefits
for statistical analyses. Sometimes, the variance within experimental
units is of direct interest for studies, e.g., assessing how the
variation in grouse weight rather than mean weight differs between
logged and unlogged stands. In this case, measuring multiple subunits
within each experimental unit would be required to estimate variance.
Taking repeat measurements within experimental units also helps to
reduce stochastic error and more accurately estimate the mean response
in the experimental unit. If we had only captured and weighed one grouse
in each forest stand there is no guarantee that the bird would represent
the population mean; the single grouse may be very light or very heavy.
Measuring 30 birds at each site, however, would likely lead to more
accurate estimates of the stand-level average. The important distinction
to remember is that increasing the number of subunits may increase the
accuracy of measurements within an experimental unit but does not
increase the number of replicates or statistical power.

Replication may be not be feasible in some cases, especially when
assessing hypotheses over broad temporal or spatial scales. Researchers
studying ecosystem-level processes, for example, may often be limited to
a single ecosystem due to the difficulty and cost associated with
manipulating and studying entire ecosystems. In other cases, a study may
be planned to asses the effects of some future development or treatment.
If a dam is scheduled to be built along a river, researchers may assess
the ecological effects of the dam by surveying the fish community before
the dam is constructed and then re-surveying the community after
construction has finished. Similar before/after fish surveying should
also occur in a nearby river which has not been dammed; this will help
assess if changes in the fish community are due to the dam or due to
other sources of variation (i.e., increased pollution from the
surrounding area, introduction of invasive species, etc.). This
experimental protocol is referred to as a BACI design (before-after,
control-impact) and can be a powerful method for assessing the effects
of a single treatment (Stewart-Oaten and Bence 2001); however, it is
inherently unreplicated. There is only one dammed river, and it is
obviously unfeasible to dam more rivers to try to increase the number of
replicates. This lack of replication does not imply that ecosystem-level
or BACI studies are not informative; in fact, unreplicated studies may
be highly valuable and are often the only way to study large, complex,
or difficult-to-manipulate systems (Hurlbert 1984, Johnson 2002). The
important point is that researchers must be careful about generalizing
results from an unreplicated study (Hurlbert 1984). The results from the
BACI study described above may show that the fish community changed
after dam construction, but the results apply only to the effects of
that particular dam. Without replication, there is no way of assessing
if the results from this particular dam are reflective of general
effects of dams on fish communities.

## Controls

The word “control” can apply to multiple different topics in
experimental design (Johnson 2002). One of the most common uses is to
refer to a control treatment, which is an experimental unit that has
either received no treatment or a sham treatment. Proper control
treatments are a critical component of experiments, as they provide a
baseline value with which to compare results from experimental
treatments. If we are interested in determining how vegetation cover
affects nest success of common pheasants (*Phasianus colchicus*), we
could locate 30 nests, remove 50% of the vegetation within 2 m of the
nest, and monitor nest success. We may find that the success rate of
these manipulated nests is 7% (95% confidence intervals ranging from 4 –
24%), but this value is uninformative on its own. Maybe pheasants
normally only fledge 7% of their nests, and our manipulations had little
effect. In order to discriminate the treatment effect, we need a control
treatment to determine the baseline nest success in this population. If
we monitor an additional 40 unmanipulated nests and find that the nest
success of these control nests is 40% (95% confidence intervals ranging
from 26 – 56%), we can determine that reducing vegetation cover
decreased nest success. Observational studies cannot have true control
treatments; instead, inferences are drawn by assessing how the response
variable is affected by variation in the explanatory factors. For
example, a resource selection study may compare the vegetation
composition and structure between locations used by radio-collared deer
and locations in nearby unused areas. Similarly, a researcher could
estimate the survival of adult northern bobwhites in patches which vary
in hawk density to assess the effects of hawk predation on bobwhite
survival.

Proper inferences depend on control and experimental treatments
differing ONLY in the experimental variable of interest. An
unmanipulated treatment may therefore not serve as an appropriate
control. Suppose we are concerned that the the added weight from
deploying radiotransmitters on breeding female black-throated blue
warblers (*Setophaga caerulescens*) increases stress and causes them to
abandon their nests. The most reliable way to catch and deploy
transmitters on breeding females of this species is to locate their
nests, place a mist-net nearby, and flush them off their nest into the
net. We perform a study locating 50 nests and randomly assign 25 to the
experimental treatment. We then go out to these experimental nests, set
up a net, flush the female, and attach a transmitter to her. For the 25
control nests, we continue monitoring the nests but otherwise do not
manipulate them. We find that females abandonment occurred at 6 of the
25 experimental nests but only 1 of the 25 control nests, so we conclude
that transmitter deployment increases rates of nest abandonment. This
conclusion is problematic because our control treatment differed from
the experimental treatment in more than one way: experimental females
were fitted with transmitters AND were flushed off their nests,
captured, and handled by the researchers. The increased nest abandonment
rates could have been due to attaching transmitters; however, the
increased rate of nest abandonment could also be due to the disturbance
around the nest. There is no way to separate these possible effects
under the current study design. A more appropriate control treatment,
capturing and handling females at all nests but only deploying
transmitters at experimental nests, would allow for discrimination
between these two potential mechanisms. Similarly, an appropriate
control for a food-supplementation study would be to establish and
periodically visit feeding trays in both experimental and control plots,
but only supply food at the experimental trays. This type of control
would allow researchers to discriminate between the actual treatment
effect and any inadvertent effects related to carrying out the
experiment (e.g., human disturbance, neophobia, etc.). When designing a
control treatment, researchers should endeavor to keep the experimental
methods as similar as possible between experimental and control units so
that only the factor of interest varies.

The word “control” can also refer to mitigating the effects of
extraneous variation on the study results. Extraneous variables are
those that affect the response variable but are not the main variable or
variables of interest. Imagine that we wish to assess insecticide
spraying affects the body condition of a forest-dwelling insectivorous
songbird: the red-eyed vireo (*Vireo olivaceus*). Our study takes place
in a heterogeneous landscape with forest patches surrounded by
non-forest (Figure 1.1) . We identify 28 study plots scattered among the
8 forest patches, 14 of which we randomly assign to the experimental
group and 14 of which we randomly assign to the control group. We fly a
helicopter over each study plot, spraying insecticides over experimental
plots and water over control plots. We capture and weigh vireos in every
study plot two weeks after spraying. WE then calculate the average vireo
mass for each plot. This study design incorporates randomization,
replication, and an appropriate control treatment; however, many
environmental variables may affect the body mass of vireos besides just
the insecticide treatment. Maybe some forest patches are lower-quality
habitat for vireos than are others (naturally lower food levels, higher
predator density, sub-optimal vegetation, etc.). In this case, vireos in
poor-quality habitats might be expected to have lower body mass than
birds in high-quality habitats regardless of the insecticide treatment.
If we do not account for this confounding variable, then we may find
that the majority of control or treatment plots are located in
poor-quality habitats just by random chance (Figure 1.1 A). This would
lead us to erroneously conclude that insecticide application does not
affect vireo mass (Box 1.1 A) simply because the effect of the
insecticide treatment is conflated with the effect of habitat quality.
Researchers must always consider potential sources of extraneous
variation and how these can be controlled for when designing studies.

Sources of extraneous variation can be controlled for statistically or
through modifications of the study design. In the vireo example, the
extraneous effect of habitat quality could be removed from analysis by
modifying the study design to only sample in either high-quality or
low-quality habitats (Figure 1.1 B, Box 1.1 B). This method of
restricted sampling may be impractical in many cases, especially if the
number of possible sampling locations is small relative to the number of
confounding environmental gradients. Extraneous variables may also be
controlled through a process called blocking, wherein experimental units
are grouped into relatively homogeneous units. If we think that patches
differ in habitat quality, and these differences may introduce
extraneous variation into our analysis, we can treat each forest patch
as a “block” and distribute control and experimental treatments randomly
within each block (Figure 1.1 C). Distributing control and experimental
treatments evenly across blocks ensures that the effect of the block on
the response variable is evenly distributed across treatments. Moreover,
we can account for the variation introduced by the block during
statistical analyses. Including habitat quality as a covariate in the
statistical model allows us to separately estimate the effects of
insecticide application and habitat quality on vireo mass (Box 1.1 C),
thereby leading us to correctly conclude that insecticide use has an
effect on vireo body mass.

![Figure 1.1. Example study designs distributing experimental (E) and
control (C) study plots across patches varying in habitat quality.
High-quality patches are green while low-quality plots are blue. Study
designs differ in how they control for extraneous envrionmental
variation: not accounting for envrionmental variation (A), accounting
for environmental variation by restricting the effects to a single level
of habitat quality (B), or accounting for environmental variation
through blocking across levels of habitat quality
(C).](BlockingFigure.png)

![Box 1.1. Example R-code showing the effects of controlling variation
through restricting sampling and blocking. In this example, we wish to
assess the effects of insecticides on the body mass of red-eyed vireos
(Vireo olivaceus). Study plots are distributed across 8 different forest
patches which vary in habitat quality.](blocking.png)

Blocking is not just valuable for experimental studies, but should be
carefully considered when designing observational studies as well.
Imagine a study surveying clearcut and mature forest patches in
mountainous areas to determine how the abundance of rabbits is affected
by logging. We may reasonably expect that rabbit abundance will vary
with elevation in this study. We could incorporate blocking to control
for this extraneous variation during the design phase of the study; for
example, by pairing each clearcut patch with a nearby mature forest
patch of similar elevation. Implementing a blocked study design is a
powerful method of accounting for known or hypothesized confounding
variables in both experimental and observational studies, but can also
help guard against extraneous variation from unforeseen environmental
variation (Hurlbert 1984).

Not all sources of extraneous variation can be easily controlled for
through modifications of the study design, but many of these may be
controlled for during statistical analyses. If we are studying the
effects of age on late-winter survival of mourning doves (*Zenaida
macroura*), we may capture doves in the summer, age them as either
juveniles or adults based on plumage characteristics, deploy
radiotransmitters, and track them throughout the late-summer to
determine survival rates. Survival is likely to dependent on multiple
environmental factors besides age; for example, survival may also be
positively correlated with body size and local food abundance. We could
attempt to control for these sources of extraneous variation by blocking
doves into different levels of food abundance and size classes, though
it may be difficult and costly to catch and track enough juvenile and
adult doves in each food/size class to provide adequate replication.
Food availability and size are also continuous variables, so it is more
appropriate to treat them as such in the analyses. In contrast to
blocking designs, these continuous extraneous variables can easily be
controlled for in statistical models (Box 1.2). Similarly, the
probability of detecting individuals during a survey is often dependent
on environmental conditions. When performing avian point counts, for
example, the probability of birds singing and being detected by
observers can depend on factors such as the time of day, precipitation,
temperature, wind speed, and background noise. Careful experimental
design may reduce some of this extraneous variation (only doing surveys
in the morning, not doing surveys in heavy rain or wind); however,
blocking or performing all surveys under the exact same environmental
conditions is clearly infeasible. Statistical control during analyses is
needed to account for these environmental variables. Researchers may not
always known *a priori* all environmental gradients affecting the
response variable; therefore, it is good practice when collecting data
to record as much information about environmental conditions as
possible. It is generally better to collect extra data that ultimately
is not used then it is to collect insufficient data and end up regret it
later.

![Box 1.2. Example R-code for controlling extraneous variation during
statistical analyses. In this example, age-related differences in
late-summer of survival of mourning doves (Zenaida macroura) are of
interest; however, body size (as measured by wing length) and food
abundance also affect survival.](statisticalcontrol.png)

## References

Heffner, R.A., Butler, M.J. and Reilly, C.K., 1996. Pseudoreplication
revisited. Ecology, 77(8), pp.2558-2562.

Hurlbert, S.H., 1984. Pseudoreplication and the design of ecological
field experiments. Ecological monographs, 54(2), pp.187-211.

Johnson, D.H., 2002. The importance of replication in wildlife research.
The Journal of Wildlife Management, pp.919-932.

Steidl, R.J. and Thomas, L., 2001. Power analysis and experimental
design. Design and analysis of ecological experiments, 2, p.415.

Stewart-Oaten, A. and Bence, J.R., 2001. Temporal and spatial variation
in environmental impact assessment. Ecological monographs, 71(2),
pp.305-339.
