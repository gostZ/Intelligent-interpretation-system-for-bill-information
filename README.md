# Intelligent-interpretation-system-for-bill-information
## I. Environment deployment
Development editor: pycharm
Running environment: Ubuntu 16.04.7 LTS (GNU/Linux 4.15.0-142-generic x86_64), anaconda virtual environment
Required libraries and packages: The following packages are installed in the anaconda Innovations virtual environment.

Cython	0.29.28
Deprecated	1.2.13
Jinja2	3.1.1
Keras	2.1.5
Keras-Preprocessing	1.1.2
Markdown	3.3.6
MarkupSafe	2.1.1
Pillow	9.1.0
PyYAML	6.0
Pygments	2.12.0
QtPy	2.0.1
Send2Trash	1.8.0
Werkzeug	2.1.1
absl-py	0.15.0
appnope	0.1.3
argon2-cffi	21.3.0
argon2-cffi-bindings	21.2.0
asttokens	2.0.5
astunparse	1.6.3
async-timeout	4.0.2
attrs	21.4.0
backcall	0.2.0
beautifulsoup4	4.11.1
bleach	5.0.0
bs4	0.0.1
cachetools	4.2.4
certifi	2021.10.8
cffi	1.15.0
charset-normalizer	2.0.12
cycler	0.11.0
debugpy	1.6.0
decorator	5.1.1
defusedxml	0.7.1
easydict	1.9
entrypoints	0.4
executing	0.8.3
fastjsonschema	2.15.3
flatbuffers	1.12
fonttools	4.33.2
gast	0.3.3
google-auth	1.35.0
google-auth-oauthlib	0.4.6
google-pasta	0.2.0
grpcio	1.34.1
h5py	2.10.0
idna	3.3
importlib-metadata	4.11.3
importlib-resources	5.7.1
ipykernel	6.13.0
ipython	8.2.0
ipython-genutils	0.2.0
ipywidgets	7.7.0
jedi	0.18.1
jsonschema	4.4.0
jupyter	1.0.0
jupyter-client	7.2.2
jupyter-console	6.4.3
jupyter-core	4.10.0
jupyterlab-pygments	0.2.2
jupyterlab-widgets	1.1.0
keras-nightly	2.5.0.dev2021032900
kiwisolver	1.4.2
lmdb	1.3.0
lxml	4.8.0
mahotas	1.4.12
matplotlib	3.5.1
matplotlib-inline	0.1.3
mistune	0.8.4
nbclient	0.6.0
nbconvert	6.5.0
nbformat	5.3.0
nest-asyncio	1.5.5
notebook	6.4.11
numpy	1.19.5
oauthlib	3.2.0
opencv-contrib-python	4.1.2.30
opt-einsum	3.3.0
packaging	21.3
pandas	1.4.2
pandocfilters	1.5.0
parso	0.8.3
pexpect	4.8.0
pickleshare	0.7.5
pika	1.2.0
pip	22.0.4
prometheus-client	0.14.1
prompt-toolkit	3.0.29
protobuf	3.20.1
psutil	5.9.0
ptyprocess	0.7.0
pure-eval	0.2.2
pyasn1	0.4.8
pyasn1-modules	0.2.8
pycparser	2.21
pyparsing	3.0.8
pyrsistent	0.18.1
python-dateutil	2.8.2
pytz	2022.1
pyzmq	22.3.0
qtconsole	5.3.0
redis	4.2.2
requests	2.27.1
requests-oauthlib	1.3.1
rsa	4.8
scipy	1.4.1
setuptools	57.0.0
six	1.15.0
soupsieve	2.3.2.post1
stack-data	0.2.0
tensorboard	2.2.2
tensorboard-data-server	0.6.1
tensorboard-plugin-wit	1.8.1
tensorflow	2.2.0
tensorflow-estimator	2.2.0
termcolor	1.1.0
terminado	0.13.3
tinycss2	1.1.1
tornado	6.1
traitlets	5.1.1
typing-extensions	3.7.4.3
urllib3	1.26.9
wcwidth	0.2.5
web.py	0.40.dev0
webencodings	0.5.1
wheel	0.36.2
widgetsnbextension	3.6.0
wrapt	1.12.1
zipp	3.8.0

Follow the project prompts to find the packages you have missed to install.
### The environment configuration method is as follows
#### 1) Create a python environment using conda
conda create -n chineseocr python=3.6 pip scipy numpy jupyter ipython.
#### 2) Activate the environment
Source code activation chineseocr
#### 3) Install the package
conda : easydict opencv-contrib-python==4.0.0.21 Cython h5py==2.10.0 lmdb mahotas pandas requests bs4 matplotlib lxml -i https://pypi.tuna.tsinghua.edu.cn/simple/
pip install easydict opencv-contrib-python==4.0.0.21 Cython h5py lmdb mahotas pandas requests bs4 matplotlib lxml -i https://pypi.tuna.tsinghua.edu.cn/simple/
pip install -U pillow -i https://pypi.tuna.tsinghua.edu.cn/simple/
pip install web.py==0.40.dev0 redis
pip install keras==2.1.5 tensorflow==1.8
conda: pytorch-cpu torchvision-cpu -c pytorch
## II. Running steps and results

<img width="322" alt="image" src="https://user-images.githubusercontent.com/50789587/221418082-f4f30019-5940-4cf4-978e-32a78a9492ef.png">

As shown in the system display, click on the upload image and select the type of recognition to view the returned results. Note that you need to turn off the display of the test result image before the returned results can be displayed on the page. The effect is as follows.

<img width="423" alt="image" src="https://user-images.githubusercontent.com/50789587/221418116-424523d4-8285-412c-8c4f-4b09740d2495.png">
