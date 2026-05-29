# BME Medical Informatics course - Examples

<a href="https://mybinder.org/v2/gh/sgsfak/BME-Medical-Informatics-course/main"><img src="https://mybinder.org/badge_logo.svg"></a>

### Contents

* In the `covid_xml` folder you can find a Python notebook parsing XML (and JSON) COVID-19 data as an example on different data formats
* In the `dicom` folder there is another notebook showing the use of [pydicom](https://github.com/pydicom/pydicom) and [pynetdicom](https://github.com/pydicom/pynetdicom) for managing the [DICOM](https://www.dicomstandard.org/) medical image format and the corresponding communication protocol.

To use these notebooks you can either clone this repo and use the Python local installation on your machine, or press the "Binder" button shown above to run it online in [Binder](https://mybinder.org). You can also open them in [Google Colab](https://colab.research.google.com/):

  -  [covid_xml](https://githubtocolab.com/sgsfak/BME-Medical-Informatics-course/blob/main/covid_xml/covid19.ipynb)
  -  [dicom](https://githubtocolab.com/sgsfak/BME-Medical-Informatics-course/blob/main/dicom/dicom-tests.ipynb)

### Running the code and the notebooks

You can launch the notebooks in [Google Colab](https://colab.research.google.com/) e.g. by visiting this url: https://colab.research.google.com/github/sgsfak/BME-Medical-Informatics-course/blob/main/dicom/dicom-tests.ipynb 

**Alternatively** you can run everything on your local machine as follows:
We are using [uv](https://docs.astral.sh/uv/) as the overall Python package manager.You can download or clone this repository and then
[install](https://docs.astral.sh/uv/getting-started/installation/) `uv`. After that you can create a local `venv` (virtual environment) and install all the pacakges needed by issuing:

```
uv sync
```

You can then launch a local notebook server through the command:

```
uv run jupyter lab
```



### Authors

* Stelios Sfakianakis
* Vaggelis Sakkalis

