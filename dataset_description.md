outcomes.csv:
- nsrrid: subject ID
- censdate: time to last contact (days)
- vital: status at last contact (0=dead, 1=alive)

shhs1-dataset-0.21.0-subsampled.csv:
- The variable explanations can be found on https://sleepdata.org/datasets/shhs/variables

dataset:
- signal file: shhs1-<subject ID>.edf (can be loaded using python package `mne`, `pyedflib`, or others)
- annotation file: shhs1-<subject ID>-nsrr.xml (can be loaded using python package `xmltodict` or others), contains sleep stages, apnea, arousal, limb movement, etc.
