# Hand_Gesture_Classification

## Evaluation of the Feasibility of Classifying Various Upper Limb Movements Using Multichannel Upper-Arm sEMG Signals

**Daehui Kim¹, Junghun Kim²,*, Sang-Il Choi²,***

¹ Department of Computer Software, Daegu Catholic University, Gyeongsangbuk-do, 38430, Republic of Korea  
² School of Computer Software, Daegu Catholic University, Gyeongsangbuk-do, 38430, Republic of Korea  

*Corresponding authors: fainal2@cu.ac.kr; sangilchoi@cu.ac.kr*

---

## Overview

This repository provides upper-arm surface electromyography (sEMG) data collected during various upper limb movements.

The dataset was constructed to evaluate the feasibility of classifying elbow, forearm, wrist, and hand movements using only multichannel upper-arm sEMG signals.

---

## Dataset Description

sEMG signals were recorded from five upper-arm muscle sites:

| Channel | Muscle |
|---|---|
| CH1 | Biceps brachii long head |
| CH2 | Biceps brachii short head |
| CH3 | Triceps brachii long head |
| CH4 | Triceps brachii lateral head |
| CH5 | Brachialis |

The signals were collected at a sampling frequency of **1000 Hz**.

The experiment included two posture conditions:

- **Static condition:** elbow fixed on a desk
- **Free condition:** elbow not fixed

Eight upper limb movements were performed:

| Label | Movement |
|---|---|
| CH | Hand Close |
| OH | Hand Open |
| WF | Wrist Flexion |
| WE | Wrist Extension |
| PRO | Forearm Pronation |
| SUP | Forearm Supination |
| EF | Elbow Flexion |
| EE | Elbow Extension |

---

## Repository Structure

    Hand_Gesture_Classification/
    ├── data/
    │   ├── CH1_a.csv
    │   ├── CH1_b.csv
    │   ├── CH1_c.csv
    │   ├── ...
    │   └── ...
    ├── .gitignore
    └── README.md

---

## File Naming Rule

The data files are named according to the following format:

    CH[channel number]_[movement label].csv

Example:

    CH1_a.csv
    CH1_b.csv
    CH1_s_a.csv

Files including `_s_` indicate the static condition.

---

## Data Usage

This dataset can be used for research on:

- sEMG-based upper limb movement classification
- hand and wrist gesture recognition
- upper-arm sEMG signal analysis
- machine learning-based biosignal classification

---

## Ethical Approval

The data used in this study were collected after obtaining approval from the Institutional Review Board (IRB) of Kyungpook National University Hospital.

All participants provided written informed consent before participating in the experiment.

---

## Citation

If you use this dataset or repository in your research, please cite the following work:

    @article{kim_upperarm_semg_2026,
      title   = {Evaluation of the Feasibility of Classifying Various Upper Limb Movements Using Multichannel Upper-Arm sEMG Signals},
      author  = {Kim, Daehui and Kim, Junghun and Choi, Sang-Il},
      journal = {Manuscript in preparation},
      year    = {2026}
    }

---

## License

This dataset is released for research and educational purposes only.

Please do not redistribute the data without permission from the authors.

---

## Contact

For questions about this repository, please contact:

**Daehui Kim**  
Department of Computer Software  
Daegu Catholic University  
Republic of Korea
