Overview

This Jupyter Notebook implements a model to simulate the physical properties of blazars, which are a type of active galactic nucleus (AGN) characterized by their relativistic jets pointing towards Earth. The notebook calculates key parameters such as the Lorentz factor, Doppler factor, observed intensity, power of the jet, and the mass of the black hole.


Requirements

To run this notebook, the following Python packages are required:

numpy

matplotlib


Key Parameters

The model uses several parameters to perform its calculations:

beta: Velocity as a fraction of the speed of light (v/c).

theta_deg: Angle in degrees at which the observer views the jet.

I_0: Intrinsic intensity of the jet.

B_p: Magnetic field strength.

M_solar_masses: Mass of the black hole in solar masses.

a: Spin parameter of the black hole.

R_BLR: Radius of the broad-line region.

Delta_V: Velocity dispersion.

f: Virial factor.


Calculations

The notebook performs the following calculations:

Lorentz Factor (gamma): A measure of time dilation and length contraction for objects moving at relativistic speeds.

Doppler Factor (delta): A factor that describes the change in frequency (and intensity) of light due to the relative motion of the source and observer.

Observed Intensity (I): The intensity of the jet as observed from Earth.

Power of the Jet (P_BZ): Power extracted from the black hole via the Blandford-Znajek mechanism.

Mass of the Black Hole (M_BH): Estimated mass of the black hole using the virial method.


Results

The notebook prints out the calculated values for the Lorentz factor, Doppler factor, observed intensity, power of the jet, and mass of the black hole. Additionally, it generates plots to visualize:

The relationship between the Doppler factor and the angle.

The observed intensity as a function of angle.

The power of the jet as a function of the spin parameter.

The estimated mass of the black hole.


Usage

To run the notebook, open it in a Jupyter environment, execute the cells sequentially, and observe the printed results and plots.
