# GraphFPN: Graph Feature Pyramid Network for Object Detection
~~~
Download graph-FPN-main.zip
~~~
For training , run:
~~~
python train.py
~~~
For test with Graph_fpn, run
~~~
python test.py
~~~
If You need COCO API for test, you can download from [here](https://github.com/cocodataset/cocoapi).


## Folder structure

```
${ROOT}
└── checkpoint/
└── COCO/    
│   └── coco/
│   │    ├── .config 
│   │    ├── 2017/
│   │
│   ├── downloads/
│
│
└── data_demo/
|   ├── data/
|   |    ├── coco
|   |    ├── checkpoint
|   ├── data.zip
|
├── results/
├── src/     
|   ├── configs/
|   |    ├── configs.py
|   |
|   ├── detection/
|   |    ├── datasets/
|   |    |      ├── coco.py
|   |    ├── utils/
|   |
|   ├── model/
|   ├── init_path.py
|   ├── demo.py
|   ├── train.py
|   ├── test.py
├── README.md 
└── requirements.txt
```
## References
[1] Graph-FPN: [GraphFPN: Graph Feature Pyramid Network for Object Detection](https://arxiv.org/abs/2108.00580) <br>

In addition, we provide more detection frameworks that can support GraphFPN
~~~
Download graph-mmdet.zip 
~~~
this code uses mmdetecion as the base framework, you can set yourself env based on [mmdetection](https://github.com/open-mmlab/mmdetection) \
this can simply run
~~~
sh train.sh
~~~
get the result of CGL-1 in graphFPN, however, you should add other components from the above codes to run the complete GraphFPN. 


