## Microstrip

- used in all modern devices such as mobile phones.
- low power transmission
- made of a layer of ceramic susbtrate material
    - has epsilon_r with value between 1 and 10.2
- base consists of another grounding metal layer (t)
- has no cutoff freq. since it works on TEM waves

### advantasges
- low weight
- low profile
- low cost

### FR4
susbtrate material manufactured in china with epsilon range of 4.4:4.7

### Fringing Effect
- part of the field moves in air and the other part moves in the dielectric material
- causes undesired coupling
- solution is to confine the wave in the substrate only
    - can achieve this with raising the permittivity (epsilon_r)
        - only good theoretically since results in diminsions impossible to fabricate (very small width when trying to maintain the 50Ohm resistance)
- most antennas are made of low permittivity substrates with epsilone_r ranges like: 2.2, 3.33, etc... since
    - these gives the most radiation
- when epsilon_r increases:
    - dimensions decrease
    - fringing effect will decrease

### How to model in HFSS
Dimension Format: LxWxH
t = 0.035
Substrate Dimensions: 50x50x0.7874 mm
Metal Base Dimensions: 50x50xt mm
Upper Layer: 2.4x50xt mm
Radiation Box: touches the ports and doesnt touch anything else

