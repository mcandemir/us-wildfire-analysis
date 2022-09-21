# U.S. Wildfire Analysis
This project contains:
<ul>
    <li>The 1.88M U.S. Wildfires Data</li>
    <li>Analysis Report as PDF</li>
    <li>Analysis Report as Document</li>
    <li>Analysis Notebook as HTML</li>
    <li>Analysis Notebook</li>
    <li>Requirements.txt</li>
</ul>

Link to the data is [here](https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires?resource=download)

## Installing Dependencies
You can also use a jupyter notebook docker image instead of creating an environment in your computer.
### 1) Using Jupyter Notebook docker image

```shell
$ docker run -it --rm -p 8889:8888 -v "${PWD}":/home/jovyan/work jupyter/datascience-notebook:python-3.10.6
```

### 2) Using pip
If you are using <b>conda</b>, create an environment. If not, you can skip this step.
```shell
$ conda create -n wildfire python=3.10.4
$ conda activate wildfire
```

Install dependencies.
```shell
$ pip install -r requirements.txt
```

