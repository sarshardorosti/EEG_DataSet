# Public EEG Datasets

**Project Description**: A curated list of public EEG datasets for brain-computer interfaces and neuroscience research, with verified links to motor imagery, emotion recognition, clinical EEG, and more. Contributions welcome!

## Overview

This repository serves as a comprehensive resource for researchers, students, and professionals in brain-computer interfaces (BCI), neuroscience, and related fields, providing a curated collection of publicly available electroencephalography (EEG) datasets. Covering diverse applications such as motor imagery, emotion recognition, clinical EEG analysis, and more, this list aims to facilitate reproducible research and innovation. Each dataset includes a brief description and a verified address linking to its source, ensuring accessibility and accuracy. The repository is actively maintained, and contributions to expand or update the dataset list are encouraged.

**Note**: All links have been verified as active and accessible as of June 7, 2025. Some datasets linked to articles may require contacting authors for access, and certain repositories necessitate searching for specific datasets. For the latest updates, explore platforms like OpenNeuro (Address: https://openneuro.org/) or ElectrophysiologyData (Address: https://github.com/openlists/ElectrophysiologyData).

## Table of Contents
- [Motor Imagery](#motor-imagery)
- [Emotion Recognition](#emotion-recognition)
- [Error-Related Potentials (ErrP)](#error-related-potentials-errp)
- [Visually Evoked Potentials (VEPs)](#visually-evoked-potentials-veps)
- [Event-Related Potentials (ERPs)](#event-related-potentials-erps)
- [Slow Cortical Potentials (SCPs)](#slow-cortical-potentials-scps)
- [Resting State](#resting-state)
- [Music and EEG](#music-and-eeg)
- [Eye Blinks/Movements](#eye-blinks-movements)
- [Clinical EEG](#clinical-eeg)
- [Miscellaneous](#miscellaneous)
- [Additional Resources](#additional-resources)
- [Contributing](#contributing)
- [License](#license)

## Motor Imagery
- **Left/Right Hand MI**: 52 subjects (38 validated), physiological/psychological questionnaires, EMG, 3D EEG electrodes, non-task EEGs.  
  Address: http://gigadb.org/dataset/100295
- **Motor Movement/Imagery Dataset (Physionet MI)**: 109 volunteers, 64 electrodes, baseline tasks (eye-open/closed), motor movement, and imagery (fists/feet). Over 1500 one- and two-minute EEG recordings. Cited in 3 papers, 1 benchmark.  
  Address: https://www.physionet.org/physiobank/database/eegmmidb/
- **Grasp and Lift EEG Challenge**: 12 subjects, 32 channels@500Hz, 6 grasp/lift events (HandStart, FirstDigitTouch, etc.).  
  Address: https://www.kaggle.com/c/grasp-and-lift-eeg-detection/data
- **BCI Competition IV-2a (BNCI 2014-001)**: 22-electrode dataset, 9 subjects, 2 sessions, 288 four-second trials of imagined movements (left hand, right hand, feet, tongue).  
  Address: http://www.bbci.de/competition/iv/#dataset2a
- **High-Gamma Dataset**: 128-electrode dataset, 14 subjects, ~1000 four-second trials of executed movements (left hand, right hand, feet, rest). Described in Schirrmeister et al. 2017, cited in 2 papers.  
  Address: https://github.com/robintibor/high-gamma-dataset
- **Large EEG Database for MI BCI**: 87 participants, 3 datasets, right and left hand motor imagery, user profile information.  
  Address: https://zenodo.org/record/8089820
- **BCI Competition IV-2b (BNCI 2014-002)**: 9 subjects, 3 electrodes, 5 sessions, left and right hand motor imagery with online feedback.  
  Address: http://www.bbci.de/competition/iv/#dataset2b
- **Motor Imagery Under Distraction BCI Dataset**: 16 subjects, motor imagery with distractions (flickering video, searching, etc.).  
  Address: https://depositonce.tu-berlin.de/items/0f01eb46-4e6e-427a-9a68-b264a839615f
- **AlexMI (Alex Motor Imagery Dataset)**: Motor imagery dataset from A. Barachant’s PhD dissertation.  
  Address: https://github.com/alexandrebarachant/BCI-MI-Dataset
- **BMI/OpenBMI Dataset for MI**: EEG dataset and toolbox for three BCI paradigms, including motor imagery.  
  Address: http://gigadb.org/dataset/100542
- **BCI Competition 2008 Dataset B (BNCI 2014-004)**: Motor imagery dataset from BCI Competition 2008.  
  Address: http://www.bbci.de/competition/iv/#dataset1
- **BNCI 2015-001 Motor Imagery Dataset**: Motor imagery dataset with detailed paradigm descriptions. Search for BNCI2015_001.  
  Address: http://bnci-horizon-2020.eu/database/data-sets
- **BNCI 2015-004 Motor Imagery Dataset**: Motor imagery dataset with specific experimental protocols. Search for BNCI2015_004.  
  Address: http://bnci-horizon-2020.eu/database/data-sets
- **Motor Imagery Dataset from Cho et al. 2017**: Motor imagery with left hand, right hand, and feet tasks, 4 subjects.  
  Address: https://github.com/cho2017/MI-EEG-Dataset
- **Motor Imagery Dataset from Ofner et al. 2017**: Upper limb motor imagery, 15 subjects, aged 22-40 years.  
  Address: https://zenodo.org/record/1158046
- **Motor Imagery Dataset from Weibo et al. 2014**: EEG oscillatory patterns during simple and compound limb motor imagery. Data may require author contact.  
  Address: https://doi.org/10.1371/journal.pone.0114853
- **Motor Imagery Dataset from Zhou et al. 2016**: Automated trial selection for motor imagery BCI, 4 subjects. Available via MOABB.  
  Address: https://moabb.neurotechx.com/docs/datasets.html
- **Munich Motor Imagery Dataset**: Motor imagery dataset from Grosse-Wentrup et al. 2009. Available via MOABB.  
  Address: https://moabb.neurotechx.com/docs/datasets.html

## Emotion Recognition
- **DEAP**: 32 subjects, music-video excerpts rated for arousal/valence/like-dislike/dominance/familiarity, frontal face recordings for 22/32. Includes EEG, physiological signals, and video data. Cited in 11 papers, 1 benchmark.  
  Address: http://www.eecs.qmul.ac.uk/mmv/datasets/deap/
- **SEED (SJTU Emotion EEG Dataset)**: 15 subjects, EEG signals while watching film clips to induce positive, negative, and neutral emotions. Cited in 114 papers, 638 benchmarks.  
  Address: http://bcmi.sjtu.edu.cn/-seed/seed.html
- **SEED-V**: 15 subjects, video clips for happy/sad/neutral/fear emotions, 62 EEG channels with eye-tracking.  
  Address: http://bcmi.sjtu.edu.cn/-seed/seed-v.html
- **NeuroMarketing**: 25 subjects, 14 electrodes, Like/Dislike on e-commerce products. Data may require author contact.  
  Address: https://link.springer.com/article/10.1007/s11042-017-4580-6
- **EEG Brainwave Dataset: Feeling Emotions**: EEG recordings for positive and negative emotions.  
  Address: https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-feeling-emotions
- **GAMEEMO Dataset**: 28 subjects, EEG while playing games to elicit emotions (boring, calm, horror, funny).  
  Address: https://data.mendeley.com/datasets/b3pn4kwpmn/3
- **FACED Dataset**: 123 subjects, 9 emotion categories (amusement, joy, etc.) induced by video clips, 32 EEG channels.  
  Address: https://www.synapse.org/#!Synapse:syn50614194
- **AMIGOS**: 40 participants, EEG, ECG, GSR during short and long emotional videos, individual and group settings, with affect, personality, and mood annotations. Cited in 31 papers, 1 benchmark.  
  Address: http://www.eecs.qmul.ac.uk/mmv/datasets/amigos/
- **PhyMER**: 30 participants, EEG, EDA, BVP, temperature, with arousal, valence, and personality annotations.  
  Address: https://zenodo.org/record/5802417

## Error-Related Potentials (ErrP)
- **BCI-NER Challenge**: 26 subjects, 56 EEG channels, P300 Speller task, labeled for correct/incorrect decoding.  
  Address: https://www.kaggle.com/c/inria-bci-challenge
- **Monitoring ErrP in Target Selection**: 6 subjects, 64 EEG electrodes, cursor movement task, labeled responses.  
  Address: http://bnci-horizon-2020.eu/database/data-sets
- **HCI-Tagging (MAHNOB-HCI)**: Subjects viewed images/movie fragments with tags, recorded with audio/video/gaze/EEG. Cited in 1 paper.  
  Address: https://mahnob-db.eu/hci-tagging/
- **ErrPs during continuous feedback**: 10 subjects, 28 EEG electrodes, playing a video game to study execution and outcome error.  
  Address: https://www-ti.informatik.uni-tuebingen.de/-spueler/eeg_data/Continous_ErrP_dataset_Part1.rar
- **BCI-Double-ErrP-Dataset**: EEG dataset with P300 and ErrP for error detection and correction in a BCI speller.  
  Address: https://ieee-dataport.org/documents/errp-dataset

## Visually Evoked Potentials (VEPs)
- **c-VEP BCI**: 9 subjects, 32 EEG channels, VEP BCI speller, labeled responses.  
  Address: https://www-ti.informatik.uni-tuebingen.de/-spueler/eeg_data/cVEP_dataset.rar
- **SSVEP - Visual Search/Discrimination and Handshake**: 30 subjects, 14 electrodes, visual search and handshake tests.  
  Address: https://www.kaggle.com/berkeley-biosense/synchronized-brainwave-dataset
- **Multi-frequency SSVEP Dataset**: SSVEPs from 35 participants using single-, dual-, and tri-frequency stimulation.  
  Address: https://doi.org/10.26188/22015694
- **MAMEM SSVEP Database**: 11 subjects, 256 channels, SSVEP with flickering lights.  
  Address: https://physionet.org/content/mssvepdb/1.0.0/
- **SEED-VIG**: EEG features (PSD, DE) from 17 subjects during a simulated driving task, vigilance labels, 17 EEG channels. Cited in 2 papers.  
  Address: http://bcmi.sjtu.edu.cn/-seed/seed-vig.html

## Event-Related Potentials (ERPs)
- **Pattern Visual Evoked Potentials**: 2 subjects, checkboard pattern, oddball paradigm, related to Brain Invaders ERP data.  
  Address: https://zenodo.org/record/2649069
- **Face vs. House Discrimination**: 7 epileptic subjects, 50 grayscale face/house stimulations, 3 runs.  
  Address: https://purl.stanford.edu/xd109qh3109
- **Target vs. Non-Target (Brain Invaders)**: Multiple datasets, visual P300 BCI, oddball paradigm, 16-32 electrodes.  
  Address: https://zenodo.org/record/2649069
- **ERP-CORE Dataset**: 40 subjects, 6 ERP paradigms (N170, MMN, N2pc, N400, P3, LRP).  
  Address: https://osf.io/thsqg/
- **Kilo-word ERP Database**: 75 subjects, lexical decision task with 960 words.  
  Address: https://osf.io/72b89/

## Slow Cortical Potentials (SCPs)
- **Mental-Imagery Dataset**: 13 participants, 60,000+ motor imagery examples, 4 paradigms, 38-channel medical-grade EEG.  
  Address: https://doi.org/10.6084/m9.figshare.c.3917698
- **SCP EEG Dataset (Kaggle)**: Processed EEG signals showing cortical negativity or positivity.  
  Address: https://www.kaggle.com/datasets/towsifahamed/eeg-dataset-of-slow-cortical-potentials
- **BCI Competition II Dataset Ia**: Self-regulation of slow cortical potentials.  
  Address: https://www.bbci.de/competition/ii/#datasetIa

## Resting State
- **Resting State EEG Data**: 22 subjects, 72 EEG channels, 8-min resting task (4 min eyes closed, 4 min eyes open).  
  Address: https://dataverse.tdl.org/dataverse/txstatecogelectro
- **EID-M, EID-S**: 8 subjects, rest state (eyes closed), 14 electrodes, 54s@128Hz. Data may require author contact.  
  Address: https://ieeexplore.ieee.org/document/8310281
- **Dortmund Vital Study Resting-State EEG Dataset**: 608 subjects, resting-state before and after cognitive tasks, with longitudinal data. Data may require further action.  
  Address: https://www.nature.com/articles/s41597-024-03797-w
- **ADHD Resting-State EEG Dataset**: 60 adults (30 ADHD, 30 controls), resting state EEG.  
  Address: https://openneuro.org/datasets/ds003775
- **Age and Gender Dataset**: 60 users (aged 6-55 years, 25 females, 35 males), resting EEG from 14 electrodes@128Hz. Cited in 1 paper.  
  Address: https://data.mendeley.com/datasets/h5n6d3h6g3/1
- **CWL EEG/fMRI Dataset**: 8 subjects, EEG/fMRI during eyes open/closed task. Cited in 3 papers, 1 benchmark.  
  Address: https://openneuro.org/datasets/ds002330

## Music and EEG
- **Music Imagery Information Retrieval**: 10 subjects, 64 EEG channels, music imagery task with 12 pieces.  
  Address: https://github.com/sstober/openmiir
- **MUSIN-G EEG Dataset**: 20 subjects, EEG during listening to 12 songs of different genres, with familiarity and enjoyment ratings.  
  Address: https://openneuro.org/datasets/ds003774
- **NMED-T Dataset**: 20 subjects, EEG during music listening with different tempos, behavioral data.  
  Address: https://exhibits.stanford.edu/data/catalog/jn859kj8079

## Eye Blinks/Movements
- **EEG-eye state**: 117s continuous EEG, eye-closed/open labels, recorded with Emotiv headset.  
  Address: https://archive.ics.uci.edu/ml/datasets/EEG+Eye+State
- **EEGEyeNet**: EEG and eye-tracking, 356 subjects, 3 paradigms (left-right, angle-amplitude, absolute position), 128 channels. Cited in 10 papers.  
  Address: https://osf.io/5n6fm/
- **Ocular Activity BCI Dataset**: EEG, eye-tracking, and video data for ocular activities in BCI tasks. Data may require further action.  
  Address: https://www.nature.com/articles/s41597-025-04861-9

## Clinical EEG
- **TUH EEG Resources**: Massive dataset for abnormal EEG and seizures.  
  Address: https://isip.piconepress.com/projects/tuh_eeg/
- **Predict-UNM**: Large repository of clinical EEG datasets.  
  Address: http://predict.cs.unm.edu/downloads.php
- **Siena Scalp EEG Database**: 14 patients with epilepsy, EEG and EKG, sampled at 512Hz, 10-20 system. Cited in 1 paper.  
  Address: https://physionet.org/content/siena-scalp-eeg/1.0.0/
- **CHB-MIT Scalp EEG Database**: Pediatric subjects with intractable seizures, 969 hours of EEG with 173 seizures, 23 patients. Cited in 6 papers, 1 benchmark.  
  Address: https://physionet.org/content/chbmit/1.0.0/
- **BIDS CHB-MIT Scalp EEG Database**: BIDS-compatible version of CHB-MIT Scalp EEG Database. Cited in 1 paper.  
  Address: https://openneuro.org/datasets/ds003017
- **BIDS Siena Scalp EEG Database**: BIDS-compatible version of Siena Scalp EEG Database. Cited in 1 paper.  
  Address: https://openneuro.org/datasets/ds003019
- **TUAC (Temple University Artifact Corpus)**: EEG artifacts (chewing, electrode, eye movement, muscle, shiver), annotated for suppression research. Cited in 1 paper.  
  Address: https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml
- **SeizeIT1**: Behind-the-ear EEG from patients during presurgical evaluation for epilepsy. Cited in 1 paper.  
  Address: https://zenodo.org/record/6347355
- **I-CARE**: EEG and ECG from comatose patients post-cardiac arrest, ICU monitoring.  
  Address: https://physionet.org/content/icare/1.0/

## Miscellaneous
- **MNIST Brain Digits**: EEG for digits (0-9) shown to a subject, 2s recordings, 1.2M+ samples.  
  Address: https://github.com/pbashivan/EEGLearn
- **ZuCo**: EEG and eye-tracking, 12 subjects, reading natural English text, 21,629 words.  
  Address: https://osf.io/q3zws/
- **Sleep-EDF Database**: 197 whole-night polysomnographic sleep recordings, EEG, EOG, chin EMG, event markers, hypnograms. Cited in 93 papers, 5 benchmarks.  
  Address: https://physionet.org/content/sleep-edfx/1.0.0/
- **BCI Competition III Dataset V**: Mental imagery tasks (arithmetic, letter composition, etc.), 3 subjects.  
  Address: https://www.bbci.de/competition/iii/#datasetV
- **Montreal Archive of Sleep Studies (MASS)**: Laboratory-based polysomnography recordings for sleep analysis, human-scored. Cited in 15 papers, 7 benchmarks.  
  Address: https://massdb.herokuapp.com/
- **MODA Dataset**: 5342 human-scored sleep spindles from 180 subjects, median 5 expert scorers. Cited in 1 paper, 1 benchmark.  
  Address: https://zenodo.org/record/1003201
- **Maintenance of Wakefulness Test (MWT) Recordings**: EEG with microsleep episodes and drowsiness. Cited in 1 paper.  
  Address: https://physionet.org/content/mwt/1.0.0/
- **STEW (Simultaneous Task EEG Workload Dataset)**: 48 subjects, EEG during SIMKAP multitasking test, 14 channels@128Hz, workload ratings. Cited in 1 paper.  
  Address: https://www.kaggle.com/datasets/sharifulhaqueemon/stew-simultaneous-task-eeg-workload
- **PhyAAt (Physiology of Auditory Attention)**: EEG, GSR, PPG from auditory attention experiment on natural speech. Cited in 4 papers, 4 benchmarks.  
  Address: https://phyaat.github.io/
- **eSports Sensors Dataset**: 10 players, 22 League of Legends matches, EEG and physiological signals. Cited in 4 papers, 2 benchmarks.  
  Address: https://data.mendeley.com/datasets/2k7bnv7p55/1
- **EEG Speech-Robot Interaction Dataset**: 15 subjects, EEG during spoken and imagined speech with a simulated robot, 64 channels. Cited in 1 paper.  
  Address: https://zenodo.org/record/5035944
- **AutoTherm**: 31 sensor signals, EEG, and thermal comfort ratings from 18 participants in climatic chamber and 20 in-vehicle. Cited in 1 paper.  
  Address: https://data.mendeley.com/datasets/4x5p2kvrnm/1
- **Mental Arithmetic Dataset from Shin et al. 2017**: EEG and NIRS during mental arithmetic tasks, 30 electrodes@1000Hz.  
  Address: https://figshare.com/articles/dataset/EEG_and_NIRS_data_during_mental_arithmetic_tasks/1234570
- **WWU DUNEuro Reference Dataset**: High-quality head models, combined EEG/MEG data for source analysis. Cited in 1 paper.  
  Address: https://zenodo.org/record/4541339

## Additional Resources
Explore these platforms for additional EEG datasets:
- **BrainSignals**: Lists EEG datasets, some links may require verification.  
  Address: http://www.brainsignals.de/
- **OpenNeuro**: Comprehensive platform for neuroimaging datasets.  
  Address: https://openneuro.org/
- **PhysioNet**: Includes EEG and other physiological data.  
  Address: https://www.physionet.org/
- **BIDS Examples**: BIDS-formatted EEG datasets.  
  Address: https://github.com/bids-standard/bids-examples
- **NEMAR**: ~200 BIDS-formatted MEEG experiments.  
  Address: https://NEMAR.org
- **Zenodo**: General repository with many EEG datasets.  
  Address: https://zenodo.org/
- **Figshare**: Repository hosting scientific data, including EEG.  
  Address: https://figshare.com/
- **IEEE DataPort**: Datasets from IEEE, including EEG.  
  Address: https://ieee-dataport.org/

## Contributing
We welcome contributions to enhance this repository. To contribute:
1. Verify dataset links and update their status if outdated.
2. Add new EEG datasets with descriptions and verified addresses.
3. Submit pull requests with clear, descriptive commit messages.

Please review the [CONTRIBUTING.md](CONTRIBUTING.md) file for detailed guidelines. For questions or suggestions, open an issue or contact the maintainers.

## License
This repository is licensed under the [MIT License](LICENSE), allowing free use, modification, and distribution of the content, subject to the terms outlined in the license file.
