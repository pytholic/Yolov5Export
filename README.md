## Note
Main reason for using [dbsystel](https://github.com/dbsystel/yolov5-coreml-tools) method is that in official conversion method `export.py`, `nms` is not icluded in the model. Rather they implement it separately during `detect.py` script. 

If you create a standalone application with coreml model, then you might have to implement nms manually which can be hard. However in dbsystel repository, it integrates `nms` in the model.
