# 按照文档添加库
-

```python
!pip install tflite-model-maker
```

    Collecting tflite-model-maker
      Using cached tflite_model_maker-0.4.0-py3-none-any.whl (642 kB)
    Collecting librosa==0.8.1
      Using cached librosa-0.8.1-py3-none-any.whl (203 kB)
    Collecting tensorflow-datasets>=2.1.0
      Using cached tensorflow_datasets-4.5.2-py3-none-any.whl (4.2 MB)
    Requirement already satisfied: PyYAML>=5.1 in d:\download\anaconda\anaconda\lib\site-packages (from tflite-model-maker) (6.0)
    Collecting sentencepiece>=0.1.91
      Using cached sentencepiece-0.1.96-cp39-cp39-win_amd64.whl (1.1 MB)
    Collecting tensorflow-model-optimization>=0.5
      Using cached tensorflow_model_optimization-0.7.2-py2.py3-none-any.whl (237 kB)
    Collecting flatbuffers==1.12
      Using cached flatbuffers-1.12-py2.py3-none-any.whl (15 kB)
    Requirement already satisfied: numpy>=1.17.3 in d:\download\anaconda\anaconda\lib\site-packages (from tflite-model-maker) (1.20.3)
    Collecting tflite-support>=0.4.0
      Using cached tflite_support-0.4.0-cp39-cp39-win_amd64.whl (439 kB)
    Requirement already satisfied: matplotlib<3.5.0,>=3.0.3 in d:\download\anaconda\anaconda\lib\site-packages (from tflite-model-maker) (3.4.3)
    Requirement already satisfied: pillow>=7.0.0 in d:\download\anaconda\anaconda\lib\site-packages (from tflite-model-maker) (9.0.1)
    Requirement already satisfied: urllib3!=1.25.0,!=1.25.1,<1.26,>=1.21.1 in d:\download\anaconda\anaconda\lib\site-packages (from tflite-model-maker) (1.25.11)
    Requirement already satisfied: Cython>=0.29.13 in d:\download\anaconda\anaconda\lib\site-packages (from tflite-model-maker) (0.29.24)
    Collecting fire>=0.3.1
      Using cached fire-0.4.0-py2.py3-none-any.whl
    Collecting tflite-model-maker
      Using cached tflite_model_maker-0.3.4-py3-none-any.whl (616 kB)
    Requirement already satisfied: six>=1.12.0 in d:\download\anaconda\anaconda\lib\site-packages (from tflite-model-maker) (1.16.0)
    Collecting tf-models-official==2.3.0
      Using cached tf_models_official-2.3.0-py2.py3-none-any.whl (840 kB)
    Collecting absl-py>=0.10.0
      Using cached absl_py-1.0.0-py3-none-any.whl (126 kB)
    Collecting numba==0.53
      Using cached numba-0.53.0-cp39-cp39-win_amd64.whl (2.3 MB)
    Collecting neural-structured-learning>=1.3.1
      Using cached neural_structured_learning-1.3.1-py2.py3-none-any.whl (120 kB)
    Collecting tensorflow>=2.6.0
      Using cached tensorflow-2.9.1-cp39-cp39-win_amd64.whl (444.0 MB)
    Collecting tensorflow-addons>=0.11.2
      Using cached tensorflow_addons-0.17.0-cp39-cp39-win_amd64.whl (758 kB)
    Collecting tensorflow-hub<0.13,>=0.7.0
      Using cached tensorflow_hub-0.12.0-py2.py3-none-any.whl (108 kB)
    Collecting tensorflowjs>=2.4.0
      Using cached tensorflowjs-3.18.0-py3-none-any.whl (77 kB)
    Requirement already satisfied: lxml>=4.6.1 in d:\download\anaconda\anaconda\lib\site-packages (from tflite-model-maker) (4.6.3)
    Requirement already satisfied: packaging>=20.0 in d:\download\anaconda\anaconda\lib\site-packages (from librosa==0.8.1->tflite-model-maker) (21.3)
    Collecting audioread>=2.0.0
      Using cached audioread-2.1.9-py3-none-any.whl
    Collecting pooch>=1.0
      Using cached pooch-1.6.0-py3-none-any.whl (56 kB)
    Collecting soundfile>=0.10.2
      Using cached SoundFile-0.10.3.post1-py2.py3.cp26.cp27.cp32.cp33.cp34.cp35.cp36.pp27.pp32.pp33-none-win_amd64.whl (689 kB)
    Requirement already satisfied: joblib>=0.14 in d:\download\anaconda\anaconda\lib\site-packages (from librosa==0.8.1->tflite-model-maker) (1.1.0)
    Requirement already satisfied: scikit-learn!=0.19.0,>=0.14.0 in d:\download\anaconda\anaconda\lib\site-packages (from librosa==0.8.1->tflite-model-maker) (0.24.2)
    Requirement already satisfied: scipy>=1.0.0 in d:\download\anaconda\anaconda\lib\site-packages (from librosa==0.8.1->tflite-model-maker) (1.7.1)
    Collecting resampy>=0.2.2
      Using cached resampy-0.2.2-py3-none-any.whl
    Requirement already satisfied: decorator>=3.0.0 in d:\download\anaconda\anaconda\lib\site-packages (from librosa==0.8.1->tflite-model-maker) (5.1.1)
    Collecting llvmlite<0.37,>=0.36.0rc1
      Using cached llvmlite-0.36.0-cp39-cp39-win_amd64.whl (16.0 MB)
    Requirement already satisfied: setuptools in d:\download\anaconda\anaconda\lib\site-packages (from numba==0.53->tflite-model-maker) (61.2.0)
    Collecting dataclasses
      Using cached dataclasses-0.6-py3-none-any.whl (14 kB)
    Collecting tf-slim>=1.1.0
      Using cached tf_slim-1.1.0-py2.py3-none-any.whl (352 kB)
    Requirement already satisfied: pandas>=0.22.0 in d:\download\anaconda\anaconda\lib\site-packages (from tf-models-official==2.3.0->tflite-model-maker) (1.3.4)
    Collecting kaggle>=1.3.9
      Using cached kaggle-1.5.12-py3-none-any.whl
    Requirement already satisfied: psutil>=5.4.3 in d:\download\anaconda\anaconda\lib\site-packages (from tf-models-official==2.3.0->tflite-model-maker) (5.8.0)
    Collecting gin-config
      Using cached gin_config-0.5.0-py3-none-any.whl (61 kB)
    Collecting py-cpuinfo>=3.3.0
      Using cached py_cpuinfo-8.0.0-py3-none-any.whl
    Collecting opencv-python-headless
      Using cached opencv_python_headless-4.5.5.64-cp36-abi3-win_amd64.whl (35.3 MB)
    Collecting google-api-python-client>=1.6.7
      Using cached google_api_python_client-2.49.0-py2.py3-none-any.whl (8.5 MB)
    Collecting google-cloud-bigquery>=0.31.0
      Using cached google_cloud_bigquery-3.1.0-py2.py3-none-any.whl (211 kB)
    Collecting termcolor
      Using cached termcolor-1.1.0-py3-none-any.whl
    Requirement already satisfied: google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0dev,>=1.31.5 in d:\download\anaconda\anaconda\lib\site-packages (from google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (2.8.0)
    Collecting uritemplate<5,>=3.0.1
      Using cached uritemplate-4.1.1-py2.py3-none-any.whl (10 kB)
    Requirement already satisfied: google-auth<3.0.0dev,>=1.16.0 in d:\download\anaconda\anaconda\lib\site-packages (from google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (2.6.6)
    Collecting google-auth-httplib2>=0.1.0
      Using cached google_auth_httplib2-0.1.0-py2.py3-none-any.whl (9.3 kB)
    Collecting httplib2<1dev,>=0.15.0
      Using cached httplib2-0.20.4-py3-none-any.whl (96 kB)
    Requirement already satisfied: protobuf>=3.12.0 in d:\download\anaconda\anaconda\lib\site-packages (from google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0dev,>=1.31.5->google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (3.19.4)
    Requirement already satisfied: googleapis-common-protos<2.0dev,>=1.52.0 in d:\download\anaconda\anaconda\lib\site-packages (from google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0dev,>=1.31.5->google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (1.56.1)
    Requirement already satisfied: requests<3.0.0dev,>=2.18.0 in d:\download\anaconda\anaconda\lib\site-packages (from google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0dev,>=1.31.5->google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (2.26.0)
    Requirement already satisfied: pyasn1-modules>=0.2.1 in d:\download\anaconda\anaconda\lib\site-packages (from google-auth<3.0.0dev,>=1.16.0->google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (0.2.8)
    Requirement already satisfied: rsa<5,>=3.1.4 in d:\download\anaconda\anaconda\lib\site-packages (from google-auth<3.0.0dev,>=1.16.0->google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (4.8)
    Requirement already satisfied: cachetools<6.0,>=2.0.0 in d:\download\anaconda\anaconda\lib\site-packages (from google-auth<3.0.0dev,>=1.16.0->google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (5.1.0)
    Requirement already satisfied: grpcio<2.0dev,>=1.38.1 in d:\download\anaconda\anaconda\lib\site-packages (from google-cloud-bigquery>=0.31.0->tf-models-official==2.3.0->tflite-model-maker) (1.46.3)
    Collecting google-cloud-core<3.0.0dev,>=1.4.1
      Using cached google_cloud_core-2.3.0-py2.py3-none-any.whl (29 kB)
    Requirement already satisfied: python-dateutil<3.0dev,>=2.7.2 in d:\download\anaconda\anaconda\lib\site-packages (from google-cloud-bigquery>=0.31.0->tf-models-official==2.3.0->tflite-model-maker) (2.8.2)
    Collecting google-resumable-media<3.0dev,>=0.6.0
      Using cached google_resumable_media-2.3.3-py2.py3-none-any.whl (76 kB)
    Requirement already satisfied: proto-plus>=1.15.0 in d:\download\anaconda\anaconda\lib\site-packages (from google-cloud-bigquery>=0.31.0->tf-models-official==2.3.0->tflite-model-maker) (1.20.4)
    Collecting google-cloud-bigquery-storage<3.0.0dev,>=2.0.0
      Using cached google_cloud_bigquery_storage-2.13.1-py2.py3-none-any.whl (180 kB)
    Collecting pyarrow<9.0dev,>=3.0.0
      Using cached pyarrow-8.0.0-cp39-cp39-win_amd64.whl (17.9 MB)
    Requirement already satisfied: grpcio-status<2.0dev,>=1.33.2 in d:\download\anaconda\anaconda\lib\site-packages (from google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0dev,>=1.31.5->google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (1.46.3)
    Collecting google-crc32c<2.0dev,>=1.0
      Using cached google_crc32c-1.3.0-cp39-cp39-win_amd64.whl (27 kB)
    Requirement already satisfied: pyparsing!=3.0.0,!=3.0.1,!=3.0.2,!=3.0.3,<4,>=2.4.2 in d:\download\anaconda\anaconda\lib\site-packages (from httplib2<1dev,>=0.15.0->google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (3.0.4)
    Requirement already satisfied: certifi in d:\download\anaconda\anaconda\lib\site-packages (from kaggle>=1.3.9->tf-models-official==2.3.0->tflite-model-maker) (2022.5.18.1)
    Requirement already satisfied: python-slugify in d:\download\anaconda\anaconda\lib\site-packages (from kaggle>=1.3.9->tf-models-official==2.3.0->tflite-model-maker) (5.0.2)
    Requirement already satisfied: tqdm in d:\download\anaconda\anaconda\lib\site-packages (from kaggle>=1.3.9->tf-models-official==2.3.0->tflite-model-maker) (4.64.0)
    Requirement already satisfied: kiwisolver>=1.0.1 in d:\download\anaconda\anaconda\lib\site-packages (from matplotlib<3.5.0,>=3.0.3->tflite-model-maker) (1.3.1)
    Requirement already satisfied: cycler>=0.10 in d:\download\anaconda\anaconda\lib\site-packages (from matplotlib<3.5.0,>=3.0.3->tflite-model-maker) (0.10.0)
    Requirement already satisfied: attrs in d:\download\anaconda\anaconda\lib\site-packages (from neural-structured-learning>=1.3.1->tflite-model-maker) (21.4.0)
    Requirement already satisfied: pytz>=2017.3 in d:\download\anaconda\anaconda\lib\site-packages (from pandas>=0.22.0->tf-models-official==2.3.0->tflite-model-maker) (2021.3)
    Requirement already satisfied: appdirs>=1.3.0 in d:\download\anaconda\anaconda\lib\site-packages (from pooch>=1.0->librosa==0.8.1->tflite-model-maker) (1.4.4)
    Requirement already satisfied: pyasn1<0.5.0,>=0.4.6 in d:\download\anaconda\anaconda\lib\site-packages (from pyasn1-modules>=0.2.1->google-auth<3.0.0dev,>=1.16.0->google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (0.4.8)
    Requirement already satisfied: idna<4,>=2.5 in d:\download\anaconda\anaconda\lib\site-packages (from requests<3.0.0dev,>=2.18.0->google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0dev,>=1.31.5->google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (3.3)
    Requirement already satisfied: charset-normalizer~=2.0.0 in d:\download\anaconda\anaconda\lib\site-packages (from requests<3.0.0dev,>=2.18.0->google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0dev,>=1.31.5->google-api-python-client>=1.6.7->tf-models-official==2.3.0->tflite-model-maker) (2.0.4)
    Requirement already satisfied: threadpoolctl>=2.0.0 in d:\download\anaconda\anaconda\lib\site-packages (from scikit-learn!=0.19.0,>=0.14.0->librosa==0.8.1->tflite-model-maker) (2.2.0)
    Requirement already satisfied: cffi>=1.0 in d:\download\anaconda\anaconda\lib\site-packages (from soundfile>=0.10.2->librosa==0.8.1->tflite-model-maker) (1.15.0)
    Requirement already satisfied: pycparser in d:\download\anaconda\anaconda\lib\site-packages (from cffi>=1.0->soundfile>=0.10.2->librosa==0.8.1->tflite-model-maker) (2.21)
    Collecting keras-preprocessing>=1.1.1
      Using cached Keras_Preprocessing-1.1.2-py2.py3-none-any.whl (42 kB)
    Collecting google-pasta>=0.1.1
      Using cached google_pasta-0.2.0-py3-none-any.whl (57 kB)
    Requirement already satisfied: h5py>=2.9.0 in d:\download\anaconda\anaconda\lib\site-packages (from tensorflow>=2.6.0->tflite-model-maker) (3.2.1)
    Requirement already satisfied: typing-extensions>=3.6.6 in d:\download\anaconda\anaconda\lib\site-packages (from tensorflow>=2.6.0->tflite-model-maker) (4.1.1)
    Collecting tensorflow-estimator<2.10.0,>=2.9.0rc0
      Using cached tensorflow_estimator-2.9.0-py2.py3-none-any.whl (438 kB)
    Collecting gast<=0.4.0,>=0.2.1
      Using cached gast-0.4.0-py3-none-any.whl (9.8 kB)
    Collecting tensorboard<2.10,>=2.9
      Using cached tensorboard-2.9.0-py3-none-any.whl (5.8 MB)
    Collecting astunparse>=1.6.0
      Using cached astunparse-1.6.3-py2.py3-none-any.whl (12 kB)
    Collecting libclang>=13.0.0
      Using cached libclang-14.0.1-py2.py3-none-win_amd64.whl (14.2 MB)
    Collecting tensorflow-io-gcs-filesystem>=0.23.1
      Using cached tensorflow_io_gcs_filesystem-0.26.0-cp39-cp39-win_amd64.whl (1.5 MB)
    Collecting keras<2.10.0,>=2.9.0rc0
      Using cached keras-2.9.0-py2.py3-none-any.whl (1.6 MB)
    Requirement already satisfied: wrapt>=1.11.0 in d:\download\anaconda\anaconda\lib\site-packages (from tensorflow>=2.6.0->tflite-model-maker) (1.12.1)
    Collecting opt-einsum>=2.3.2
      Using cached opt_einsum-3.3.0-py3-none-any.whl (65 kB)
    Requirement already satisfied: wheel<1.0,>=0.23.0 in d:\download\anaconda\anaconda\lib\site-packages (from astunparse>=1.6.0->tensorflow>=2.6.0->tflite-model-maker) (0.37.1)
    Requirement already satisfied: markdown>=2.6.8 in d:\download\anaconda\anaconda\lib\site-packages (from tensorboard<2.10,>=2.9->tensorflow>=2.6.0->tflite-model-maker) (3.3.7)
    Collecting google-auth-oauthlib<0.5,>=0.4.1
      Using cached google_auth_oauthlib-0.4.6-py2.py3-none-any.whl (18 kB)
    Requirement already satisfied: tensorboard-data-server<0.7.0,>=0.6.0 in d:\download\anaconda\anaconda\lib\site-packages (from tensorboard<2.10,>=2.9->tensorflow>=2.6.0->tflite-model-maker) (0.6.1)
    Requirement already satisfied: werkzeug>=1.0.1 in d:\download\anaconda\anaconda\lib\site-packages (from tensorboard<2.10,>=2.9->tensorflow>=2.6.0->tflite-model-maker) (2.0.2)
    Requirement already satisfied: tensorboard-plugin-wit>=1.6.0 in d:\download\anaconda\anaconda\lib\site-packages (from tensorboard<2.10,>=2.9->tensorflow>=2.6.0->tflite-model-maker) (1.8.1)
    Requirement already satisfied: requests-oauthlib>=0.7.0 in d:\download\anaconda\anaconda\lib\site-packages (from google-auth-oauthlib<0.5,>=0.4.1->tensorboard<2.10,>=2.9->tensorflow>=2.6.0->tflite-model-maker) (1.3.1)
    Requirement already satisfied: importlib-metadata>=4.4 in d:\download\anaconda\anaconda\lib\site-packages (from markdown>=2.6.8->tensorboard<2.10,>=2.9->tensorflow>=2.6.0->tflite-model-maker) (4.11.3)
    Requirement already satisfied: zipp>=0.5 in d:\download\anaconda\anaconda\lib\site-packages (from importlib-metadata>=4.4->markdown>=2.6.8->tensorboard<2.10,>=2.9->tensorflow>=2.6.0->tflite-model-maker) (3.8.0)
    Requirement already satisfied: oauthlib>=3.0.0 in d:\download\anaconda\anaconda\lib\site-packages (from requests-oauthlib>=0.7.0->google-auth-oauthlib<0.5,>=0.4.1->tensorboard<2.10,>=2.9->tensorflow>=2.6.0->tflite-model-maker) (3.2.0)
    Collecting typeguard>=2.7
      Using cached typeguard-2.13.3-py3-none-any.whl (17 kB)
    Collecting tensorflow-metadata
      Using cached tensorflow_metadata-1.8.0-py3-none-any.whl (50 kB)
    Collecting dill
      Using cached dill-0.3.5.1-py2.py3-none-any.whl (95 kB)
    Collecting promise
      Using cached promise-2.3-py3-none-any.whl
    Collecting dm-tree~=0.1.1
      Using cached dm_tree-0.1.7-cp39-cp39-win_amd64.whl (90 kB)
    Collecting packaging>=20.0
      Using cached packaging-20.9-py2.py3-none-any.whl (40 kB)
    Collecting sounddevice>=0.4.4
      Using cached sounddevice-0.4.4-py3-none-win_amd64.whl (195 kB)
    Collecting pybind11>=2.6.0
      Using cached pybind11-2.9.2-py2.py3-none-any.whl (213 kB)
    Requirement already satisfied: text-unidecode>=1.3 in d:\download\anaconda\anaconda\lib\site-packages (from python-slugify->kaggle>=1.3.9->tf-models-official==2.3.0->tflite-model-maker) (1.3)
    Requirement already satisfied: colorama in d:\download\anaconda\anaconda\lib\site-packages (from tqdm->kaggle>=1.3.9->tf-models-official==2.3.0->tflite-model-maker) (0.4.4)
    Installing collected packages: llvmlite, httplib2, google-crc32c, google-auth-oauthlib, absl-py, uritemplate, typeguard, termcolor, tensorflow-metadata, tensorflow-io-gcs-filesystem, tensorflow-estimator, tensorboard, pyarrow, promise, packaging, opt-einsum, numba, libclang, keras-preprocessing, keras, google-resumable-media, google-pasta, google-cloud-core, google-cloud-bigquery-storage, google-auth-httplib2, gast, flatbuffers, dm-tree, dill, astunparse, tf-slim, tensorflow-model-optimization, tensorflow-hub, tensorflow-datasets, tensorflow-addons, tensorflow, soundfile, sounddevice, sentencepiece, resampy, pybind11, py-cpuinfo, pooch, opencv-python-headless, kaggle, google-cloud-bigquery, google-api-python-client, gin-config, dataclasses, audioread, tflite-support, tf-models-official, tensorflowjs, neural-structured-learning, librosa, fire, tflite-model-maker
      Attempting uninstall: packaging
        Found existing installation: packaging 21.3
        Uninstalling packaging-21.3:
          Successfully uninstalled packaging-21.3
    Successfully installed absl-py-1.0.0 astunparse-1.6.3 audioread-2.1.9 dataclasses-0.6 dill-0.3.5.1 dm-tree-0.1.7 fire-0.4.0 flatbuffers-1.12 gast-0.4.0 gin-config-0.5.0 google-api-python-client-2.49.0 google-auth-httplib2-0.1.0 google-auth-oauthlib-0.4.6 google-cloud-bigquery-3.1.0 google-cloud-bigquery-storage-2.13.1 google-cloud-core-2.3.0 google-crc32c-1.3.0 google-pasta-0.2.0 google-resumable-media-2.3.3 httplib2-0.20.4 kaggle-1.5.12 keras-2.9.0 keras-preprocessing-1.1.2 libclang-14.0.1 librosa-0.8.1 llvmlite-0.36.0 neural-structured-learning-1.3.1 numba-0.53.0 opencv-python-headless-4.5.5.64 opt-einsum-3.3.0 packaging-20.9 pooch-1.6.0 promise-2.3 py-cpuinfo-8.0.0 pyarrow-8.0.0 pybind11-2.9.2 resampy-0.2.2 sentencepiece-0.1.96 sounddevice-0.4.4 soundfile-0.10.3.post1 tensorboard-2.9.0 tensorflow-2.9.1 tensorflow-addons-0.17.0 tensorflow-datasets-4.5.2 tensorflow-estimator-2.9.0 tensorflow-hub-0.12.0 tensorflow-io-gcs-filesystem-0.26.0 tensorflow-metadata-1.8.0 tensorflow-model-optimization-0.7.2 tensorflowjs-3.18.0 termcolor-1.1.0 tf-models-official-2.3.0 tf-slim-1.1.0 tflite-model-maker-0.3.4 tflite-support-0.4.0 typeguard-2.13.3 uritemplate-4.1.1
    

# 安装的时候遇到ERROR: Cannot uninstall 'llvmlite'.的问题。首先卸载llvmlite包，这里利用Anaconda Navigator中Environments组件管理和卸载相关的Package。
-

```python
!pip install conda-repo-cli==1.0.4
```

    Requirement already satisfied: conda-repo-cli==1.0.4 in d:\download\anaconda\anaconda\lib\site-packages (1.0.4)
    Requirement already satisfied: PyYAML>=3.12 in d:\download\anaconda\anaconda\lib\site-packages (from conda-repo-cli==1.0.4) (6.0)
    Requirement already satisfied: pytz in d:\download\anaconda\anaconda\lib\site-packages (from conda-repo-cli==1.0.4) (2021.3)
    Requirement already satisfied: clyent>=1.2.0 in d:\download\anaconda\anaconda\lib\site-packages (from conda-repo-cli==1.0.4) (1.2.2)
    Requirement already satisfied: six in d:\download\anaconda\anaconda\lib\site-packages (from conda-repo-cli==1.0.4) (1.16.0)
    Requirement already satisfied: nbformat>=4.4.0 in d:\download\anaconda\anaconda\lib\site-packages (from conda-repo-cli==1.0.4) (5.3.0)
    Requirement already satisfied: python-dateutil>=2.6.1 in d:\download\anaconda\anaconda\lib\site-packages (from conda-repo-cli==1.0.4) (2.8.2)
    Requirement already satisfied: setuptools in d:\download\anaconda\anaconda\lib\site-packages (from conda-repo-cli==1.0.4) (61.2.0)
    Requirement already satisfied: requests>=2.9.1 in d:\download\anaconda\anaconda\lib\site-packages (from conda-repo-cli==1.0.4) (2.26.0)
    Requirement already satisfied: pathlib in d:\download\anaconda\anaconda\lib\site-packages (from conda-repo-cli==1.0.4) (1.0.1)
    Requirement already satisfied: traitlets>=4.1 in d:\download\anaconda\anaconda\lib\site-packages (from nbformat>=4.4.0->conda-repo-cli==1.0.4) (5.1.1)
    Requirement already satisfied: fastjsonschema in d:\download\anaconda\anaconda\lib\site-packages (from nbformat>=4.4.0->conda-repo-cli==1.0.4) (2.15.1)
    Requirement already satisfied: jsonschema>=2.6 in d:\download\anaconda\anaconda\lib\site-packages (from nbformat>=4.4.0->conda-repo-cli==1.0.4) (4.4.0)
    Requirement already satisfied: jupyter-core in d:\download\anaconda\anaconda\lib\site-packages (from nbformat>=4.4.0->conda-repo-cli==1.0.4) (4.10.0)
    Requirement already satisfied: attrs>=17.4.0 in d:\download\anaconda\anaconda\lib\site-packages (from jsonschema>=2.6->nbformat>=4.4.0->conda-repo-cli==1.0.4) (21.4.0)
    Requirement already satisfied: pyrsistent!=0.17.0,!=0.17.1,!=0.17.2,>=0.14.0 in d:\download\anaconda\anaconda\lib\site-packages (from jsonschema>=2.6->nbformat>=4.4.0->conda-repo-cli==1.0.4) (0.18.0)
    Requirement already satisfied: idna<4,>=2.5 in d:\download\anaconda\anaconda\lib\site-packages (from requests>=2.9.1->conda-repo-cli==1.0.4) (3.3)
    Requirement already satisfied: urllib3<1.27,>=1.21.1 in d:\download\anaconda\anaconda\lib\site-packages (from requests>=2.9.1->conda-repo-cli==1.0.4) (1.25.11)
    Requirement already satisfied: charset-normalizer~=2.0.0 in d:\download\anaconda\anaconda\lib\site-packages (from requests>=2.9.1->conda-repo-cli==1.0.4) (2.0.4)
    Requirement already satisfied: certifi>=2017.4.17 in d:\download\anaconda\anaconda\lib\site-packages (from requests>=2.9.1->conda-repo-cli==1.0.4) (2022.5.18.1)
    Requirement already satisfied: pywin32>=1.0 in d:\download\anaconda\anaconda\lib\site-packages (from jupyter-core->nbformat>=4.4.0->conda-repo-cli==1.0.4) (302)
    


```python
!pip install anaconda-project==0.10.1
```

    Requirement already satisfied: anaconda-project==0.10.1 in d:\download\anaconda\anaconda\lib\site-packages (0.10.1)
    Requirement already satisfied: tornado>=4.2 in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-project==0.10.1) (6.1)
    Requirement already satisfied: conda-pack in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-project==0.10.1) (0.6.0)
    Requirement already satisfied: ruamel-yaml in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-project==0.10.1) (0.17.21)
    Requirement already satisfied: jinja2 in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-project==0.10.1) (2.11.3)
    Requirement already satisfied: requests in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-project==0.10.1) (2.26.0)
    Requirement already satisfied: anaconda-client in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-project==0.10.1) (1.9.0)
    Requirement already satisfied: PyYAML>=3.12 in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-client->anaconda-project==0.10.1) (6.0)
    Requirement already satisfied: python-dateutil>=2.6.1 in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-client->anaconda-project==0.10.1) (2.8.2)
    Requirement already satisfied: nbformat>=4.4.0 in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-client->anaconda-project==0.10.1) (5.3.0)
    Requirement already satisfied: six in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-client->anaconda-project==0.10.1) (1.16.0)
    Requirement already satisfied: pytz in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-client->anaconda-project==0.10.1) (2021.3)
    Requirement already satisfied: setuptools in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-client->anaconda-project==0.10.1) (61.2.0)
    Requirement already satisfied: clyent>=1.2.0 in d:\download\anaconda\anaconda\lib\site-packages (from anaconda-client->anaconda-project==0.10.1) (1.2.2)
    Requirement already satisfied: jupyter-core in d:\download\anaconda\anaconda\lib\site-packages (from nbformat>=4.4.0->anaconda-client->anaconda-project==0.10.1) (4.10.0)
    Requirement already satisfied: fastjsonschema in d:\download\anaconda\anaconda\lib\site-packages (from nbformat>=4.4.0->anaconda-client->anaconda-project==0.10.1) (2.15.1)
    Requirement already satisfied: jsonschema>=2.6 in d:\download\anaconda\anaconda\lib\site-packages (from nbformat>=4.4.0->anaconda-client->anaconda-project==0.10.1) (4.4.0)
    Requirement already satisfied: traitlets>=4.1 in d:\download\anaconda\anaconda\lib\site-packages (from nbformat>=4.4.0->anaconda-client->anaconda-project==0.10.1) (5.1.1)
    Requirement already satisfied: attrs>=17.4.0 in d:\download\anaconda\anaconda\lib\site-packages (from jsonschema>=2.6->nbformat>=4.4.0->anaconda-client->anaconda-project==0.10.1) (21.4.0)
    Requirement already satisfied: pyrsistent!=0.17.0,!=0.17.1,!=0.17.2,>=0.14.0 in d:\download\anaconda\anaconda\lib\site-packages (from jsonschema>=2.6->nbformat>=4.4.0->anaconda-client->anaconda-project==0.10.1) (0.18.0)
    Requirement already satisfied: idna<4,>=2.5 in d:\download\anaconda\anaconda\lib\site-packages (from requests->anaconda-project==0.10.1) (3.3)
    Requirement already satisfied: urllib3<1.27,>=1.21.1 in d:\download\anaconda\anaconda\lib\site-packages (from requests->anaconda-project==0.10.1) (1.25.11)
    Requirement already satisfied: charset-normalizer~=2.0.0 in d:\download\anaconda\anaconda\lib\site-packages (from requests->anaconda-project==0.10.1) (2.0.4)
    Requirement already satisfied: certifi>=2017.4.17 in d:\download\anaconda\anaconda\lib\site-packages (from requests->anaconda-project==0.10.1) (2022.5.18.1)
    Requirement already satisfied: MarkupSafe>=0.23 in d:\download\anaconda\anaconda\lib\site-packages (from jinja2->anaconda-project==0.10.1) (1.1.1)
    Requirement already satisfied: pywin32>=1.0 in d:\download\anaconda\anaconda\lib\site-packages (from jupyter-core->nbformat>=4.4.0->anaconda-client->anaconda-project==0.10.1) (302)
    Requirement already satisfied: ruamel.yaml.clib>=0.2.6 in d:\download\anaconda\anaconda\lib\site-packages (from ruamel-yaml->anaconda-project==0.10.1) (0.2.6)
    

#开始运行相关库和代码


```python
import os

import numpy as np

import tensorflow as tf
assert tf.__version__.startswith('2')

from tflite_model_maker import model_spec
from tflite_model_maker import image_classifier
from tflite_model_maker.config import ExportFormat
from tflite_model_maker.config import QuantizationConfig
from tflite_model_maker.image_classifier import DataLoader

import matplotlib.pyplot as plt
```

#进行数据训练


```python
image_path = tf.keras.utils.get_file(
      'flower_photos.tgz',
      'https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz',
      extract=True)
image_path = os.path.join(os.path.dirname(image_path), 'flower_photos')
```

这里从storage.googleapis.com中下载了本实验所需要的数据集。image_path可以定制，默认是在用户目录的.keras\datasets中。

运行
第一步：加载数据集，并将数据集分为训练数据和测试数据


```python
data = DataLoader.from_folder(image_path)
train_data, test_data = data.split(0.9)
```

    INFO:tensorflow:Load image with size: 3670, num_label: 5, labels: daisy, dandelion, roses, sunflowers, tulips.
    

# 第二步：训练Tensorflow模型
-

```python
inception_v3_spec = image_classifier.ModelSpec(uri='https://storage.googleapis.com/tfhub-modules/tensorflow/efficientnet/lite0/feature-vector/2.tar.gz')
inception_v3_spec.input_image_shape = [240, 240]
model = image_classifier.create(train_data, model_spec=inception_v3_spec)
```

    INFO:tensorflow:Retraining the models...
    Model: "sequential"
    _________________________________________________________________
     Layer (type)                Output Shape              Param #   
    =================================================================
     hub_keras_layer_v1v2 (HubKe  (None, 1280)             3413024   
     rasLayerV1V2)                                                   
                                                                     
     dropout (Dropout)           (None, 1280)              0         
                                                                     
     dense (Dense)               (None, 5)                 6405      
                                                                     
    =================================================================
    Total params: 3,419,429
    Trainable params: 6,405
    Non-trainable params: 3,413,024
    _________________________________________________________________
    None
    Epoch 1/5
    

    D:\Download\Anaconda\ANACONDA\lib\site-packages\keras\optimizers\optimizer_v2\gradient_descent.py:108: UserWarning: The `lr` argument is deprecated, use `learning_rate` instead.
      super(SGD, self).__init__(name, **kwargs)
    

    103/103 [==============================] - 74s 698ms/step - loss: 0.8775 - accuracy: 0.7670
    Epoch 2/5
    103/103 [==============================] - 72s 697ms/step - loss: 0.6588 - accuracy: 0.8975
    Epoch 3/5
    103/103 [==============================] - 70s 681ms/step - loss: 0.6256 - accuracy: 0.9111
    Epoch 4/5
    103/103 [==============================] - 72s 699ms/step - loss: 0.6025 - accuracy: 0.9269
    Epoch 5/5
    103/103 [==============================] - 71s 688ms/step - loss: 0.5897 - accuracy: 0.9372
    

# 评估模型
-

```python
loss, accuracy = model.evaluate(test_data)
```

    12/12 [==============================] - 11s 713ms/step - loss: 0.6163 - accuracy: 0.9183
    

# 最后一步：导出模型
-

```python
model.export(export_dir='.')
```

    INFO:tensorflow:Assets written to: C:\Users\阿超吖\AppData\Local\Temp\tmp7o36mowv\assets
    

    INFO:tensorflow:Assets written to: C:\Users\阿超吖\AppData\Local\Temp\tmp7o36mowv\assets
    D:\Download\Anaconda\ANACONDA\lib\site-packages\tensorflow\lite\python\convert.py:766: UserWarning: Statistics for quantized inputs were expected, but not specified; continuing anyway.
      warnings.warn("Statistics for quantized inputs were expected, but not "
    

    INFO:tensorflow:Label file is inside the TFLite model with metadata.
    

    INFO:tensorflow:Label file is inside the TFLite model with metadata.
    

    INFO:tensorflow:Saving labels in C:\Users\阿超吖\AppData\Local\Temp\tmpsezrye35\labels.txt
    

    INFO:tensorflow:Saving labels in C:\Users\阿超吖\AppData\Local\Temp\tmpsezrye35\labels.txt
    

    INFO:tensorflow:TensorFlow Lite model exported successfully: .\model.tflite
    

    INFO:tensorflow:TensorFlow Lite model exported successfully: .\model.tflite
    
-
# 到此实验完毕，完成模型的训练，该模型已经可以在android相关程序中运行使用，功能为：识别花卉图片
