# Hand_Gesture_Classification

This repository contains the dataset used in the study:

**Evaluation of the Feasibility of Classifying Various Upper Limb Movements Using Multichannel Upper-Arm sEMG Signals**

## Overview

This dataset was collected to evaluate the feasibility of classifying various upper limb movements using five-channel upper-arm surface electromyography (sEMG) signals.

The sEMG signals were measured from five upper-arm muscles:

- Biceps brachii long head
- Biceps brachii short head
- Triceps brachii long head
- Triceps brachii lateral head
- Brachialis

The dataset includes recordings collected under two posture conditions:

- Static condition: movements were performed with the elbow supported.
- Free condition  : movements were performed without elbow support.

## Movements

Eight upper limb movements were included in this dataset:

- Elbow flexion (EF)
- Elbow extension (EE)
- Forearm pronation (PRO)
- Forearm supination (SUP)
- Wrist flexion (WF)
- Wrist extension (WE)
- Hand open (OH)
- Hand close (CH)

Each movement was repeated 30 times under each posture condition.

## Data Structure

The data files are stored in the `data` directory.

```text
Hand_Gesture_Classification/
├── data/
├── .gitignore
└── README.md


Data Acquisition

sEMG signals were recorded using a five-channel upper-arm configuration at a sampling frequency of 1000 Hz.

The collected signals were used for signal preprocessing, movement interval segmentation, sliding-window-based data segmentation, time-domain feature extraction, and machine learning-based classification.

Related Publication

This repository is associated with the following manuscript:

Daehui Kim, Junghun Kim, and Sang-Il Choi.
Evaluation of the Feasibility of Classifying Various Upper Limb Movements Using Multichannel Upper-Arm sEMG Signals

Usage

This dataset is provided for research and academic purposes.

If you use this dataset, please cite the related manuscript.

Contact

For questions regarding the dataset, please contact:

Junghun Kim
E-mail: fainal2@cu.ac.kr

Sang-Il Choi
E-mail: sangilchoi@cu.ac.kr
