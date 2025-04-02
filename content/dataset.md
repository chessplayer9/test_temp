---
title: 'Dataset'
date: 2023-10-24
type: landing

design:
  spacing: '3rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: markdown
    content:
      text: |
        {{< test margin="625px" bg="#ffffff" >}}
        ## Sub-dataset 1

        ## Sub-dataset 2

        ## Sub-dataset 3
        The data from Sub-dataset 3 is sourced from CC3M and RS5M. To expand the diversity included in the dataset, we consider retrieving aerial images with the same semantics or categories from above web datasets. Sub-dataset 3 contains 11,037 images with 137 classes, which are included in the 187 classes in Sub-dataset 1. The file structure of the dataset is as follows:
        ```
        sub-dataset3-Aerial-domain3/
        ├── ALL/ (All 11,037 images with 137 classes.)
        │   ├── train/ (Train set)
        │   │   ├── BareLand/ (Class XXX)
        │   │   │   ├──xxxxx.jpg (Images of class XXX)
        │   │   │   └──......
        │   │   ├── Bridge/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   └──......
        │   ├── test/ (Test set)
        │   │   ├── BareLand/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   ├── Bridge/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   └──......
        ├── ID/ (Including 71 in-distribution (ID) classes, used for Covariate Shift OOD Detection & Generalization.)
        │   ├── train/
        │   │   ├── BareLand/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   ├── Cloud/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   └──......
        │   ├── test/
        │   │   ├── BareLand/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   ├── Cloud/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   └──......
        ├── OOD/ (Including 66 resampling bias OOD classes, used for Covariate Shift OOD Detection & Generalization.)
        │   ├── train/
        │   │   ├── Baseball field/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   ├── Playground/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   └──......
        │   ├── test/
        │   │   ├── Baseball field/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   ├── Playground/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   └──......
        ├── DIL-Aerial/ (Including 50 classes, used for Domain Incremental Learning (DIL))
        │   ├── train/
        │   │   ├── Desert/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   ├── cloud/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   └──......
        │   ├── test/
        │   │   ├── Desert/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   ├── cloud/
        │   │   │   ├──xxxxx.jpg
        │   │   │   └──......
        │   │   └──......
        ├── ID.txt (71 ID classnames.)
        ├── OOD.txt (66 OOD classnames.)
        └── classname.txt (137 all classnames.)
        ```

        ## Sub-dataset 4

        ## Sub-dataset 5
        {{< /test >}}
      design:
        spacing:
          padding: ["0px", "0px", "0px", "0px"]  # 垂直30px/水平0.
        design:
            width: full

---
