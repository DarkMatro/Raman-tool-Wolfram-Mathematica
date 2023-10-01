# Raman-tool
Raman tool (Wolfram Mathematica prototype) 

The program is designed for a full cycle of processing Raman spectra solving machine learning classification problem: preprocessing, decomposition of spectra, creation of Logistic regression classifier model for further work with new measured spectra.
This Wolfram Mathematica notebook allows to work in user interface.

# Installation
1. Download the 'Raman tool v.1.0.175.nb' file.
2. Open it in Wolfram Mathematica 12.2.

# Program functionality
- Classifier training and measurement classification using 'Logistic regression' model.
- The ability to use the program to classify new measured spectra using trained models.
- Import files in .txt, .asc format as a two-dimensional array with spectra.
- Saving all data in a .zip project file. All information is converted into binary format and compressed in a zip archive with the maximum compression ratio.
- Interpolation to bring spectra with different wavelength ranges to the same nm range.
- Despike (removal of high-frequency random noise (electrical noise)).
- Conversion of spectra from the nm wavelength range to wavenumbers cm-1.
- Normalization of spectra using: Standart Norman Vatiate (SNV)
- Smoothing of spectra using: Empirical Mode Decomposition (EMD).
- Baseline correction with iModPoly method.
- Original Raman spectrum decomposition algorithm.
- Automatic construction of all necessary graphs for articles and the ability to save them in various formats.

![1](https://github.com/DarkMatro/Raman-tool-Wolfram-Mathematica/assets/113565324/e8635ce6-5896-4edc-a3c3-a46a48560714)
![2](https://github.com/DarkMatro/Raman-tool-Wolfram-Mathematica/assets/113565324/37009545-84a1-43ef-a736-e27ac1d7a019)
![3](https://github.com/DarkMatro/Raman-tool-Wolfram-Mathematica/assets/113565324/3c67433c-c5e6-40fc-9e8f-c4e24dc0654c)
![4](https://github.com/DarkMatro/Raman-tool-Wolfram-Mathematica/assets/113565324/2b93c0bc-9ce6-4a8f-a604-e3853b3bb963)
