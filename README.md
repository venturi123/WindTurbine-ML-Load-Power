# WindTurbine-ML-Load-Power

This repository contains the implementation of our paper ["Towards machine learning applications for structural load and power assessment of wind turbine: An engineering perspective"](https://doi.org/10.1016/j.enconman.2024.119275) published in Energy Conversion and Management.

## Getting Started

### Installation

1. Clone this repository:
```bash
git clone https://github.com/qlwang/WindTurbine-ML-Load-Power.git
cd WindTurbine-ML-Load-Power
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Download the model weights from the `Releases` page.

### Usage

#### Load the pre-trained model

```python
import joblib

model = joblib.load('RandomForestRegressor.joblib')
```

## Citation

If you find this code useful in your research, please consider citing our paper:

```bibtex
@article{WANG2025119275,
  title = {Towards machine learning applications for structural load and power assessment of wind turbine: An engineering perspective},
  journal = {Energy Conversion and Management},
  volume = {324},
  pages = {119275},
  year = {2025},
  issn = {0196-8904},
  doi = {https://doi.org/10.1016/j.enconman.2024.119275},
  url = {https://www.sciencedirect.com/science/article/pii/S0196890424012160},
  author = {Qiulei Wang and Junjie Hu and Shanghui Yang and Zhikun Dong and Xiaowei Deng and Yixiang Xu},
  keywords = {Wind turbine, Dynamic wake meandering model (DWM), Fatigue analysis, Machine learning}
}
```