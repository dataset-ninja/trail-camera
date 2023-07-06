Dataset **Trail Camera** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/C/D/Kq/jBilnIvW348wBML6XffPU7ScUYcDCxlXzu63PrJHwAhyw3x9QQwEv22kc3727HJYHS31mkCYibI8FtOWj9akQwndGcOo0Eo7gLvNXA5ihRs5OtCJp9SUhWxBfGID.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Trail Camera', dst_path='~/dtools/datasets/Trail Camera.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/roboflow-100/trail-camera/dataset/2/download)