'Uncertainpy A python toolbox for uncertainty quantification and sensitivity analysis tailored towards computational neuroscience'. https://open-neuroscience.com/post/uncertainpy_a_python_toolbox_for_uncertainty_quantification_and_se #Software#ComputationalNeuroscience ...
nsitivity_analysis_tailored_towards_computational_neuroscience/
Uncertainpy is a python toolbox for uncertainty quantification and sensitivity analysis tailored towards computational neuroscience.Uncertainpy is model independent and treats the model as a black box where...
 the model can be left unchanged. Uncertainpy implements both quasi-Monte Carlo methods and polynomial chaos expansions using either point collocation or the pseudo-spectral method. Both of the polynomial chaos expansion methods have support for the rosenblatt transform...
ation to handle dependent input parameters.Uncertainpy is feature based, i.e., if applicable, it recognizes and calculates the uncertainty in features of the model, as well as the model itself. Examples of features in neuroscience can be spike timing and the action pote...
ntial shape.Uncertainpy is tailored towards neuroscience models, and comes with several common neuroscience models and features built in, but new models and features can easily be implemented. It should be noted that while Uncertainpy is tailored towards neuroscience, t...
he implemented methods are general, and Uncertainpy can be used for many other types of models and features within other fields....