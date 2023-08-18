# deep-learning-based-controller-design-

Presence of model uncertainties creates challenges for model-based control design, and complexity of the control design is further exacerbated when
coping with nonlinear systems. This code presents a sliding mode control (SMC) design approach for nonlinear systems with partially known dynamics
by blending data-driven and model-based approaches. First, an SMC is designed for the available (nominal) model of the nonlinear system.
The closed-loop state trajectory of the available model is used to build the desired trajectory for the partially known nonlinear system states. Next,
a deep policy gradient method is used to cope with unknown parts of the system dynamics and adjust the sliding mode control output to achieve a desired
state trajectory. You can find the simulation results in the "Deep learning based controller design.ipynb" file.
