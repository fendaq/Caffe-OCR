## 项目说明
根据Github上的[senlinunx/caffe_ocr](https://github.com/senlinuc/caffe_ocr)项目，修改源码[Caffe-rc5](https://github.com/BVLC/caffe/releases/tag/rc5),原项目为windows下的项目，这里尝试修改为linux下的项目。

项目正在进行中...

---

#### TODO:
* ​关于[原项目](https://github.com/senlinuc/caffe_ocr)里的ctcpp_entrypoint.cpp/cu究竟需不需要添加？
* 训练实验

#### DONE:
* 修改data layer 增加对 <b>multi-label</b> 的支持
  自己按照教程修改失败，幸好有伟大的Github，用了[last-one/caffe-multi](https://github.com/last-one/caffe-multilabel).
* add layer:<b> lstm_layer_Junhyuk
* add layer:<b> transpose_layer
* add layer:<b> reverse_layer,reverse_time_layer
* add layer:<b> DenseBlock
* add layer:<b> WarpCTCLossLayer


---
#### Thanks：

* <b>原项目  [senlinuc/caffe_ocr](https://github.com/senlinuc/caffe_ocr)
* <b>multilabel [last-one/caffe-multi](https://github.com/last-one/caffe-multilabel)
