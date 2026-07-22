# 8hp 12dB/Oct Voltage Controlled state-variable Filter

![](https://github.com/Fihdi/SVF12/blob/main/SVF12-Front.png?raw=true)

A dual pole VCF with 2 Audio (**IN**) and CV Inputs (**V/O** and **CV** jack and potentiometer), Ping input (**PING**), Variable Resonance (**RES**) and Oscillator mode with volt per octave tracking. The filter produces Lowpass (**LP**), Bandpass (**BP**), Bandstop (**BS**) and Highpass (**HP**) versions of the input signal. The module can be switched from Filter mode (Switch in the **FILT** position) to Oscillator mode (Switch in the **OSC** position). In Oscillator mode the module will produce clean sine waves on the **BP**, **BS** and **LP** outputs.

By sending a rising-edge signal like a Gate or a short Pulse to the **PING** input, the filter core gets excited and creates a damped oscillation. The length of this oscillation is controlled by the resonance (**RES**) setting.

A trimmer on the back of the module can be found to tune the Volt/Octave tracking. 

A standard 10-pin Eurorack power connector is used (Red Stripe indicates -12V (negative twelve volts)). The module is internally running on +/-9V to stabilise the volt per octave tracking.
