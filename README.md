## Note
Main reason for using [dbsystel](https://github.com/dbsystel/yolov5-coreml-tools) method isthat in official conversion method, `nms` is not icluded in the model. Rather they implement it separately during `detect.py` script. However in dbsystel repository, it included `nms` in the model.
