# Explainable microstructure-property predictions in steel

This project uses extracted features describing the M-A morphology, distances, statistics or direction from segmented images of bainite (based on M-A island detection and segmentation)
. These features are the input for building classification models in pycaret. The best-performing model (QDA) reaches 99% in accuracy and together with LR (2nd best) and LGBM (3rd best) we performed a SHAP analyses to retrieve local and global feature importance.