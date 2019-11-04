# Integration of Small Renewable Sources into the Bulk Power System using Integer Programming
This repository provides the instances of investment costs used to compute the total cost of the planning the integration of small renewable sources into the bulk power system.


[1] Transmission Line Cost (cl_{ij,y,c}): composed by the sum between the cost of conductor (cd_{c}) and structure (Cst_{y}), suche as tower, insulators, ground, etc., for each voltage magnitude level.

Table 1: Conductor Cost (cd_{c}, \forall c \in \eta)
	
|  ID   |  Cost [MUS$/km]  |
-----------------------------
|  C1   |       0.120      |
|  C2   |       0.189      |
	
	
	Table 2: Transmission Structure Cost (Cst_{y}, \forall y \in \Upsilon)
	
	    |	 Voltage    |    Cost    |
    	    |	Mag. [kV]   |  [MUS$/km] | 
            ------------------------------
	    |	   13.8	    |    0.02    |
	    |	    69	    |    0.109   |
	    |	   138	    |    0.215   |
	    |	   230	    |    0.303   |

	cl_{ij,y,c} = (cd_{c} + Cst_{y})*dl_{ij}	#where dl_{ij} is the length in km of a branch ij.



[2] Collector Substation Cost: 
