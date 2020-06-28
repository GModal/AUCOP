## AUCOP-guitarToy16x

AUCOP-guitarToy16x is a 16x-oversampled guitar audio processor. It includes a custom distortion module, an unusual filter module and a set of presets.

See the AUCOP parent README for installation instructions.

![gtoy pic](../webstuff/guitarToy.png)

## Plugin use (copy of Info.txt)
---
AUCOP-guitarToy16x is a guitar-oriented effect plugin, with 16x oversampled distortion and simple but powerful pre-filter.

### USE:
--Click on the Preset buttons to reset the parameters. These are loaded from a text file at start-up.

#### Parameters:

- Gain: Distortion gain.
- Squash Peaks: Asymmetrically down-scale the peaks after the first level of distortion is appled. This does lower amplitude, so compensate with Level.
- Low Pass In: Low-pass filter applied after up-sampling.
- Low Pass Out: Low-pass filter applied before down-sampling.
- Scale: Perform a destructive Pre and Post scaling of the signal, before the distortion and after.

#### Preset section
- Preset: Click for preset in current Bank.
- Bank: Click to select Bank.

#### Filter section
- LFO Freq: The filter has an optional LFO to alter the center frequency. On/Off enables/disables the LFO.
- LFO Sweep Range: The center frequency is shifted by this amount by the LFO.
- Freq Center: Filter center frequency.
- Filter Q: The Q value of the filter.
- Filter Mix: Alter the filter mix between Band-Pass and Low-Pass.
- Mix Amount: Mix the filtered signal with the incoming signal.
- Level: Overall volume output level.


#### Notes:
A post-distortion filter is appled before the signal is upsampled. It's currently set to a low frequency, to suppress higher harmonic alias issues.

This corresponds (very) loosely to the frequency response of guitar speakers.

#### AUCOP: An Unfortunate Collection Of Plugins

Plugin build from a PureData vanilla patch, with Camomile.

---
