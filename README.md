<p align="justify">
  The work represents comparison between modern deep learning and fusion models which
is solution to multiclass categorization (normal, cysts, tumors, stones) of renal disease
classification. The accuracy of detecting renal diseases is crucial for treatment. Despite
having machines interpret their CT scans, it is a labor-intensive exercise that takes time.
Furthermore, it can vary greatly between skilled observers and less skilled ones since the
pathological classes look visually similar. The MFC-Net study was designed as an
automated diagnostic framework to classify renal abnormality with top-notch precision as
well as accuracy. The proposed architecture fuses feature representations from three
different CNN backbones which are EfficienetB3, MobilenetV2, and Xception using a
custom Multi-Head Attention. This fusion method gives weight to important spatial and
textural characteristics while minimizing the background noise. Further, Focal Loss is
adopted to confront the major class imbalance found in medical datasets, enabling strong
learning of the minority classes. The CT Kidney Dataset had 12,446 images and was used
to evaluate the model based on five baseline architectures (ResNet50, DenseNet121,
MobileNetV2, Xception, and EfficientNetB3). We obtain a state-of-the-art weighted F1-
Score of 99.95%, which is slightly better than the best baseline (99.84%). In addition to
this, we validated the interpretation of the model using Grad-CAM and Grad-CAM++.
These confirmed that the model localizes pathological areas and can do this based on the
pathology without relying on artefacts. MFC-Net enabled an accurate and explainable
computer-aided diagnosis of nephrology indicating its usefulness.
</p>
