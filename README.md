# GW150914 Gravitational Wave Signal Processing

A Python signal processing and data analysis pipeline to extract, filter, and visualize the first directly detected gravitational wave signal (**GW150914**) from raw LIGO interferometer strain data.

## Overview

Raw gravitational wave detector data is dominated by low-frequency seismic noise, thermal noise, and narrowband instrumental artifacts (such as power line harmonics and violin modes). This project processes the 32-second raw strain recordings from both LIGO observatories—**Hanford (H1)** and **Livingston (L1)**—to isolate the characteristic binary black hole merger "chirp" signal around GPS time `1126259462` ($\approx 0.25\text{ s} - 0.46\text{ s}$ in the event window).
