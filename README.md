# IBD-ICD

This repo contains the validation dataset for severity scoring of ulcerative colitis. 

Images are grouped into folders named as m1, m2, m3 and normal. You can access each folder by entering "validation_set_for_colitis_2024_{name of folder}".

Access through: https://drive.google.com/drive/folders/1K6JzTk7kD6_olAiGRikIQ_914P23HNZ4?usp=drive_link

One gastroenterologist with 13 years of experience performed colonoscopies using an Olympus 160 device (653*560 pixel image output). Reports with the term "mayo" were retrieved and classified into m1, m2, and m3, and normal colonoscopy studies were collected. To create image-level labels, images were labelled by an MD and a GI fellow. A gastroenterologist resolved discrepancies. A senior gastroenterologist with 10 years of experience in IBD management reviewed all image-level labels.

The paper describing the dataset will be published soon. Future uses should mention the source of data by citing the article. 


### Used in: 
- [TiLense-4BlackBox-VLM](https://github.com/Sdamirsa/TiLense-4BlackBox-VLM) to test the validation of a model-agnostic approach for explaining important regions for prediction tasks, when using vision language models. 

