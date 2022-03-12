# A visual representation of an EEG recording
An electroencephalography recording will be captured via a brain-computer interface. The EEG signal will be processed into a frequency-based representation (a spectrogram), which then will be used as input into a artistic representation that can be visually experienced.

Then another EEG recording will be captured, of the same participant as the previous recording. However under this scenario the participant will be viewing the previous artistic representation of their brainwaves.

Finally, the difference in brainwaves comparing the 1st to 2nd scenario will be determined (via further signal processing). This difference will be highlighted, in addition to both visual representations of both scenarios.

## Requirements
This project uses a Python-based environment for most computation. In particular, it leans on the BrainFlow and MNE packages for processing of data. This EEG data is acquired from a low-cost, brain-computer interface developed by OpenBCI.

For more information relating to these details check out the following, which is foundational to this project: [Acquiring & processing an electroencephalography signal](https://github.com/NicholasCHowlett/eegDataAnalysis).
