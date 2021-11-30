# hologram-biometric-signal-parsing
Nonparametric multivariate two-sample testing of the Mind-X hologram time-series datasets by hyppo package developed by Vogelstein lab

## Motivation
This was a part of a contractual job requested by Mind-X, an AI company that specializes in signal processing and wearable technology. The task involved extracting a meaningful biometric signal from noisy multivariate time-series stored in Tensorflow data format, then deduce a statistically significant signal of origin by A/B testing.

## Basic Format of the Experiment
The human subjects were visually stimulated for a certain period of time. Their EEGs were collected during the entire period of segment of experiment where each individual underwent 10 segments per experiment. As EEGs are proned to environmental noise contamination, other physiological responses, such as EKG and PPG, are recorded as EEGs were collected.