Moving the iceberg basal melting from the surface layer (evaporation-precipitation [kg/m2/s]) to the layer that matches the keel depth. 
The impact of basal melting is represented as salinity and temperature tendencies per second. 
These tendency fields are updated by each iceberg and also exchanged. For diagnostic output, the summation DDPDD is used globally. 

Modified the lateral basal melting (excluding wave-induced erosion) such that it is not assumed to be concentrated at the surface.
The impact of lateral basal melting on temperature and salinity tendencies now has a vertical profile extending
down to the iceberg keel depth.

It is important to note that in the middle of each time step, the tendencies in the TS array are set to zero. 
We add the temperature and salinity tendencies associated with iceberg basal melt after this reset.
