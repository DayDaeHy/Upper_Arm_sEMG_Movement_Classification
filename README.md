# Upper_Arm_sEMG_Movement_Classification

## Evaluation of the Feasibility of Classifying Various Upper Limb Movements Using Multichannel Upper-Arm sEMG Signals

**Daehui Kim¹, Junghun Kim²\*, Sang-Il Choi²\***

¹ Department of Computer Software, Daegu Catholic University, Gyeongsangbuk-do, 38430, Republic of Korea  
² School of Computer Software, Daegu Catholic University, Gyeongsangbuk-do, 38430, Republic of Korea  

\* Corresponding authors: fainal2@cu.ac.kr; sangilchoi@cu.ac.kr

---

## Overview

This repository provides surface electromyography (sEMG) data recorded from upper-arm muscles during various upper limb movements.

The dataset was constructed to evaluate the feasibility of classifying elbow, forearm, wrist, and hand movements using only multichannel upper-arm sEMG signals.

---

## Dataset Description

sEMG signals were recorded from five upper-arm muscle sites.

| Channel | Muscle |
|---|---|
| CH1 | Biceps brachii long head |
| CH2 | Biceps brachii short head |
| CH3 | Triceps brachii long head |
| CH4 | Triceps brachii lateral head |
| CH5 | Brachialis |

The signals were collected at a sampling frequency of **1000 Hz**.

The experiment was conducted under two posture conditions.

- **Static condition:** elbow fixed on a desk
- **Free condition:** elbow not fixed

The following eight upper limb movements were performed.

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
    ├── LICENSE
    └── README.md

---

## File Naming Rule

The data files are named according to the following format.

    [movement label][trial number]_[participant label].csv
    [movement label][trial number]_s_[participant label].csv

Examples:

    CH1_a.csv
    CH1_s_a.csv
    CH2_a.csv
    CH2_s_a.csv

The file name consists of the movement label, trial number, posture condition, and participant label.

- `CH`, `OH`, `WF`, `WE`, `PRO`, `SUP`, `EF`, and `EE` indicate the movement labels.
- The number after the movement label indicates the trial session number.
- Files without `_s_` indicate data collected under the **static condition**.
- Files containing `_s_` indicate data collected under the **free condition**.
- The final alphabetic label indicates the participant.

For example:

- `CH1_a.csv` indicates data from participant `a`, collected during the 1st trial session of the hand close movement under the static condition.
- `CH1_s_a.csv` indicates data from participant `a`, collected during the 1st trial session of the hand close movement under the free condition.

Each movement was recorded for three trial sessions.

---

## Data Usage

This dataset can be used for research on:

- sEMG-based upper limb movement classification
- hand and wrist gesture recognition
- upper-arm sEMG signal analysis
- machine learning-based biosignal classification
- comparison of sEMG classification performance under different posture conditions

---

## Ethics Statement

This dataset was collected after Institutional Review Board (IRB) approval and written informed consent from all participants.

---

## Citation

If you use this dataset or repository in your research, please cite the related paper.

---

## License

This dataset is provided for research and educational purposes only.

Please see the [LICENSE](LICENSE) file for details.

---

## Contact

For questions regarding this repository, please contact the email below.

**eogml7732@gmail.com**
