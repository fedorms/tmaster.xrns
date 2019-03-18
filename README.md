![Screenshot](https://i.imgur.com/uFaQxRi.png)

# Motto
An advanced, versatile, and easy-to-use mastering template for Renoise.

# Introduction
Advanced mastering techniques are indeed possible in Renoise, I made a project file to prove it. This template works by using native Renoise DSP devices to achieve signal summation and subtraction to achieve mid/side processing. In short, a source signal is "split" into two signals and sent to their respective mixer tracks, the Mid and Side. It is then "joined" (sent) to a track labeled "M+S" before finally being sent to a track called "Mst" (not to be confused with Renoise's master bus). Additionally, each signal, Mid, Side, and M+S, is subdivided into 3 bands to allow for multiband processing (such as multiband compression, distortion), and is summed again into a "Sum" track to allow for post-processing.

Note: The "M+S" track's post-processing bus is referred to "Mst" rather than "Sum", and carries its own seperate color.

# Features
* Renoise-native functionality, guaranteeing cross-platform compatibility.
* Easy to use drag-and-drop functionality.
* Autoseek, oversampling, and high-quality sinc interpolation enabled. Scroll with ease.
* Mid/side signal processing.
* Multiband processing, followed by a post-processing track.
* An easily soloable reference track to quickly compare your work.
* Project internals and processing hidden from plain sight.
* Default effects such as a limiter and exciter in the "master".
* 8n butterworth digital high-pass filters, 2x oversampled, on the mid and side to get rid of unwanted frequencies.
* A "Mono Tester" device that allows you to play your mix in mono to simulate non-directional listening environments.

# Usage
* Use on any Renoise 3.1-compatible platform.
* Safely convertable to 3.0. Convertable to 2.7, 2.8 with changes.
* Just drag-and-drop.
* Add all DSP effects and devices before devices marked with a **#** or the effects will not work.
* Use 24-bit or 32-bit renders to have low noise floors. This is crucial when processing dynamics.
* You can work solely from the Mixing and Sampling tabs, with minimal mouse involvement.
* **Mastering is not a substitute for a good mix!**

# Latency
The total latency of the standard project file is 0.34 ms. Approximately 5 ms should be expected in typical projects.

# Licensing
As of writing this, I am releasing this project file to the public domain.
