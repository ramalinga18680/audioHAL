# audioHAL
This project aims at creating the audio HAL for an Odroid C2.

The Odroid C2 has the HDMI audio output as the primary output/input.
But i am keen on using the HDMI connector for display, without using a HDMI switch.

Now the other option is using a USB Audio Adapter for speaker and microphone.
Additionally have a Sony PS3 eye which has its own mic.

Now this HAL is to make use of the MIC of Sony PS3 eye for CAMCORDER use cases,
and the MIC from the USB audio adapter for all other use cases.

The idea is to customize or provide custom implementation for the AudioPolicyManager to realize the above.
