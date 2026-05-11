1. The notebook shows the development of the final model ARGUS which is capable of classifying a video under 14 categories [13 violence, 1 normal/non-violence]:

    ['Abuse', 'Arrest', 'Arson', 'Assault', 'Burglary', 'Explosion', 'Fight', 'Normal', 'RoadAccidents', 'Robbery', 'Shooting', 'Shoplifting', 'Stealing', 'Vandalism']

   using CNNs, BiLSTMs and Attention Mechanisms.
   While experimenting with a lot of possible approaches to this objective, such as: Direct Approach (Phase Learning), LAHA Versions and CBAM-Induced Approach,
   it is highly observed for CBAM-Induced Approach lead us with the best results.
   
Therefore, the final model includes, *"CNNs + CBAM (spatial attention + channel attention) + BiLSTMs + Temporal Attention"* 
in its architecture for fulfilling the detection purpose.

-------------------------------------------------------------------

2. A video file is also uploaded to showcase the modularity and integration scalability of the final detection model across various devices,
such as drones and web-apps. However, it can be viewed by clicking on "View Raw" option.

-------------------------------------------------------------------





