Dataset **Guns in an Active State Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMjg1NF9HdW5zIGluIGFuIEFjdGl2ZSBTdGF0ZSBEZXRlY3Rpb24vZ3Vucy1pbi1hbi1hY3RpdmUtc3RhdGUtZGV0ZWN0aW9uLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIlp4UW9jQlZVNWpCOUdRQUZvTjh1RUVvYWoxcHJsd1ovM0UwWExpRlFpNzQ9In0=?response-content-disposition=attachment%3B%20filename%3D%22guns-in-an-active-state-detection-DatasetNinja.tar%22)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Guns in an Active State Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/ugorjiir/gun-detection/download?datasetVersionNumber=1).