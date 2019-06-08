# Image Learning - Medical Image Classification 

## Applied image classification - Histopathologic Cancer Detection 

The kaggle competition Histopathologic Cancer Detection states the problem of creating an algorithm to identify metastasic cancer in small histopathologic patches, taken from larger digital pathology scans. The task of this data science project is a binary classification problem of histopathologic image patches. Hence, the goal is to identify the presence of metastases from 96x96px digital color images.

***

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)

This notebook is optimized to be executed on Google Colab ([(https://colab.research.google.com).]((https://colab.research.google.com).))


### Acknowledgements

The notebook contains excerpts from [A complete ML pipeline (Fast.ai)](https://www.kaggle.com/qitvision/a-complete-ml-pipeline-fast-ai/comments#470204) and was inspired by fast.ai's online course [(Practical Deep Learning for Coders, v3)](https://course.fast.ai/).

***

## Project Understanding

Metastasic involvement in lymph nodes is an important indicator in (breast) cancer prognosis. Usually the regional lymph node status is assesed by sentinel lymph node procedure. The sentinel lymph node is most likely to contain metastasized cancer cells. For the diagnostic procedure it is exised, histopathologically processed and examined by a pathologist.([1399 H&E-stained sentinel lymph node sections of breast cancer patients: the CAMELYON dataset](https://academic.oup.com/gigascience/article/7/6/giy065/5026175))

The histopathological images are glass slides containing a tissue section of the lymph node stained with hematoxylin and eosin (H&E). This method forms the basis of contemporary cancer diagnosis. Hematoxylin has a deep blue-purple color and stains nucleic acids. Eosin is pink and stains in a typical tissue the cytoplasm and extracellular matrix in different shades of pink. On the basis of nuclei, different cell-type and cancer-type specific patterns can be shown.

As an illustration the next figure shows an example of metastasic region in the lymph node.([Camelyon17](https://camelyon17.grand-challenge.org/Background/))




 



