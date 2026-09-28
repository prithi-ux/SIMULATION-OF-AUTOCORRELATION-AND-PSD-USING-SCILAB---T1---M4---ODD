# SIMULATION-OF-AUTOCORRELATION-AND-PSD-USING-SCILAB---T1---M4---ODD
# SIMULATION OF AUTOCORRELATION AND PSD USING SCILAB

## AIM

Write a program for Autocorrelation and PSD of signals in SCILAB and verify Wiener-Khinchin relation.

## EQUIPMENTS NEEDED

- Computer with i3 Processor
- SCI LAB

## THEORY

The Wiener-Khinchin theorem states that the power spectral density of a wide sense stationary random process is the Fourier transform of the corresponding autocorrelation function.

### Power Spectral Density (PSD)

$$
S_{XX}(\omega)=FT[R_{XX}(\tau)]
=\int_{-\infty}^{\infty}R_{XX}(\tau)e^{-j\omega\tau}d\tau
$$

### Autocorrelation Function (ACF)

$$
R_{XX}(\tau)=IFT[S_{XX}(\omega)]
=\frac{1}{2\pi}\int_{-\infty}^{\infty}S_{XX}(\omega)e^{j\omega\tau}d\omega
$$

## ALGORITHM

### 1. Load or Define the Signal:

Input your time-domain signal.

### 2. Compute Autocorrelation:

Calculate the autocorrelation function of the signal.

### 3. Compute Power Spectral Density (PSD):

Estimate the PSD of the signal, either directly using a method like Welch’s periodogram or by using the Fourier transform of the autocorrelation.

### 4. Plot Results:

Visualize the autocorrelation function and PSD.

## PROCEDURE

- Refer Algorithms and write code for the experiment.
- Open SCILAB in System.
- Type your code in New Editor.
- Save the file.
- Execute the code.
- If any Error, correct it in code and execute again.
- Verify the generated waveform using Tabulation and Model Waveform.

## RESULT
<img width="628" height="287" alt="image" src="https://github.com/user-attachments/assets/6c1f459b-4755-41ba-a596-4555c60800c6" />
<img width="1151" height="317" alt="image" src="https://github.com/user-attachments/assets/91bd1191-a340-414e-b69c-698294163f54" />

