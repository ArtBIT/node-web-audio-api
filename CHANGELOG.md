## v0.6.0 - Feb 2023

- Basic support for mediaDevices & MediaStreamAudioSourceNode
- Add bindings to ConvolverNode, AnalyserNode & Panner nodes
- Update upstream crate to v0.26

## v0.5.0 - Dec 2022

- Implement AudioParam#setValueCurveAtTime
- Offline context constructor 

## v0.4.0 - Nov 2022

- Implement offline audio context
- Update upstream crate to v0.24 
- Implement AudioNode#disconnect
- Properly support ESM
- Limit number of online contexts to 1 on Linux
- Force latencyHint to 'playback' if not manually set on RPi
