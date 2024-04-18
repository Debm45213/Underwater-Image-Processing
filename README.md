# Underwater-Image-Processing
Underwater imagery serves as a crucial medium for understanding marine life, including undiscovered species, shipwrecks, and hydrothermal vent processes. 
However, these images often suffer from numerous disturbances and distortions. 
Addressing these challenges, this study initiates with adaptive color correction utilizing channel similarity values to rectify the deficient red channel. 
Given the propensity of red light to scatter more significantly than blue or green light due to its larger wavelength, underwater images frequently lack red components. 
By applying adaptive color correction, we restore the red channel while preserving the blue and green channels. 
Subsequently, we enhance image details through stationary wavelet transform (SWT), employing the simplest "haar" wavelet to decompose the image into LL, LH, HL, and HH components via first-level decomposition. 
Employing high boost filtering on the LL component yields a sharpened version of the image after inversing stationary wavelet transform. 
Furthermore, we implement contrast enhancement techniques such as histogram equalization (HE), contrast-limited adaptive histogram equalization (CLAHE), and dynamic range separate histogram equalization (DRSHE).
They we compared the results obtained by us with the existing state-of-the-art method minimal color loss and locally adaptive contrast enhancement(MLLE) and got satisfactory outcomes.
