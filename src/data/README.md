# Data

In this folder you can download the datasets used in the project.
To download the datasets you can use the following command:

```bash
wget "https://storage.googleapis.com/public-datasets-lila/larch-casebearer/Data_Set_Larch_Casebearer.zip"
unzip Data_Set_Larch_Casebearer.zip
mv Data_Set_Larch_Casebearer larches
rm Data_Set_Larch_Casebearer.zip
```

Then, structure the folder as follows:

```python
data
├── README.md           # this file
├── train.json          # the train annotations
├── val.json            # the val annotations
├── test.json           # the test annotations
└── larches
    ├── Bebehojd_20190527
    │   ├── Annotations
    │   │   ├── B01_0004.xml
    │   │   ├── B01_0005.xml
    │   │   └── ...
    │   ├── Images
    │   │   ├── B01_0004.JPG
    │   │   ├── B01_0005.JPG
    │   │   └── ...
    │   ├── Labels
    │   │   ├── B01_0004.txt
    │   │   ├── B01_0005.txt
    │   │   └── ...
    ├── Bebehojd_20190819
    │   ├── Annotations
    │   │   ├── B06_0001.xml
    │   │   ├── B06_0002.xml
    │   │   └── ...
    │   ├── Images
    │   │   ├── B06_0001.JPG
    │   │   ├── B06_0002.JPG
    │   │   └── ...
    │   ├── Labels
    │   │   ├── B06_0001.txt
    │   │   ├── B06_0002.txt
    │   │   └── ...
    └── ...
```