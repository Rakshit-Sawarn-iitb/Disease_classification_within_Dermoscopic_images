# Disease_classification_within_Dermoscopic_images

Dermoscopic lesion imaging, like many diagnostic medical exams, produces a long-tailed distribution of clinical findings; while a small subset of diseases are routinely observed, the vast majority of diseases are relatively rare. This poses a challenge for standard AIML methods, which exhibit bias toward the most common classes at the expense of the important, but rare, “tail” classes. Many existing methods have been proposed to tackle this specific type of imbalance, though only recently with attention to long-tailed medical image recognition problems.
Diagnosis on dermoscopic lesion images is a multi-class problem, as each image is associated with a single disease class. This dataset has 10, 015 skin images with 7 lesion classes. This dataset is characterized by an imbalance ratio (IR) of 58, where IR is defined as the ratio of the sample size of the largest majority class and that of the smallest minority class. Thus the larger the value of IR, the larger the imbalance extent.

Since most large-scale image classification benchmarks contain single-label images with a mostly balanced distribution of labels, many standard AIML methods fail to accommodate the class imbalance problem posed by the long-tailed nature of tasks like disease diagnosis on dermoscopic lesion images.
To develop a benchmark for long-tailed, multi-class medical image classification, we will use the HAM10000 Dataset that was acquired with a variety of dermatoscope types that are categorized into one of seven possible disease categories.

Possible disease categories are:

Melanoma (MEL)
Melanocytic nevus (NV)
Basal cell carcinoma (BCC)
Actinic keratosis / Bowen’s disease (intraepithelial carcinoma) (AKIEC)
Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis) (BKL)
Dermatofibroma (DF)
Vascular lesion (VASC)
