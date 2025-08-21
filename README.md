# myocarditis-mfm: A Multimodal Foundation Model for Myocarditis 



Hierarchical taxonomy of Cardiomyopathies:

```text
Myocardial Health
│
├── Normal
│
├── Myocarditis (Inflammatory disease)
│   ├── Viral
│   │    ├── Acute
│   │    └── Chronic → DCM
│   ├── Fulminant → Recovery (if survive)
│   ├── Autoimmune / ICI → ACM
│   ├── Ischemic overlap → ICM
│   └── Hypersensitivity / Toxin → RCM
│
└── Cardiomyopathy (Remodeled disease)
    ├── Dilated (DCM)
    ├── Restrictive (RCM)
    ├── Arrhythmogenic (ACM)
    ├── Ischemic (ICM)
    └── Recovered myocarditis (no CM)
```

References:
1. **Esteva, A.** _et al._ Dermatologist-level classification of skin cancer with deep neural networks. _Nature_ **542**, 115–118 (2017).
2. **Hannun, A. Y.** _et al._ Cardiologist-level arrhythmia detection and classification in ambulatory electrocardiograms using a deep neural network. _Nat. Med._ **25**, 65–69 (2019).
3. **Ouyang, D.** _et al.) Video-based AI for beat-to-beat assessment of cardiac function. _Nature_ **580**, 252–256 (2020).
4. **Dai, L.** _et al._ A deep learning system for predicting time to progression of diabetic retinopathy. _Nat. Med._ **30**, 584–594 (2024). https://doi.org/10.1038/s41591-023-02702-z
