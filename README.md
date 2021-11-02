# Signal and Noise Data for Diverging Acoustic Waves

The dataset contains the medical ultrasound imaging measurement data. The phantom dataset was measured by using two different imaging methods.
These methods are diverging wave imaging (DWI), and conventional single-focused phased array imaging (CSFI).

We used a Digital Phased Array System (DiPhAS, Fraunhofer IBMT, Frankfurt, Germany) for data acquisition. We also used 128 elements phased array transducer (Fraunhofer IBMT, Frankfurt, Germany) operating at a 7.5 MHz center frequency. We performed phantom (Model 550, Breast & Small Parts Phantom, ATS Laboratories, Bridgeport, USA) measurements. The phantom consists of monofilament nylon line targets with a diameter of 50 micrometers and tissue-mimicking cylindrical targets of varying sizes and contrasts. The data sampling rate is 80 MHz in the reception. The receive phase length is 95 microseconds. Therefore, the length of the data at each array element is 7600 samples. We applied 22 dB fixed and 2.3 dB/cm time-varying gain for phantom measurements.

A detailed description of the measurement setup is available in arXiv:2104.10526v1. The transducer measurement data is also available in arXiv:2105.14816v1.

# Instructions:

We applied appropriate time delays to each transducer array element to obtain diverging wavefronts in DWI. We used 8-bit complementary Golay sequences (CGSs) with different bit lengths (0.5, 1, 1.5, and 2-cycle/bit) to code the transmitted signal and binary phase-shift keying for modulation in DWI.

In CSFI measurements, we transmitted a 1-cycle pulse. We used 181 steered and focused beam transmissions to construct the image scan lines. The steering angle is between -45° and 45°, with 0.5° intervals. We focused each transmission at 40 mm away from the transducer array center. All array elements were used in each transmit and receive event. 

We measured the noise in each channel without any transmission. The array was kept acoustically in contact with the phantom surface to ensure the noise contribution of the radiation resistance. We recorded 13 separate measurements, where the transducer is displaced by about 1 mm in each measurement. 

We also performed measurements in freshwater. We immersed a highly reflective material, a steel plate, in the water at a 5 cm depth (approximately). 
We fired the 64th element of the transducer and received the reflecting echoes from all elements. 

Do not hesitate to contact the author (yasin.kumru@bilkent.edu.tr) if you have any questions about the dataset.

# Access to Dataset Files

The dataset is available on “https://drive.google.com/file/d/1aRyn8uKgGRkIxohs6M7sddUSCdfe3IFZ/view?usp=sharing”.
