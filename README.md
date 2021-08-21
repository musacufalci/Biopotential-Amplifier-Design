# Biopotential Amplifier Design

The value of the detected signal at 1-1.5 mv level was increased to 500 mv levels.

Features:

- Linear Amplifiers
- Voltage Supply, Single/Dual (±)	  : ±6V ~ 18V
- Current Supply			              : 3.5mA
- Operating Temperature		          : -25°C ~ 85°C
- Gain Bandwidth Product		        : 25MHz
- Pin Programmable Gains		        : 1, 100, 200, 500
- Slew Rate			                    : 5V/µs
- -3db Bandwidth			              : 1MHz
- Current - Input Bias		          : 50nA
- Voltage - Input Offset		        : 200µV

The human body produces electrical signals of the order of µV during normal operation. In order for these signals to be used in devices such as ECG, EEG, bedside monitors and defibrillators, they must first be amplified at the desired level.

Since the frequency values ​​of the bioelectric signals (ECG, EEG, EMG, EOG) go down to very low frequency regions, the biopotential amplifiers are usually DC coupled, and the upper cut-off frequencies can go up to 100 Khz, depending on the signal to be amplified. In amplifiers that use electrodes, such as EKG amplifiers, -AC- coupling is used so that the -DC- voltage generated on the electrodes does not saturate the high-gain amplifier. In this case, the lower cut-off frequency of the amplifier is increased to 0.04 Hz. The frequency characteristic of the amplifiers is limited in the upper frequency region by filters. Thus, signals that are free from the negative effects of high-frequency interference (noise) signals are obtained. The upper cutoff frequency of the biopotential amplifier is generally tried to be made up to the frequency of the largest frequency component of the signals to be amplified. In some cases, special filters (Notch-Notch filter) are also used, especially in ECG amplifiers, in order to weaken the mains frequency (50 Hz) distortion signals in the main signal...

Design by https://www.linkedin.com/in/musacufalci/
