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
To be determined.
