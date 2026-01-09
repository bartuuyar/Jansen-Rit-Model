# Jansen-Rit-Model

## Overview

This project explores how a simple neural mass model (Jansen–Rit)
can reproduce key spectral properties of human EEG signals.

Rather than fitting the model to data, we analyze how model parameters
(shape of synaptic responses, excitatory gain, and noise)
control resonance frequency and power.

## Key Questions

- What determines EEG resonance frequency?
- What controls oscillation power?
- Which EEG features can (and cannot) be explained by neural mass models?

## Methods

- Jansen–Rit neural mass model
- Power spectral density (Welch method)
- Parameter sweeps over synaptic time constants and gains
- Comparison with real EEG data (PhysioNet EEG Motor Imagery dataset)

## Main Findings

- Synaptic time constants determine resonance frequency
- Excitatory gain controls oscillation power
- Noise amplifies but does not create oscillations
- Model reproduces qualitative EEG spectral structure (1/f + band-limited resonance)
