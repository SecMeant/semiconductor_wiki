# Problem statement
We experience very poor quality of the oxide grown on the silicon wafers on both dry and wet thermal oxidation.  
We observe the results in cases:

1. Grown oxide does not provide a good dopant stop. We read N-type semiconductor during the hot point probe test in places that should have not been doped, because we grew 500nm thick oxide.
1. Grown oxide does not form an insulating gate, when we apply a silver glue based contact. The bigger the contact the more probability there is to obtain a leaking gate with resistivity dropping below 200k Ohms.
1. We observe "cracks" and "islands" when looking at the grown oxide under SEM.

# Proposed solution
I suspect the poor quality of the oxide is due to contamination by particles from the air or chemical residue from the RCA clean, blocking a path to silicon to form a silicon dioxide during oxidation.  
I suspect the contamination to follow a random distribution in space.  

Therefore, I propose a statistical method, that grows the oxide in multiple stages, where each stage is loosely defined as:

1. RCA clean of the wafer.
1. Dry oxide growth
1. Wet oxide growth

The whole oxide growth process is broken down into multiple stages like that, **including the RCA clean**.
Provided that the contamination has a random spacial distribution on the wafer, by breaking the oxidation process into multiple stages, we minimize the chance for the contamination to cover the very same place twice, thus being cleaned/removed by the next RCA clean, uncovering the place where oxide has been poorly grown.
Naturally, the possibility of obtaining a critical defect on the oxide drops with each next stage, meaning more stages - less likelihood for a defect, but at a cost of longer overall process.

# Results
## Results #1
Reported on 2024.07.14
Contacts and testing on 2024.07.13
Oxide growing on 2024.07.07

The results are disappointing. It's very easy to create, even a small contact and get a leak in the oxide.  We get
resistivity comparable to those without oxide.  Tests was done on 2x clean (fresh from the supplier) P100 wafer and one
already processed and cleaned NPN wafer.  All of the samples had the very same issue. Never got more terrible results.
The growing was done in tube furnace for all the samples.

I suspect that the source of the contamination is the furnace itself. The bricks are huge source of dust or small brick
particles that are not removed by the cleaning acids.

We need sealed quartz labware that we can process the wafers when they are in the furnace.
I suspect that this will solve the issue.

We may want to add DI water rinse **after** the IPA bath too, maybe we leave some residues, which influence the oxide
growth?
Prepare samples cleaned in both ways and check them under the SEM.

### Process
Reapeat 4 times:
    3min Clean-1
    DI Water rinse
    3min Clean-2
    DI Water rinse
    Aceton bath
    Air pressure clean
    IPA bath
    Air pressure clean
    Grow dry 20min 1100C

