# Frequency-Division-Multiplexing---Modulation-and-Demodulation-using-Python

__Aim__:

To generate an FDM signal by multiplexing multiple baseband message signals on different carrier frequencies, transmit (sum) them, optionally add channel noise, then recover each message by bandpass filtering and coherent demodulation in Python (Google Colab). Observe time & frequency domain signals and measure recovery quality.


__Apparatus Required__:

Google Colab (or any Python environment)

Python libraries: numpy, matplotlib, scipy (scipy.signal)


__Theory__:

FDM places different message signals in separate, non-overlapping frequency bands by modulating each message onto a distinct carrier frequency. The multiplexed signal is the sum of all modulated channels. At the receiver, bandpass filters (or tuned filters) isolate each channel; then each isolated carrier is demodulated (coherently multiplied by a synchronized carrier) and low-pass filtered to recover the original baseband.

__Procedure__:

1 — Imports and parameters

2 — Create message signals and carriers

3 — Modulate each message (standard AM DSB-SC) and form FDM signal

4 — Frequency domain (spectrum) of FDM signal

5 — (Optional) Add AWGN noise to FDM signal

6 — Receiver: isolate each channel with bandpass filter

7 — Demodulate each isolated channel (coherent) and low-pass filter to recover baseband

__Output_:
![WhatsApp Image 2025-11-15 at 06 36 47_b8064b80](https://github.com/user-attachments/assets/8cb94d3c-8a6e-48e0-abdf-d555a9fa5823)

![WhatsApp Image 2025-11-15 at 06 36 55_13a7ae57](https://github.com/user-attachments/assets/a68eae6c-f4fb-4e45-994c-88062b5c1f0b)

![WhatsApp Image 2025-11-19 at 21 54 18_49ff4c17](https://github.com/user-attachments/assets/101e5450-36ed-4599-8525-15fa37a7ff12)


__Result__:

 thus frequency division multiplexing is done experimentally and output is verified

