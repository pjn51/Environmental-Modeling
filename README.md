# Environmental-Modeling
This is a repo for my models of environmental systems (just for fun really). 

## Forestmodel.ipynb
This model shows % forest floor cover for various undergrowth species in a birchwood forest. 

Gap indicates that there is no undergrowth, and there is light streaming down through the canopy in this plot. We would expect to see this cover type after a disturbance, or due to disease or something like that. 

Bare indicates that the forest floor is bare, but saplings have colonized the area. The density of the saplings during this stage causes no light resources to be available for any undergrowth.

Oxalis indicates that the plot has been taken over by oxalis, a first-on-the-scene colonizer of the forest floor. It has fast growth rates, but a short lifespan.

Rubis indicates that a plant of the rubis family has taken over, usually replacing oxalis. These plants have longer lifespans than oxalis do.

### Modeling disturbance
This model adds a layer of complexity to the birth / death rate model of the four floor states. There is a random chance of forest fire, which will alter the composition of the forest floor significantly.

### Conclusions from the model
We can see that with just a few species, and a single disturbance event, we already start to see complex, nonlinear patterns in the development of any one species, and of overall composition. Add to this hundereds or thousands of other species, including human influence, and many more disturbances, which are each functions of many other variables, and you begin to see how complex the forest ecosystem really is. 
