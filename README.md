# fNIRS_rigid-arithmetic-3bank
Functional Near-Infrared Spectroscopy (fNIRS) is a non-invasive neuroimaging technique that maps cognitive activity by monitoring hemodynamic changes (fluctuations in oxygenated and de-oxygenated hemoglobin).

This dataset was collected using a custom miniaturized rigid device with 3 sets of optodes placed on the prefrontal cortex (e.g., FP1) during mental arithmetic and resting periods. Details of the device and study protocol are published in  _Wearable Wireless Functional Near-Infrared Spectroscopy System for Cognitive Activity Monitoring_, M. Victorio, J. Dieffenderfer, T. Songkakul, J. Willeke, A. Bozkurt, V.A. Pozdin,
Biosensors 15(2), 92 (2025). https://doi.org/10.3390/bios15020092.  The three optode separations are: 15mm (bank 3), 17.5mm (bank 2), 20mm (bank 1).

The dataset includes data from 10-participants. The study followed two timing protocols:

Participants 1-5:
- **10** minutes of resting for baseline collection
- **5** cycles of
  - 2 minutes of 3-digit math
  - 2 minutes of rest (looking at screen with a countdown timer)
  - 2 minutes of 2-digit math
  - 2 minutes of rest (looking at screen with a countdown timer)
- 10 minutes of resting for baseline collection

Participants 6-10:
- **20** minutes of resting for baseline collection
- **3** cycles of
  - 2 minutes of 3-digit math
  - 2 minutes of rest (looking at screen with a countdown timer)
  - 2 minutes of 2-digit math
  - 2 minutes of rest (looking at screen with a countdown timer)
- **30** minutes of resting for baseline collection

Datasets are available as:
- RAW - raw ADC values
- CSV - data converted to deoxygenated hemoglobin (Hbb) and oxygenated hemoglobin (HbO) labelled with activity (_math2_ - 2-digit math, _math3_ - 3-digit math, _resting_, and _baseline_) 
- sMIRF - coming soon

- Data is available under 
