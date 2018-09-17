# [Source code now lives in the PyTorch repository](https://github.com/pytorch/pytorch/).

## Caffe2

Caffe2 is a lightweight, modular, and scalable deep learning framework. Building on the original [Caffe](http://caffe.berkeleyvision.org), Caffe2 is designed with expression, speed, and modularity in mind.

Learn more about Caffe2 on the [caffe2.ai website](http://caffe2.ai/)

- - -
.gitmodules
- change
```
[submodule "third_party/aten"]
	path = third_party/aten
	url = https://github.com/zdevito/aten
```
to
```
[submodule "third_party/aten"]
	path = third_party/aten
	url = https://github.com/zdevito/ATen.git
```

- change
```
[submodule "third_party/eigen"]
	path = third_party/eigen
	url = https://github.com/RLovelett/eigen.git
```
to 
```
[submodule "third_party/eigen"]
	path = third_party/eigen
	url = https://github.com/eigenteam/eigen-git-mirror.git
```
