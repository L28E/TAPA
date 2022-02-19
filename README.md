# ELEC 4700 Carrier Transport PA Assignment

## Whats new:
- `LinearGradient.m`
- `ExponentialGradient.m`
- `LinearJuntion.m`

## Questions

- Whats changed [by doping with a gradient]?
    - By changing the concentration of donors to a gradient, we induce a diffusion current particularly at the ends, which have high and low concentrations, and subsequently create an electric field and a potential at either end. 
- Turn off the disturbance (npDisturbance). What can you see?
    - Without the disturbance, the holes are less normally distributed, and diffuse towards the left hand side where the electrons are less concentrated.
- Play with the flags Coupled, TwoCarriers and RC. See if you can explain any changes.
    - When `Coupled=0` the concentrations are uncoupled. 
    - When `TwoCarriers=0` there are no holes in the simulation.
    - When `RC=0` there is no recombination.
