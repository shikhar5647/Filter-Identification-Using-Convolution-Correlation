# Filter-Identification-Using-Convolution-Correlation
Identify the type of filtering applied to an input signal using convolution and correlation. This project implements Low Pass, High Pass, and Band Pass filters, compares their filtered outputs with the given output signal, and determines the best-matched filter.

This repository contains code for a project on signal processing and systems analysis. The project focuses on identifying the type of filtering applied to an input signal to produce a given output signal. Three types of filters are implemented: Low Pass, High Pass, and Band Pass. The methodology involves convolving each filter with the input signal to obtain filtered outputs, and then comparing these outputs with the given output signal using correlation.

## Signal Filtering
Signal filtering is a fundamental concept in signal processing, which involves modifying or extracting information from signals. In this project, we implement three types of filters:

# Low-Pass Filter:
A low-pass filter allows signals with frequencies lower than a specified cutoff frequency to pass through while attenuating higher frequencies. It is commonly used for noise reduction and smoothing applications.

# High-Pass Filter:
A high-pass filter allows signals with frequencies higher than a specified cutoff frequency to pass through while attenuating lower frequencies. It is often used for removing baseline drift and extracting high-frequency components from signals.

# Band-Pass Filter:
A band-pass filter allows signals within a specified frequency range (bandwidth) to pass through while attenuating frequencies outside the range. It is useful for isolating specific frequency components in signals, such as in applications involving modulation or demodulation.

## Correlation Analysis
Correlation analysis is a statistical technique used to measure the strength and direction of the relationship between two variables. In this project, we calculate the correlation between the filtered input signal and the corresponding output signal. A high correlation indicates a strong linear relationship between the signals, while a low correlation suggests a weaker or no relationship.

## Features

- Implementation of Low Pass, High Pass, and Band Pass filters.
- Convolution of filters with input signal to obtain filtered outputs.
- Correlation-based comparison between filtered outputs and given output signal.

## Usage

1. Clone the repository to your local machine:

    ```
    git clone https://github.com/shikhar5647/Filter-Identification-Using-Convolution-Correlation.git
    ```

2. Install the required dependencies:

    ```
    pip install numpy scipy
    ```

3. Navigate to the cloned repository directory:

    ```
    cd Filter-Identification-Using-Convolution-Correlation
    ```
