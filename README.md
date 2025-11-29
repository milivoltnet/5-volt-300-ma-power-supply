# 5-volt-300-ma-power-supply
Electronics - 7805-positive voltage regulator

Today we are going to make a power supply with a transformer, which we disassembled from an adapter with a broken electronic circuit. We tried the transformer with 220 volts AC voltage. We measured 6 Volt AC voltage on the secondary winding side.

We built our circuit on a breadboard and ran it. Below is the video about the application on our Youtube channel.



We measured whether the transformer was intact without connecting 220 Volt AC voltage. When we measured the primary and secondary sides of the measuring leads in the OHM part of the multimeter, we saw that the resistance of the primary side was higher than the secondary resistance. This was the second indication that the transformer was intact.

The most needed voltage level in electronics workshops is 5 Volts. That's why we used the 7805 circuit element. Although the input voltage goes up to 35 Volts, the output voltage remains constant at 5 Volts.

We used a rectifier diode on the secondary side of the transformer. This type of connection we made with the 1N4001 diode is called a half-wave rectifier. The 1000 micro Farad capacitor connected after the diode brings the half sinusoidal voltage closer to the DC voltage. But it is not exactly DC voltage yet. The 7805 circuit element comes into play here and the conversion to DC signal is completed to a large extent. On the 3rd pin of the 7805 circuit element, that is, the output pin, there is a waveform closer to the DC voltage. We also used another 10 micro Farad capacitor to avoid minor fluctuations in voltages.

The 7805-positive voltage regulator can normally deliver up to 1.5 amps. But the transformer in our circuit cannot provide that high current. This power supply can provide 5 volts and 300 milliamperes of current.

Related link : https://milivolt.news/post/5-volt-300-ma-power-supply
Related video: https://youtu.be/IICbv9E8Hck?si=7z2NA3EP7muI14aq
