# Real-Time Audio Waveform Plotter

## Purpose:
This Python program captures audio from the microphone input, processes it, and displays the audio waveform in real-time.

## Components:
- **PyAudio**: For audio input and output operations.
- **NumPy**: For numerical operations and data manipulation.
- **Matplotlib**: For real-time waveform plotting.

## How it Works:
1. **Audio Capture**: Continuous capture of audio data from the microphone.
2. **Data Processing**: Processing raw audio data into numerical values and adjusting its range for plotting.
3. **Real-Time Plotting**: Matplotlib generates a plot window to display the audio waveform.
4. **Interactive Display**: Plot updates dynamically with new audio data.
5. **Termination Handling**: Graceful termination of plot window when closed, calculating and displaying average frame rate.


## Requirements:
- Python
- PyAudio
- NumPy
- Matplotlib

## Instructions:
1. Ensure all required libraries are installed.
2. Run the script.
3. Speak or produce audio near the microphone to observe the real-time waveform plot.


![Video](https://github.com/noone313/Audio-Spectrum-Analyzer/blob/main/audio.gif)
