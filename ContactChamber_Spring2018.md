# Contact Chamber, Spring 2018
#### Cheer Tsang, Yeonjin Yun, Canaan Delgado
#### April 21, 2018

<div class="alert alert-block alert-danger">
Please do not delete my comments. Address them for the next submission and then I will use the comments to check for corrections. If you disagree with my comments, just add one below mine.
</div>

## Abstract
When coagulant is introduced to turbid water, coagulant nanoparticles attach to suspended solids in the water. The coagulant will promote the sticking of partcicles so that the collision probablity may increase. As more collisions occur, these particles continue to adhere to each other, promoting the growth of flocs. However, a substantial portion of the coagulant dose adheres to the flocculator walls rather than influent particles, requiring a higher than necessary coagulant dose to compensate for this effect. In order to minimize the amount of coagulant wasted, an apparatus called the contact chamber was fabricated to increase the probability of collisions between the influent particles and coagulant by increasing residence time. The Spring 2018 Contact Chamber team analyzed the performance of the newly redesigned contact chamber by analyzing the headloss across the flocculator with and without the contact chamber.

## Introduction
In normal conditions, the AguaClara plants typically operate at a relatively low influent turbidity. However, the plants operate at optimal efficiency with a high influent turbidity; this is due to the fact that with a higher concentration of suspended solids at the influent, there is a greater probability that the particles in the water will come in contact with the coagulant nanoparticles. Therefore, at low influent turbidity conditions, the coagulant has a lower probability of coming into contact with influent particles. The excess coagulant that does not adhere to the influent particles instead attaches to the walls of the flocculator, resulting in coagulant buildup within the flocculator. This issue also occurs in low flow rate systems, such as the 1 L/s plants.

In order to minimize the amount of coagulant lost to the flocculator walls, the amount of coagulant that adheres to the influent particles must be maximized. One possible solution for this is adding a contact chamber, which would allow the coagulant to mix with the influent prior to entering the flocculator. Reducing the amount of coagulant that adheres to the walls of the flocculator would reduce the amount of coagulant wasted, thereby reducing plant operation costs.

In order to quantitatively measure the impact of coagulant attaching to the walls of the flocculator, headloss across the flocculator can be measured to determine the amount of coagulant buildup. As excess coagulant adheres to the inner walls of the flocculator, the coagulant buildup effectively causes a decrease in the pipe diameter (Figure 1).

![Headloss_diagram](https://github.com/AguaClara/contact_chamber/blob/master/Diagrams/Headloss_diagram.png?raw=true)

Figure 1: Coagulant buildup on the inner pipe walls of the flocculator causes a decrease in the pipe diameter, which increases headloss.

The decrease in pipe diameter causes an increase in headloss due to the Darcy-Weisbach equation:

$$ \Delta h = \frac{f_DLV^2}{2Dg} $$

where delta h is the pressure loss in meters, $f_{D}$ is the Darcy friction factor, L is the pipe length in meters, D is the hydraulic diameter in meters, V is the fluid flow average velocity in m/s, and g is the standard gravity. As the hydraulic diameter, D, decreases due to the buildup of coagulant, the pressure loss, delta h, increases. Therefore, the more coagulant that builds up on the pipe walls, the more headloss is observed. The change in headloss can then be used as a measure of the amount of coagulant that builds up on the walls.

Currently, the AguaClara plants are not using contact chambers because there has not been enough evidence to support the utility of it. Previous semesters have had mixed results in demonstrating that the contact chamber significantly reduces the amount of coagulant that adheres to flocculator walls. We made changes in our experiments this semester to rectify inconsistencies and reduce the potential for error. We hope that in the future after this semester's series of experiments, we will be able to determine with certainty the efficacy of the contact chamber and introduce the device to the AguaClara plants. It is hypothesized that the addition of the contact chamber will result in a lower increase of headloss; thus, less coagulant will adhere to the walls of the flocculator, and the plant will run more efficiently.

<div class="alert alert-block alert-danger">
Avoid first person
</div>

## Literature Review
The drinking water treatment processes are coagulation and flocculation, sedimentation, filtration, and disinfection. In the first steps, coagulation and flocculation, particles aggregate together to form larger particles. The coagulation and flocculation process allows maximum aid in removing sediment particles in water before the filtration process. In the late 1940’s, a new theory was developed that distinguished two modes of removing colloidal impurities. This process, double layer compression, also known as coagulation, has been widely known to be cost-effective and has revolutionized the water treatment process (Balik and Aydin, 2015).

<div class="alert alert-block alert-danger">
I would eliminate the word new since you talk about coagulation in the previous sentence.
</div>

Coagulation describes the overcoming of the repulsive forces between the particles to adhere together and precipitate. Stable particles of clay and organic substances found in influent raw water are negatively charged, causing particles to repel each other and remain suspended in solution. As positively charged coagulant is added to the water, the negative charges are neutralized, allowing the particles to adhere together into aggregations called “microflocs" (Jiang, 2015).

The coagulants that are normally used for drinking water treatment tend to be predominantly inorganic salts of aluminum or iron, alum in particular being the most ubiquitous. When these coagulants are introduced to water, the aluminum ions have a tendency to hydrolyze in an unstable manner, eventually forming “a range of metal hydrolysis species.” AguaClara plants utilize polyaluminum chloride (PACl), a more commercially available polymeric aluminum coagulant.

<div class="alert alert-block alert-danger">
Where does this quote come from?
</div>

In a study of coagulation kinetics, batch experiments were conducted to examine the different ways that PACl and alum destabilize particles and the different factors that affect how quickly particles are destabilized. At low temperatures, PACl can be advantageous over traditional coagulants because temperature fluctuation has less of an impact on the coagulant efficacy. Previous research showed that the rate of collisions between particles is slower than the rate of particle destabilization; thus, the rate at which collisions occur is the rate-determining step. Therefore, the efficiency of the coagulation process depends on the rate of collisions, and as a result, optimizing the collision rate would have the greatest impact on coagulant efficacy (Pablo Cañizares, 2007).

After the coagulation process, the process of ‘precipitate enmeshment,’ also known as flocculation, begins. The rapid mixing stage can be considered one of the most vital components of the coagulation-flocculation processes. At this stage, primary flocs tend to form and destabilization reactions occur (Jiang, 2015). The smaller particles are physically enmeshed by the metal precipitates previously introduced. This process causes the particles in the water to aggregate and form flocs.

<div class="alert alert-block alert-danger">
What is the rapid-mix chamber? Is that the contact chamber?
</div>
- No, I guess I did not know about to word it correctly (in the lab, the portion that shoots coagulant through the system about 20 RPM).

<div class="alert alert-block alert-danger">
Just clarify in the report.
</div>

Parameters, such as pH, temperature, alkalinity, composition of precipitates and mixing speeds can impact how effective the coagulation process is. Previous research shows that alum coagulant performs at its maximum capacity when immersed within a solution of pH levels between 6 and 7. Coagulant, when introduced to high alkalinity water, may need to be used in large amounts to stabilize pH at an optimal level. This is important because if an insufficient amount of coagulant is administered, many problems can occur, such as pipe corrosion, pH destabilization, and the formation of residues that can clog pipes. Residues may be the coagulant itself or the accumulation of influent particles that may be too large to remove and restrict flow through the pipe. Another parameter that can dictate the quality of the coagulation-flocculation process is temperature. Lower temperature waters tend to “decrease the hydrolysis and precipitation kinetics” (Hart, 1979).

A recent study proposed a new method of regulating pH and coagulant: "A multiple model predictive control (MMPC) strategy is proposed for coagulation control in water treatment plants. The proposed control strategy is developed to work effectively with different local operating regions of the chemical dosing unit where coagulation takes place" (Bello et al., 2014). The method involves controlling the surface charge and pH values of chemically treated water at the same time. By being able to assess the pH values and  surface charges simultaneously, operational costs and the amount of waste can be reduced. Similarly, the improvement of water quality can be enhanced, and thus the coagulation control can be effectively implemented. So yes, in theory there should be a way to regulate the pH levels themslves apart of the actual coagulant itself, which is much more cost effective given the price for coagulant.


<div class="alert alert-block alert-danger">
REmove the word "yes" in the last sentence
</div>

Through flow and tracer transport methods, vorticity field, a microscopic measure of rotation (vector) at a given point in the fluid, is determined to be the key parameter to use to discern areas of jet flow (where the water speed travels in a much faster, concentrated area) and recirculation zones (where the water circulates repeatedly) within the contact chamber. The vorticity gradient and the flexion product, the result of a bending movement around a 'joint' within the piping, shed the most mathematical insights on the topic of differentiating recirculation and jet zones, as well as fluid to fluid flow separations. From this, the team will have a mathematical analysis of the validity behind the qualitative results. The ratio of t90/t10, or the Morrill index, describes the travel time of 10% and 90% of the cumulative normalized tracer concentration observed at the outlet of the contact chamber.

<div class="alert alert-block alert-danger">
Split up first sentence into two.

What are the sources for this paragraph?
</div>

Understanding all of these terms is vital to how the function of the contact chmaber may play a huge role in water treatment efficiency. If allof these factors weren't taken into consideration, the way that the contact chamber would function could be skewed and could ultimtely prove to be a waste of resources and time.

<div class="alert alert-block alert-danger">
Revise first sentence for readability.

Where is your source for this paragraph?

Lots of jargon here that you need to explain/define: vorticity field, flexion, jet zones

Why do all of those things matter?
</div>

<div class="alert alert-block alert-danger">
I propose we get rid of this paragraph - CT

If you do not get rid of the paragraph, then please address the above comments for the final!
</div>

The basis with which the indices were characterized was classified as a "black box" analysis since the mechanisms of mixing within the contact chamber were overlooked or not analyzed. The objective of this experimental analysis of behavior of the conservative tracer in the contact chamber is to note the mixing of the chemical within recirculation zones where the tracer is briefly retained before release, as well as the interactions between the jet zones and recirculation zones. Identifying these interactions were important because they both played a role in the aggregate mixing process. The difficulties posed in this analysis were the monitoring methods utilized in literature. The index bases were derived by measurements made only at specific outlet points throughout the system. There was no data highlighting the mechanics of mixing within the contact chamber itself (Demirel and Aral, 2016).

<div class="alert alert-block alert-danger">

<div class="alert alert-block alert-danger">
Get rid of this paragraph too, or explain better - CT
</div>
-I believe that understanding hwo everything interacted and what they did when they were brought together would provide some more clarity into what we were doing. I changed it a little so it made more sense!

NM - Changes make things clearer. I recommend reorganizing it a bit for flow and understandability. Also feel free to delete comments in this area only because it is getting confusing having so many!
</div>
- Sorry about the source kind of being crammed into the paragraph. Just like in an earlier comment, I just shifted it to the end because it covers the whole topic of discussion and for clarity purposes.

<div class="alert alert-block alert-danger">
Definitely improved but continue to revise because it is difficult information to digest. I recommend that you redefine "indices" as the ones talked about two paragraphs ago or move the middle paragraph to the end.

Is the experimental analysis in sentence two you analysis or?
</div>

##Previous Work

In previous semesters, the AguaClara contact chamber subteams have assessed the efficacy of the addition of a contact chamber before flocculation in order to promote greater collision frequency between the coagulant nanoparticles and the suspended solids. It was hypothesized that increasing residence time would promote collisions (Akpan et al., 2017).

The current contact chamber was modified from the contact chamber designed by the Spring 2017 subteam. The contact chamber has a diameter of 2.54 cm (1 in) and a length of 25.4 cm (10 in). The length of the contact chamber is ten times the diameter to model the length of the turbulent jet stream. Since the turbulent jet creates eddies that recirculate water at the outer edges of the jet stream, by minimizing the recirculation near pipe walls, the amount of coagulant that adheres to the walls can be reduced.

Many of the experiments that were conducted revolved around the ideas of using high concentrations of coagulant to develop a floc blanket (Experiment 2) and using water pump speeds to determine the upward velocity rate and NTU (Experiments 1 & 3).

<div class="alert alert-block alert-danger">
The concept of a floc blanket makes me wonder about the geometry of the contact chamber and the flow patterns. Is there a way to briefly explain that or show it in a diagram?

Where these experiments (1, 2, and 3) done by the Spring 2017 team? I am getting confused if you are talking about current or past experiments (I would guess past because this is the previous work section, but make it clear)
</div>

The water pump speed was initially calculated using a target upflow velocity of 3 mm/s in the sedimentation tube. However, since the AguaClara High Rate Sedimentation subteam reduced the upflow velocity to 2 mm/s, the water pump was recalculated. The flow rates of the coagulant and clay inflow were assumed to be negligible.

<div class="alert alert-block alert-danger">
Check this value with HRS again if this is current.
</div>

In the first experiment, the water pump speed was set to 114 rpm to achieve an upflow velocity in the sedimentation tube of 3 mm/s. The main purpose of this experiment was to determine an appropriate coagulant dose which would yield an effluent turbidity of 2 NTU, by varying the coagulant pump speed, which subsequently changed the mass flow rate of coagulant. It was observed that the sedimentation tube did not have enough floc particles to form a floc blanket; as a result, the team hypothesized that the lack of a floc blanket was causing the high effluent turbidity readings.

<div class="alert alert-block alert-danger">
What was influent turbidity? It is sometimes easier to put a target change in turbidity instead of a target effluent. i.e. a reduction of 50 NTU has more meaning than a target effluent of 2 NTU
</div>

In the second series of experiments, the coagulant dosage was increased to be eight times more concentrated than in Experiment 1. The reason for increasing the concentration by eight-fold was that at a 4 times higher concentration, the results were essentially the same as Experiment 1. In Experiment 2, the largest observable change was that the floc blanket started to form in the sedimentation tube. After the formation of the floc blanket, the effluent turbidity was significantly reduced.

In Experiment 1, 2.5 mL of 70.9 g/L concentration PACl was added to 5 L of distilled water. However, since this coagulant dose did not have an effect on effluent turbidity even at high coagulant pump speeds, the coagulant stock concentration was increased by eight-fold. In Experiments 2 and 3, to prepare the coagulant solution, 1 liter of distilled water was added to a 1 liter-capacity bottle. It was essential to use distilled water because the coagulant particles could more effectively adhere to clay particles in a deionized environment. In order to achieve a floc blanket at such a low flow rate throughout the system, 4 mL of 70.9 g/L concentration PACl were added to the volume of water. Under the constraints set by PID control, the coagulant dose was continually adjusted throughout the experiment in o and is commonly used to characterize the mixing efficiency of a contact chamber.

<div class="alert alert-block alert-danger">
This section may be too detailed. A good rule of thumb is to try to not include too many numbers in the previous work section. Describing the coag conc as 8 times higher is good enough detail, the actual water and PACl conc are not important here. Trim it down
</div>

Other experiments were also carried out to determine the effectiveness of the contact chamber. Trials were ran, without the presence of the contact chamber, After ensuring that the influent turbidity could stabilize at 10 NTU despite initial startup complications, experiments were run to compare performance of the system with and without a contact chamber. Experiments with the contact chamber yielded higher effluent turbidity than experiments without the contact chamber. It was hypothesized that there was particle buildup in the effluent turbidimeter, so the effluent turbidimeter was emptied and refilled with distilled water. Cleaning out the turbidimeter notably decreased effluent turbidity, from approximately 4 NTU to 0.3 NTU.

<div class="alert alert-block alert-danger">
Change ran to run (or avoid passive voice altogether)

Issues with clarity and sentence structure

So the clogged turbidimeter was the issue and the results saying that the contact chamber led to higher effluent turbidity were incorrect? or no?
</div>

The Fall 2017 Team concluded that the effluent turbidity without the contact chamber was consistently lower than the effluent turbidity with the contact chamber. These results suggest that the contact chamber was not effective in improving plant efficiency. However, more tests should be run to determine why the addition of the contact chamber was not only ineffective in improving plant efficiency, but actually increased the effluent turbidity, worsening the plant efficiency.  Several recent modifications to the experiment setup and methods could have had an impact on the results. The addition of the 1 RPM pump at the waste drain controlled water flow through the tube settler, allowing most of the flow to flow up through the settler to the effluent turbidimeter, rather than allowing most of the flow to drain into the waste, as in previous experiments (Tsang et al., 2017).

## Methods
### Experimental Design

The experimental setup was similar to the other Particle Removal subteams, High G Flocculation and High Rate Sedimentation, to standardize results among the teams.

![Spring2018Schematic](https://github.com/AguaClara/contact_chamber/blob/master/Diagrams/Spring2018Schematic.jpg?raw=true)
Figure 2: The experiment setup includes a contact chamber and a coiled flocculator.

![Complete_setup](https://github.com/AguaClara/contact_chamber/blob/master/Diagrams/bench_setup.png?raw=true)


Figure 3: Image of bench setup. The flow accumulator and needle valve were added to damp pressure oscillations due to the water pump.

The experiment setup models the flow of water through a plant on a lab scale (Figure 2):

<div class="alert alert-block alert-danger">
Consider "experimental setup" rather than "experiment setup"
</div>

1. The clay stock is prepared and mixed.
2. The flow of coagulant, water, and clay are controlled by the pumps.
3. The influent turbidimeter measures the turbidity of the clay-water mixture before entering the contact chamber and flocculator.
4. Coagulant is injected immediately before the contact chamber and mixes with the clay-water mixture in the contact chamber.
5. The coiled flocculator causes further collisions between clay particles and coagulant.


The influent turbidity was controlled using a Proportional-Integral-Derivative (PID) controller on ProCoDA. ProCoDA (Process Controller and Data Acquisition) is a process control software created to automate pump control and generate datalogs ([Weber-Shirk, 2016](https://confluence.cornell.edu/display/AGUACLARA/ProCoDA)).

The PID controller uses a feedback response loop to maintain the influent turbidity. The target influent turbidity was set to 100 NTU, and the values of P (Proportional), i (Integral), and D (Derivative) were set to 0.5, 0.25, and 0, respectively. The values were selected using trial and error to optimize the response time of the PID controller.

![DiagramSchematic](https://github.com/AguaClara/contact_chamber/blob/master/Diagrams/Diagram%20Schematic.jpg?raw=true)

Figure 4: Schematic of experimental setup. The PID controller adjusts the clay pump speed to maintain an influent turbidity of 100 NTU. The water pump and coagulant pump were kept constant at 76 rpm and 20 rpm, respectively. The water pump speed was calculated to achieve an upflow velocity in the sedimentation tube of 2 mm/s (calculations shown in Python code, listed under Manual). The coagulant pump speed was adjusted experimentally to achieve an effluent turbidity of 2 NTU.

A flow accumulator was added to reduce fluctuations in flow due to the water pump. The flow accumulator consists of a bottle with two holes. Water exits on one side of the bottle and exits at the other side. At the start of an experiment, the flow accumulator bottle is filled with water to reach a water level above the two holes. The bottle is then sealed with a cap to allow the bottle to pressurize with air, thus maintaining the water level at a steady state. Water flows from the water pump to the inflow of the flow accumulator. Water flows out of the floc accumulator to the clay input.

A needle valve was added after the flow accumulator to constrict flow and further reduce fluctuations in flow. The needle valve allows the degree of constriction to be controlled by turning the knob, where "10" is closed and "0" is open. The needle valve was set to "6," which was determined experimentally to be the optimal setting for reducing the oscillation amplitude. The purpose of the needle valve and flow accumulator is to dampen oscillations in pressure due to the peristaltic pump.


### Materials

1. Pumps
    - Easy-load Masterflex 1 RPM Pump (Floc Weir Discharge)
    - (2) Masterflex 1.6-600 RPM Pumps
      - Coagulant Pump
      - Clay Pump
    - (1) Masterflex 10-600 RPM Pump (Water Pump)
2. Turbidimeters
    - (2) HF Scientific Inc MicroTOL Turbidimeters 0-1000 NTU
      - Influent turbidimeter: measures influent stream after introduction of clay into raw water stream before entering contact chamber
      - Effluent turbidimeter: measures effluent stream after flow through sedimentation tube
3. Contact chamber
    - Clear polycarbonate pipe
      - 10 in (25.4 cm) length, 1 in (2.54 in) diameter
    - PVC pipe end caps
4. Tubing and Fittings
    - Hard Tubing
    - Microbore Tubing
    - Yellow-blue size soft tubing
    - Size 16 soft tubing
5. Stock solution containers
    - 5 L tank for clay stock
    - 5 L tank for coagulant stock
5. Materials for stock solutions
    - Raw water line
    - Distilled water (used for coagulant stock)
    - Kaolinite clay
    - Polyaluminum chloride (PACl) coagulant (70.9 g/L)

### Experimental Apparatus
The contact chamber was constructed with a length that is 10 times the diameter to model the dimensions of the turbulent jet stream ([Tsang et al. 2017](https://github.com/AguaClara/contact_chamber/blob/master/contact-chamber-fall.pdf)). The turbulent jet creates eddies that recirculate near the pipe walls. By minimizing contact with the walls of the contact chamber, the amount of coagulant that adheres to the walls instead of the clay particles can be minimized.

![Contact_chamber](https://github.com/AguaClara/contact_chamber/blob/master/Diagrams/contact_chamber.png?raw=true)

Figure 5: The redesigned contact chamber, with a length that is ten times the diameter, to model the dimensions of the turbulent jet.

### Procedure
To maintain an upflow velocity in the sedimentation tube of 2 mm/s, the water pump was kept constant at 76 rpm, while the flow rate contributions of the clay and coagulant were assumed to be negligible, due to the low flow rate through the microbore tubing. PID control was used to vary the speed of the clay pump to reach the target influent turbidity of 100 NTU. The clay stock solution was diluted, so that the clay pump speed could be reduced to minimize the flow rate contribution of the clay pump. The concentration of the clay stock was 2 g/L. The coagulant dose was set by manual input to 20 RPM. The concentration of coagulant stock was 0.1418 g/L (see Python code in Manual).

Before running an experiment, all valves were opened (raw water, floc weir outlet, and the waste stream outlet). The PID set point was adjusted from the OFF state to ON state, initiating the clay pump to feed the clay stock solution into the system. The water pump and coagulant pump were switched on and set to pre-determined pump speeds. The influent turbidity was allowed to reach its target turbidity of 100 NTU, and changes in the headloss were observed.

<div class="alert alert-block alert-danger">
Potentially add that the turbidity at the effluent was recorded.

How long were experiments run for?
</div>

## Results and Analysis
###Red Dye Test
Prior to running experiments, a red dye test was conducted to observe the fluid dynamics of the coagulant dose in the contact chamber. Red dye was added to the coagulant stock, which tracked the motion of coagulant in the contact chamber.

The red dye test indicated a long residence time and a lot of recirculation within the contact chamber, which may have caused a significant portion of the coagulant to adhere to the walls of the contact chamber, rather than interact with the clay particles in the water. It is hypothesized that the slow flow rate of the coagulant injection into the contact chamber did not allow the coagulant to mix well, which may have contributed to the poor performance of the contact chamber in previous experiments.

<div class="alert alert-block alert-danger">
How much recirculation was expected and how did you quantify that?

What is recirculation?

Did you observe coagulant sticking to the walls?

Why would the slow flow rate of the coagulant injection affect the mixing?

Were these addressed? - NM
</div>

###Experimental Trials
To reduce the high recirculation in the contact chamber, the team decided to change the orientation of the contact chamber. The contact chamber was previously oriented in the upflow direction, with the coagulant injection and clay mixture flowing into the contact chamber from the bottom. The contact chamber was inverted, and a red dye test was conducted with the coagulant and clay mixture entering the contact chamber from the top.

![5hoursexperiment](https://github.com/AguaClara/contact_chamber/blob/master/Diagrams/Experiment%20Result%20after%205%20hours.png?raw=true)
Figure 6: The influent and effluent turbidimeter after an experiment runtime of 5 hours.

<div class="alert alert-block alert-danger">
Is this a continuation of the red dye test or a new test?

Was this addressed? Still unclear. Were these the results before or after the inversion?
</div>

The experiment was run for 5 hours to observe the formation of the floc blanket in the sedimentation tube. The results differed significantly from the results of previous experiments run in Fall 2017. All parameters were held consistent to the parameters used in the Fall 2017 experiments, except for the longer experiment runtime. It was observed that the effluent turbidity did not decrease sufficiently. Some possible sources of errors were identified, and possible solutions were attempted. The first noticeable issue was the growth of algae on the sides of the sedimentation tube throughout multiple experiments, which may have had an impact on the effluent turbidity. To solve this problem, the sedimentation tube was cleaned with pipe brushes and bleach. Another possible source of error is the lack of a floc blanket in the sedimentation tube. In the Fall 2017 experiments, the sedimentation tube was not cleaned out in between experiments, which allowed a floc blanket to form after repeated trials. In order to standardize results, the sedimentation tube was drained in between each experiment. However, since the influent turbidity very low, at 10 NTU, it was time-consuming to form a new floc blanket for each experiment. Although increasing the turbidity would speed up the floc blanket formation, the team's main goal was to test the process with low turbidity, which represents normal operating conditions in the AguaClara plants. Therefore, the experiment was redesigned.

The scope of the investigation was shifted from lowering the effluent turbidity with low initial turbidity to lowering the headloss occurs across the flocculator. This was because the main purpose of the contact chamber use is to reduce the coagulant particles sticking on to the walls of the flocculator so that it would require cleaning process very often, which is not preferred. After the decision was made, the experimental apparatus was changed from before. The sedimentation tube settler, 1 RPM Waste pump and effluent turbidimeter were discarded and pressure sensor, flow accumulator and needle valve were added to the apparatus. Headloss across the flocculator was used as a measure to quantify the efficiency of the contact chamber instead. Experiments with and without the contact chamber were conducted to identify the difference in headloss before and after the coiled flocculator. The relationship between pressure and experiment time was graphed to determine the slope, which was used to quantify how much headloss increased. Further investigation is required in how long of the experiment would be sufficient to determine the rate of increase. It was hypothesized that the experiments with the contact chamber would have a smaller slope than the experiments without the contact chamber, indicating the the contact chamber decreased the rate of headloss of increase.

<div class="alert alert-block alert-danger">
Revise for technical writing.

Great content/logic in the first half

Make sure you refer to each diagram/figure included so that we get explanation on every figure in the text. They should not stand alone.
</div>

![4-15-2018](https://github.com/AguaClara/contact_chamber/blob/master/Data%20Analysis/Graphs/4-15-2018.png?raw=true)
Figure 7: Headloss across the flocculator in centimeters of water in experimental setup without the contact chamber. The positive slope indicates that the headloss increased over time. The first trial of the experiment was run for approximately 8.4 hours.

![4-16-2018](https://github.com/AguaClara/contact_chamber/blob/master/Data%20Analysis/Graphs/4-16-2018.png?raw=true)
Figure 8: Headloss across the flocculator in centimeters of water in experimental setup without the contact chamber. The positive slope indicates that the headloss increased over time. The second trial of the experiment was run for approximately 8.4 hours.

The two trials run without the contact chamber showed slopes that differed by a factor of approximately 2. The increase in headloss over time was linear, allowing for a slope to be calculated for each trial. By comparing the slopes with the experiments run with the contact chamber, the rate of increase in headloss can be compared.

<div class="alert alert-block alert-danger">
This is very vague. how many experiments did you run of each set-up. Did you average the results?
</div>

There was a slight discrepancy between the two experiments without the contact chamber in pressure difference and slope. The starting pressure difference for the first trial was 30.245 cm, and the starting pressure difference was 26.627 cm for the second trial. The headloss also increased at a faster rate in the first trial, with a slope of 11.263, compared to the second trial, with a slope of 6.682. The cause of the discrepancy could not be determined because both trials were run under the same conditions; the pump speeds were the same and influent turbidity was also the same. The team subsequently decided to run two trials with the contact chamber to determine the range of headloss values that would constitute a significant difference between the control and variable experiments.

![4-19-2018](https://github.com/AguaClara/contact_chamber/blob/master/Data%20Analysis/Graphs/4-19-2018.png?raw=true)
Figure 9: Headloss across the flocculator in centimeters of water in experimental setup with the contact chamber. The positive slope indicates that the headloss increased over time. The first trial of the experiment was run for approximately 19 hours.

![4-21-2018](https://github.com/AguaClara/contact_chamber/blob/master/Data%20Analysis/Graphs/4-21-2018.png?raw=true)
Figure 10: Headloss across the flocculator in centimeters of water in experimental setup with the contact chamber. The positive slope indicates that the headloss increased over time. The second trial of the experiment was run for approximately 19 hours.

The two experiments with the contact chamber had a relatively smaller slope, at 1.73 and 4.14, compared to the slope without the contact chamber, 11.263 and 6.68. This suggests that the rate of increase in headloss was lower with the contact chamber than without the contact chamber. Further experiments will be conducted to verify these results.

![5-1-18-Contact-Chamber](https://github.com/AguaClara/contact_chamber/blob/master/Data%20Analysis/Graphs/5-1-18-Headloss-Contact-Chamber.png?raw=true)

Figure 11: Headloss across the flocculator in centimeters of water in experimental setup with the contact chamber.

![5-2-18-Contact-Chamber](https://github.com/AguaClara/contact_chamber/blob/master/Data%20Analysis/Graphs/5-2-18-Headloss-Contact-Chamber.png?raw=true)

Figure 12: Headloss across the flocculator in centimeters of water in experimental setup with the contact chamber.

In the experiments with the contact chamber, the slope was 0.0003 and 0.0002 (Figures 11 and 12, respectively). The headloss increased 2 to 3 cm from the start of the experiment time to the end.

![5-9-18-Contact-Chamber](https://github.com/AguaClara/contact_chamber/blob/master/Data%20Analysis/Graphs/5-9-18-Headloss-Control.png?raw=true)

Figure 13: Headloss across the flocculator in centimeters of water in experimental setup without the contact chamber.


![5-12-18-Contact-Chamber](https://github.com/AguaClara/contact_chamber/blob/master/Data%20Analysis/Graphs/5-12-18-Headloss-Control.png?raw=true)

Figure 14: Headloss across the flocculator in centimeters of water in experimental setup without the contact chamber.

In the control experiments without the contact chamber, the slope was 0.0006 and 0.0004 (Figures 13 and 14, respectively). The headloss increased 4 to 12 cm from the start of the experiment time to the end. 


<div class="alert alert-block alert-danger">
Reconnect these results with whether the contact chamber is helping coagulant stop sticking to the walls of the flocculator.
</div>


## Conclusions
In order to determine the efficiency of the contact chamber, experiments were conducted to measure the change in headloss across the coiled flocculator with and without contact chamber. This was a change from the previous semester, which used comparisons in effluent turbidity to quantify the contact chamber's performance. From the series of experiments conducted, there was a relatively higher slope observed in the experiments without the contact chamber. This indicates that the contact chamber effectively reduces the rate of coagulant building up on the walls of the flocculator. Thus, the results of these experiments support the use of a contact chamber in the AguaClara plants, as it may help reduce the amount of coagulant wasted. Although there needs to be further investigation into how much more effective the contact chamber is, we tentatively conclude that the contact chamber achieves its goal of reducing the amount of coagulant that adheres to the walls of the flocculator.

## Future Work
The contact chamber theoretically increases the probability of collisions between the clay particles and coagulant before the mixture enters the flocculation system. As a result, it is predicted that the contact chamber will allow the clay particles more time to interact with the coagulant, which will decrease the amount of free coagulant that adheres to the walls of the flocculator, and therefore decrease headloss across the flocculator. Since this was observed in the series of experiments, the team will further investigate the difference in the efficiency between different dimensions of contact chamber. There will be comparison between the current team's contact chamber and the Spring 2017 Team's contact chamber. Also, the team will work on verifying results in the experiments conducted by running more trials.

<div class="alert alert-block alert-danger">
This section almost reads like the abstract. Be specific here with future goals like what experiments should be done or what theories looked into next. I would really rewrite most of this.

Remove the word "theoretically" in the first sentence.
</div>

## Bibliography
Akpan, Teuffer, and Zhang (2017). Rapid Mix Contact Chamber, Spring 2017.

Balik, Y., & Aydin, S. (2015). Coagulation/flocculation optimization and sludge production for pre-treatment of paint industry wastewater. Desalination and Water Treatment, 57(27).

Bello, Oladipupo & Hamam, Yskandar & Djouani, Karim. (2014). Coagulation process control in water treatment plants using multiple model predictive control. AEJ - Alexandria Engineering Journal. Vol. 53. Pages 939–948. 10.1016/j.aej.2014.08.002.

Bratby J. (2006) Coagulation and Flocculation in Water and wastewater Treatment. IWA Publishing, London, Seattle.

EPA (2018, January). Conventional Treatment.

Frederick L. Hart, Journal (Water Pollution Control Federation), Improved Hydraulic Performance of Chlorine Contact Chambers) Dec 1979.

Jiang, J., “The role of coagulation in water treatment” (2015, February 19).

Tsang, C., Yun, Y., Gassaway, B. Contact Chamber, Fall 2017.

# Manual
<!-- The goal of this section is to provide all of the guidance that would be necessary for a future team to pick up your work where you left off. Please try to be thorough and put yourselves in the shoes of a newcomer to the project. Below are some recommended sections, but the manual will likely take a slightly different form for each team. -->

<div class="alert alert-block alert-danger">
Delete the section descriptions before the final submission.
</div>

## Fabrication Details
<!-- Include any information related to the fabrication of equipment, experimental apparatuses, or technologies. Include the purpose of each step and the fabrication methods used. Reference appropriate safety precautions. -->
The contact chamber was fabricated using a 25.4 cm (10 in) clear polycarbonate pipe. PVC caps were attached on the ends of the pipe using PVC cement to waterproof the contact chamber. Threaded push-to-connect connections were attached to each end of the contact chamber to allow tubing to be attached (Figure 5).


<!-- ## Special Components -->
<!-- If your subteam uses a particular part that is unique and you could foresee a future subteam needing to order it or learn more about it, please include basic information like the vendor where it was purchased, catalog/item number, and a link to any documentation. -->

## Experimental Methods
### Set-up

1. Open valves to raw water and waste streams.
2. Power on all three pumps: Coagulant, Clay, and Water.
3. Run clay solution mixer.
4. Set raw water and clay pump speeds manually.

### Experiment
1. Begin ProCoDA program.
2. Run until a steady-state floc blanket is achieved.
3. Track changes in headloss.

### Cleaning Procedure
1. Run Water through the system until the floc blanket escapes the system.
2. Turn off clay pump using ProCoDA.
3. Turn off all three pumps: Coagulant, Clay, and Water.
4. Close valves to raw water and waste streams.

<!-- ## Experimental Checklist -->
<!-- Another potential section could include a list of things that you need to check before running an experiment. -->

## ProCoDA Method File

### States
* OFF
  - Default state for the experimental apparatus while not recording experimental results. Controls the PID controlled clay pump for the plant.
* PID Control
  - State that powers the clay peristaltic pump into the plant. This flow rate is adjusted autonomously by the PID program responding to the variations in the influent turbidimeter. The raw water, coagulant stock, and waste pumps are all adjusted by manually based on previous calculations.

### Set Points
<!-- Here, you should list the set points used in your method file and explain their use as well as how each was calculated. -->
| Set Point                | Operation Type | Value |
|:------------------------ |:--------------:|:-----:|
| OFF                      |       1        |   0   |
| ON                       |       1        |   1   |
| Turb Target inf          |    Constant    |  10   |
| P                        |    Constant    | 500m  |
| i                        |    Constant    | 250m  |
| D                        |    Constant    |   0   |
| Influent Turbidimeter ID |    Constant    |   2   |
| Influent Turbidity       |    Variable    |  10   |
| Effluent Turbidimeter ID |    Constant    |   1   |
| Effluent Turbidity       |    Variable    |   2   |
| Pump Control (Clay)      |    Variable    |  N/A  |


## Python Code
<!-- $g$: gravity
$\sigma$: dispersion
$a$: amplitude
$h$: water depth
$H$: distance from wave crest to trough (2$a$)
$T$: wave period
$\lambda$: wavelength
$k$: wavenumber
$c_p$: celerity (wave phase speed)
$P$: pressure
$F$: force
$u$, $w$: x-velocity, z-velocity components -->

###Coagulant and Clay Stock Concentration Calculations
Calculates the concentration of clay and coagulant in the plant
given the stock concentrations.

####Coagulant Stock Concentration
```python
from aide_design.play import*

coag_stock = 70.9 * u.grams / u.liters
coag_vol = (10 * u.milliliter).to(u.liter)
water_vol = 5 * u.liter

c_coag = (coag_stock * coag_vol)/(water_vol)

q_coag = 5 * u.milliliter/u.min #Flow rate of coagulant from stock solution
q_plant = 180 * u.milliliter/u.min  #Flow rate in sed tank
q_plant.to(u.milliliter/u.sec)

c_plant = (q_coag * c_coag/q_plant).to(u.mg/u.liter)
#we should try to make this 1.5 mg/L
```
####Calculate coagulant stock concentrations
```python
c_plant = 1.5 * u.milligram/u.liter
q_plant = 180 * u.milliliter/u.min
q_coag = 5 * u.milliliter/u.min
c_coag = (c_plant*q_plant)/q_coag
water_vol = 5 * u.liter
coag_stock = 70.9 * u.grams / u.liters

coag_vol = (c_coag*water_vol)/coag_stock
(coag_vol).to(u.milliliter)

```
####Clay stock concentration
```python
from aide_design.play import*

clay_mass = 3 * u.grams
water_vol2 = 5 * u.liter

c_clay = clay_mass/water_vol2
q_clay = 4
q_plant2 = 5

c_plant = q_clay * c_clay/q_plant2

c_plant
```
###Calculation of Residence Time
```python
from aide_design.play import*
upflowv= 2 * u.millimeter / u.s
diameter= 1 * u.inch
Area= pc.area_circle(diameter)
flowrate= (upflowv * Area).to(u.mL/u.s)
flowrate
DiameterCC=diameter
LengthCC= 10 * u.inch
VolumeCC= pc.area_circle(DiameterCC)*LengthCC
residencet=(VolumeCC/flowrate).to(u.s)
residencet
```
###Required RPM for Water Pump to Achieve Required Volumetric Flow
```python
WaterPump_rpm = ((SedTube_Flow/0.8)*(60*(u.s))).magnitude
print('The required RPMs for the water pump to achive a flow rate of 1.52 mL/s is ' +ut.sig(WaterPump_rpm,4)+' RPM.')
#The required RPMs for the water pump to achive a flow rate of 1.52 mL/s is 76.01 RPM.
```

```python
To convert the document from markdown to pdf
pandoc ContactChamber_Spring2018.md -o contact_chamber_Research_Report.pdf
```
