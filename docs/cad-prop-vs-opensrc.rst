Proprietary vs Open Source 
==========================

DRC rules
---------

2025 Chipathon version

LPW.1_LV not implemented correctly on the proprietary software

*Proprietary software*

CO.5b - Pplus overlap of contact on COMP < 0.1 (Only for contacts to
butted Nplus and Pplus COMP areas)

*Opensource option* file = contact.drc

*# Rule CO.5b: Pplus overlap of contact on COMP
## (Only for contacts to butted Nplus and Pplus COMP areas). is 0.1µm*

*Proprietary software*

| V1.4_V1.4_ii
| V1.4 Metal2 overlap via1 = 0.01 & via1 missing metal2
| V1.4_ii If metal2 overlap via1 by < 0.04 on one side, adjacent metal2
  edges overlap = 0.06

*Opensource software* file = via1.drc

*# Rule V1.4a: metal2 overlap of via1*\ No rule for \_ii

*Proprietary software*

MT.2b - Top metal space to wide top metal (length & width > 10um) = 0.6

*Opensource option* file = metaltop.drc

*# Rule MT.2b: Space to wide Metal2 (length & width > 10um) is 0.5µm*
