This is the readme for the model associated with the paper

Park C, Rubin JE (2013) Cooperation of intrinsic bursting and calcium  
oscillations underlying activity patterns of model pre-Botzinger  
complex neurons. *J Comput Neurosci* 34:345-66

This model written in XPP was implemented by Jon Rubin and Choongseok  
Park.

XPP is freely available at [http://www.math.pitt.edu/~bard/xpp/xpp.html](http://www.math.pitt.edu/~bard/xpp/xpp.html)

To run the model in its default setting start with a command like  
(depends on your platform):

xppaut OneCellTwoOsc.ode

Once XPP starts select Initalconds -> (G)o to see a figure like this:

![screenshot](./screenshot.png)

Inside XPP, use File -> Read set with the included set files to get  
certain dynamics from the paper:

OneCellTwoOsc.ode.setsb <-> the paper's Fig. 2a,  
![fig 2a](./fig2a.png)

OneCellTwoOsc.ode.setdb <-> the paper's Fig. 2b,  
![fig 2b](./fig2b.png)

OneCellTwoOsc.ode.setsdb <-> the paper's Fig. 2c  
![fig 2c](./fig2c.png)

---

2025-07-09: Converted README to Markdown.