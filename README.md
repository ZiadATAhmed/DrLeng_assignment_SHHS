# Sleep Analysis and HRV Project

## Overview
This project contains two main Jupyter notebooks for analyzing sleep stages and heart rate variability (HRV):
- Task 1: HRV analysis and survival modeling
- Task 2: Automatic sleep staging evaluation

## Features
- ECG signal processing and HRV metrics computation
- Sleep stage classification
- Survival analysis with Cox proportional hazards models
- Automated report generation
- Comprehensive visualization tools

## Requirements
- Python 3.8+
- Required packages:
  - numpy
  - pandas
  - mne
  - yasa
  - pyedflib
  - hrvanalysis
  - lifelines
  - scikit-learn
  - matplotlib
  - seaborn
  - tqdm

## Installation
1. Clone the repository:
```bash
git clone https://github.com/ZiadATAhmed/DrLeng_assignment_SHHS.git
cd DrLeng_assignment_SHHS
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Place your EDF files in the `dataset/` directory
2. Place corresponding NSRR XML files in the same directory
3. Run the notebooks:
   - `20250203_Task_1_clean.ipynb` for HRV analysis
   - `20250203_Task_2_clean.ipynb` for sleep staging

## Output
- HRV metrics: `hrv_data.csv`
- Model reports: `model_report_*.pdf`
- Analysis plots: `results_*/*.png`
- Log files: `logs/*.log`

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Ziad AT Ahmed
