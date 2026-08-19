# 8hp 12dB/Oct Voltage Controlled state-variable Filter

![](https://github.com/Fihdi/SVF12/blob/main/SVF12-Front.png?raw=true)

# Features
- Two  Inputs **IN** (DC-coupled, allows for audio and CV processing)
- Volt per octave Input **V/O**
- Ping Input **PING**
- Self-Resonance switch **FILT/OSC**
- Lowpass **LP** Bandpass **BP** Bandstop(Notch) **BS** and Highpass **HP** outputs 

# Oscillator mode
The module can be switched from Filter mode (Switch in the **FILT** position) to Oscillator mode (Switch in the **OSC** position), turning the module into a musical sine-cosine quadrature VCO. This can produce clean sine waves on the **BP**, **BS** and **LP** outputs with no input, a mode called self-oscillation. The sinusoidal signals of  **BP** and **HP** are phase-shifted 0, 90 and 180 degrees.

.Inverting the **BP** signal and sending it back into a state variable filter it starts to self-oscillate, albeit with no limiting. Switching from **FILT** to **OSC** changes the **RES** knob from a variable voltage divider to an attenuverter with diode-clipping. With a trimmer on the back of the module, the **V/O** input can be tuned to allow for volt per octave tracking

# Ping Input
By sending a rising-edge signal like a Gate or a short Pulse to the **PING** input, the filter core gets excited and creates a damped oscillation. The length of this oscillation is controlled by the resonance (**RES**) setting.

# Power
A standard 10-pin Eurorack power connector is used (Red Stripe indicates -12V (negative twelve volts)). The module is internally running on +/-9V to stabilise the volt per octave tracking.

# Sponsor
A big Thank You to [PCBWay](https://www.pcbway.com) for sponsoring the development and prototyping of this module! They have excellent build quality and I can recommend using their service to build your own projects! I used the "Black" soldermask and white silkscreen and the surface has very deep and glossy black finish.

Simply upload the Gerber and production files for the B-Board and 90% of the circuitry is done. Solder the final through-hole components and tightend the screws and you have a finished Eurorack module, ready to give your sounds a crunchy filter effect.

![](https://github.com/Fihdi/Eurorack/blob/main/PCBWay-Logo.png?raw=true)
