Dataset **Guns in an Active State Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/6/c/MY/5lc3cNO5nqead9Ms8lOg3lD98JeklWtwchErngJviFeJhn3tTNXpaeBGxoenkcxlb23YIHKgMEjX6AxZotLltIP8gkQ3Z7CW8LKOaGpUqAGenp8AunIYu37grv57.tar)

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