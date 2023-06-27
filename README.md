# Deep learning-based age estimation from clinical Computed Tomography image data of the thorax and abdomen in the adult population

Aging is an important risk factor for disease, leading to morphological change that can be assessed on Computed Tomography (CT) scans.   We propose a deep learning model for automated age estimation based on CT-scans of the thorax and abdomen generated in a clinical routine setting.



A pre-trained ResNet-18 model was modified to predict chronological age as well as to quantify its aleatoric uncertainty. Generalization performance was assessed on a publicly available test dataset consisting of thorax-abdomen CT-scans of 421 subjects. Score-CAM saliency maps were generated for interpretation of model outputs and to identify hallmarks of aging.

The model and its weights are available in this project as well as the Score-CAM-implementation that was used and the preprocessing suite.

<img src="https://github.com/BjarneKerber/age_estimation/blob/main/images/fig_ex_img.jpg" alt="" title="Score-CAM saliency maps">

![The lumbar spine and abdominal aorta were highlighted as regions important for age estimation. The pattern was consistent over different age groups and even expressed in unusual subjects that differed from the majority. Higher values on the colorbar indicate higher importance.](https://github.com/BjarneKerber/age_estimation/blob/main/images/fig_score.jpg "Score-CAM saliency maps")
