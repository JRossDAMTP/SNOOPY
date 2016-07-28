# SNOOPY

Modifications

time varying thermal diffusion
- given by nu_th*(1+atan(sin(t/param.th_period)/0.1))
- timestep takes into account this timevartion
- to use uncomment #define PULSE_KAPPA in gvars.h
- thermic_period set in snoopy.cfg
