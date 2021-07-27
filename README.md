# CCSNet: a deep learning modeling suite for CO2 storage

The data set and pre-trained models were used in the above manuscript published in Advances in Water Resources

## 1. Data sets

The data set is available at https://drive.google.com/drive/folders/1SVZFkaxkAIjcGKew3rzGTmKW5tSBUGf7?usp=sharing 

*Note: variable name is same as file name.*

#### Train:
- Input: `train_x.h5`
- Gas saturation: `trian_y_SG.h5` 
- Reservoir pressure: `train_y_BPR.h5`
- Initial pressure: `train_y_P_init.h5`
- xCO2 molar fraction: `train_y_BXMF.h5`
- yCO2 molar fraction: `train_y_BYMF.h5`
- Liquid phase density: `train_y_BDENW.h5`
- Gas phase density: `train_y_BDENG.h5`

#### Test:
- Input: `test_x.h5`
- Gas saturation: `test_y_SG.h5` 
- Reservoir pressure: `test_y_BPR.h5`
- Initial pressure: `test_y_P_init.h5`
- xCO2 molar fraction: `test_y_BXMF.h5`
- yCO2 molar fraction: `test_y_BYMF.h5`
- Liquid phase density: `test_y_BDENW.h5`
- Gas phase density: `test_y_BDENG.h5`

## 2. Pre-trained models

The data set is available at https://drive.google.com/drive/folders/1SVZFkaxkAIjcGKew3rzGTmKW5tSBUGf7?usp=sharing 

- Gas saturation: `trained_models/SG_v1.h5` 
- Pressure buildup: `trained_models/dP_v1.h5`
- xCO2 molar fraction: `trained_models/bxmf_v1.h5`
- yCO2 molar fraction: `trained_models/bymf_v1.h5`
- Liquid phase density: `trained_models/bdenw_v1.h5`
- Gas phase density: `trained_models/bdeng_v1.h5`