# ID-segmentation

In this project, a U-Net-like network for document segmentation is created and trained.

The midv500 fragment is used as a dataset. This is a dataset containing photographs of documents such as a passport or driver's license.

Two trainings were conducted with different loss functions (BCELoss and BinaryDiceLoss). 

Results with BCELoss:

<img width="830" alt="Снимок экрана 2023-06-05 в 14 29 21" src="https://github.com/vladimir-ciric/ID-segmentation/assets/95381758/66ca4be4-0c61-4b38-95bb-ae14d1da83ab">

Accuracy - 0.707

Results with BinaryDiceLoss:

<img width="830" alt="Снимок экрана 2023-06-05 в 14 31 11" src="https://github.com/vladimir-ciric/ID-segmentation/assets/95381758/89b738ec-2f0a-46c8-bcc8-1c3b402671c6">

Accuracy - 0.697
