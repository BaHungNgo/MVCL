# MVCL
## pip install -r requirements.txt

## Data preparation (We implement the proposed method on four datasets)
[Office-31](https://www.cc.gatech.edu/~judy/domainadapt/#datasets_code),
[Office-Home](https://www.hemanthdv.org/officeHomeDataset.html),
[VisDa2017](http://ai.bu.edu/visda-2017/),
and [DomainNet](http://ai.bu.edu/M3SDA/).

The data processing follows the protocol of [MME](https://github.com/VisionLearningGroup/SSDA_MME).
 
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

## Citation
If you find this project useful for your research, please kindly cite our paper:


```

