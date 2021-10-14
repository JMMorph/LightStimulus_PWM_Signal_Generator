# LightStimulus_PWM_Signal_Generator
This project allows you to generate three different signals to control a light emitter with PWM
To use it you just need to set the parameters:

    t_max = 30; # duration of the signal in minutes
    periodo = 1 # period of the PWM value update in seconds, this means it will change each second
    res = 4 # bits resolution PF THE pwm

    # Duration of stimuli
    on_off = np.array([4,9,14,17,22,23])+0.25 # Use this array to indicate the on and off time for the number of stimuli you want in the same signal
