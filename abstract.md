## Automatic isobath generalisation using the *Triangle Region Graph*: uniting soundings and isobath through a navigational surface

### Authors

*Willem van Opstal, Martijn Meijers, Ravi Peters*

### Abstract

-------
+ Short introduction on navigational charts
+ why they are critical (compared to topographic maps)
+ why generalisation is important in these charts
+ the four constraints (context)  
-------    
+ properties of line- and surface based approaches
+ information bias between only accounting for lines or soundings
+ goal of integrated approach (ideal)
+ basis is the surface base approach: generalises the surface without any information on the outcome
-------  
+ linking mechanism: triangle region graph
+ geometry of trg
+ properties of trg
-------
+ generalisation approach
+ continue generalisation, up to minimum legibility requirements
+ goal is having a legible chart, safe by definition, morphology represented as good as possible
+ simple rule-based process
+ in theory could use information on both survey-level (accuracy/lineage/direction) and cartographic level (constraints)
+ generalisation mechanism is smoothing the surface, effectively smoothing lines, removing pits, enlarging peaks etc.
-------
+ proof of concept: results
+ in relation to VSBA, maintain more morphology
+ especially effective on large scale
+ need more radical generalisation operators on small scales
-------
+ the advantages of an integrated approach, best of line- and surface-based
+ now, develop better metrics suitable for the constraints and more complex operators
+ beyond smoothing the surface
+ other evaluation model: optimisation, or using more of the available structure (~hierarchical)
+ do not underestimate the cartographer's eye, especially in these critical applications

### Abstract (original thesis)

Navigational charts play a vital role in a ship's safety while navigating the seas, rivers or lakes. With most of the features and obstructions being out of sight -below sea-level - these charts are more critical than e.g. topographic maps. For routing but also positioning, depth information is a key aspect on these charts. This depth information is available in either depth contours, coloured depth areas and individual soundings. However with the data originating from accurate but usually erratic survey data, a visualisation of raw data is not sufficient for use in a navigational chart directly. It would not clearly convey the information to a human operator in one sight, and thus this visualisation is in need of generalisation: a simplified representation of the same data with irrelevant details being omitted. This thesis gives new insights in the generalisation process for isobaths only and proposes a new framework to deal with those.

We propose a framework based on a novel auxiliary data structure to link a triangulation to the resulting isobaths: the triangle region graph. It links the position of isobaths directly to individual triangles, as well as establishes relations between the isobaths themselves. With this structure we ultimately link the survey data to the final cartographic product and thus in theory we could integrate all information across the generalisation pipeline in one and the same process. We have successfully used this framework with a basic rule-based evaluation model: we isolate conflicting isobaths, triangles and vertices based on legibility requirements and target generalisation operators on those. With this approach we can successfully maintain more of the morphology while still yielding a finely legible chart.

Especially at large scale charts the results are promising: narrow channels, pits and bends remain if legibility permits. With smaller scale charts the challenge now is to generalise beyond smoothness. More radical generalisation operators are needed to omit all irrelevant details. However the overall framework using the triangle region graph as integrating mechanism has potential to do so. It is easily extensible due to its modular approach and can incorporate most depth information: from survey accuracy to size of isobaths and even golden sounding selection in the future.
