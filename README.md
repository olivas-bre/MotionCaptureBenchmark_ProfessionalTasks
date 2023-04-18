# MotionCaptureBenchmark_ProfessionalTasks
This benchmark provides motion capture (MoCap) files in .bvh form. The recordings were done in the span of May 2019 to January 2020 for the needs of the CoLLaboratE and MINGEI H2020 projects funded by the European Commission. The tasks included are:

- TV assembling
- Airplane component manufacturing
- High ergonomic hazard motions 
- Silk-Weaving
- Glassblowing
- Mastic Cultivation

The TV assembly and airplane component manufacturing tasks were recorded in real-world conditions inside the factory during the actual production of the items. The high ergonomic hazard motions were recorded in a controlled lab environment and serve as baseline/prototype motions for ergonomic risk assessment.

The silk-weaving, glassblowing, and mastic cultivation data sets were created, corresponding to movements performed by skilled craftsmen and mastic farmers. These data sets were produced in order to extract the expert's gestural knowledge and analyze their dexterity while doing their crafts.

## Naming Convention:

All files in this benchmark follow a strict naming convention to allow for easier parsing by scripts. The names have a total of 12 or 13 characters that convey the following information:

- The first three or fours characters label the recording session (e.g., LAB, PLN, GBBC, MCSN, etc.)
- The next three characters label the subject number (e.g., S01, S02, S03, etc.)
- The next three characters label the posture or gesture number (e.g., P01, P02, G01, G02, etc.)
- The final three characters label the repetition number (e.g., R01, R02, R03, etc.)

For example, LABS02P03R01 denotes a lab recording of the second subject, performing the third posture for the first time.

## Recording Sessions:

There are six recording sessions in this benchmark, the ergonomic risk motion recorded in the lab (denoted as "LAB"), the construction of an airplane component (denoted as "PLN"), and the assembling and packaging of TVs (denoted as "TV*"), the silk weaving (denoted as "SW*"), glassblowing (denoted as "GB*"), and mastic cultivation (denoted as "MC*").

The postures are the following:

### LAB:

#### Standing:
- P01: The subject stays in I-pose
- P02: The subject rotates his/her torso to the left as far the person can
- P03: The subject will laterally bend his/her torso to the left for 6 seconds
- P04: The subject bends more than 20° but less than 60°
- P05: The subject bends more than 20° but less than 60° while rotating and laterally bending the torso to the left
- P06: The subject stretches his/her arms, and bends forward more than 20° but less than 60° while rotating and laterally bending the torso to the left
- P07: The subject bends more than 60°
- P08: The subject bends more than 60° while rotating and laterally bending the torso to the left
- P09: The subject stretches his/her arms, and bends forward more than 60° while rotating and laterally bending the torso to the left
- P10: The subject upright, raises the elbows above the shoulder level with the forearms bent 90° (
- P11: The subject raises the elbows above the shoulder level with the forearms bent 90° while rotating and laterally bending the torso to the left
- P12: The subject raises the elbows above the shoulder level with the arms stretched while rotating and laterally bending the torso to the left
- P13: The subject upright, raises the hands above the head
- P14: The subject raises the hands above the head with the arms stretched while rotating and laterally bending the torso to the left
####  Sitting on a chair:
- P15: The subject sits upright
- P16: The subject bends forward more than 60°
- P17: The subject bends forward more than 60° while rotating and laterally bending the torso to the left
- P18: The subject stretches the arms, and bends forward more than 60° while rotating and laterally bending the torso to the left
- P19: The subject raises the hands above the head with arms stretched
- P20: The subject raises the hands above the head with the arms stretched while rotating and laterally bending the torso to the left
#### Kneeling:
- P21: The subject stays upright
- P22: The subject rotates the torso to the left as far he/she can
- P23: The subject will laterally bend the torso to the left for 6 seconds
- P24: The subject bends more than 60°
- P25: The subject bends more than 60° while rotating and laterally bending the torso to the left
- P26: The subject stretches the arms, and bends forward more than 60° while rotating and laterally bending the torso to the left
- P27: The subject upright, raises the elbows to the shoulder level with the arms stretched
- P28: The subject raises the elbows to the shoulder level with the arms stretched while rotating and laterally bending the torso to the left

The TV assembling tasks are further divided. The subtasks are: packing the TVs on a stack for shipping (denoted as "TVP" for medium-sized TVs and "TVL" for larger TVs), placing assembling and placing electronic circuit boards on the chassis (denoted as "TVB"), and screwing the boards on the TV chassis (denoted as "TV_"). Each task is comprised of a number of postures.  

### TV Assembling:

#### Assembling the board and placing it on the TV chassis (TVB):
- P01: Reaching high, above the shoulder level, to pick one component
- P02: Reaching low, below the knee level, to pick up the second component
- P03: Connecting the components and placing the board on the chassis to be screwed
#### Screwing an electrical circuit board on the TV chassis (TV_) :
- P01: A screw is placed on a power tool and it is being screwed on the chassis. The process is repeated four times
#### Preparing TVs for Shipping (TVP & TVL):
- P01: Placing TVs on a wooden pallet (bottom level)
- P02: Preparing to wrap the bottom level with a membrane
- P03: Wrapping the bottom level
- P04: Placing TVs on top of the bottom level (second level)
- P05: Placing TVs on top of the second level (third level)
- P06: Wrapping the second level with a plastic membrane
- P07: Wrapping the third level with a plastic membrane
- P08: Placing TVs on top of the third level (fourth level)
- P09: Wrapping the fourth level with a plastic membrane

#### Riveting of an airplane floater (PLN):
- P01: Rivet with the pneumatic hammer.
- P02: Prepare the pneumatic hammer and grab rivets. 
- P03: Place the bucking bar to counteract the incoming rivet.

The tasks recorded for silk weaving, glassblowing, and mastic cultivation data sets were segmented by gestures (e.g., G01, G02, etc.) . The tasks recorded for these three data sets are the following:

### Silk weaving (SW*):
- The creation of the punch cards (SWPC).
- Preparation of the beam (SWPB).
- Wrapping of the beam (SWWB).
- Jacquard weaving with small loom (SWSL).
- Jacquard weaving with medium size loom (SWML).
- Jacquard weaving with large loom (SWLL).

### Glassblowing (GB*):
- Beak cutting (GBBC).
- Blowing and shaping (GBBS).
- Cervix refining (GBCR).
- Cord laying (GBCL).
- Finish details (GBFD).
- Handle laying (GBHL).
- Transfer to punty (GBTP).
- Leg and foot laying (GBLF).

### Mastic Cultivation (MC*):
- Scrapping with new tool (MCSN).
- Scrapping with old tool (MCSO).
- Sweeping (MCSW).
- Dusting (MCDU).
- Embroidery A (MCEA).
- Embroidery B (MCEB).
- Embroidery with an axe (MCEX).
- Gathering (MCGA).
- Harvesting (MCHA).
- Wiping (MCWI).
- Shifting A (MCSA).
- Shifting B (MCSB).
- Cleaning with the wind (MCCW).

The motion capture files were processed and segmented with a 3D character animation software (MotionBuilder, Autodesk Inc., San Rafael, CA. USA) and exported to Biovision Hierarchy (BVH) files.
