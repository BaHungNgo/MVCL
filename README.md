# Multi-view-Collaborative-Learning-for-Semi-Supervised-Domain-Adaptation

## pip install -r requirements.txt

## Data preparation (DomainNet)
The data processing follows the protocol of [MME](https://github.com/VisionLearningGroup/SSDA_MME).
To get data, run

`sh download_data.sh`

The images will be stored in the following way.

`./data/multi/real/category_name`,

`./data/multi/sketch/category_name`

The dataset split files are stored as follows,

`./data/txt/multi/labeled_source_images_real.txt`,

`./data/txt/multi/unlabeled_target_images_sketch_3.txt`,

`./data/txt/multi/validation_target_images_sketch_3.txt`.

The office and office home datasets are organized in the following ways,

 `./data/office/amazon/category_name`,
 
 `./data/office_home/Real/category_name`.
 
The dataset split files of office or office_home are stored as follows,

`./data/txt/office/labeled_source_images_amazon.txt`,

`./data/txt/office_home/unlabeled_target_images_Art_3.txt`,
