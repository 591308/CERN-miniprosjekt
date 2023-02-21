# CERN-miniprosjekt

This code requires to have downloaded files from https://zenodo.org/record/573298#.Y-pAJnaZNtZ

Also a enviroment with python 3.9.16 with necessary libraries installed

Install cuda, tensorflow-gpu using anaconda

Change jupyter_notebook_config.py add these lines
-c.Session.gpu_id = 0
-c.Session.use_gpu = True

You can find gpu_id using nvidia-smi command usually its equals 0

If cant find jupyter config file run following code in therminal (anaconda)
-jupyter notebook --generate-config


You will have to install some libraries and packages for your enviroment, this is the list of all i had that seems to make everything to work:

#
# Name                    Version                   Build  Channel
_r-mutex                  1.0.0               anacondar_1
_tflow_select             2.1.0                       gpu
abseil-cpp                20210324.2           hd77b12b_0
absl-py                   1.4.0                    pypi_0    pypi
aiohttp                   3.8.3            py39h2bbff1b_0
aiosignal                 1.2.0              pyhd3eb1b0_0
appdirs                   1.4.4              pyhd3eb1b0_0
astor                     0.8.1            py39haa95532_0
asttokens                 2.0.5              pyhd3eb1b0_0
astunparse                1.6.3                      py_0
async-timeout             4.0.2            py39haa95532_0
attrs                     22.1.0           py39haa95532_0
backcall                  0.2.0              pyhd3eb1b0_0
blas                      1.0                         mkl
blinker                   1.4              py39haa95532_0
blis                      0.7.9                    pypi_0    pypi
blosc                     1.21.3               h6c2663c_0
blosc2                    2.0.0                    pypi_0    pypi
brotli                    1.0.9                h2bbff1b_7
brotli-bin                1.0.9                h2bbff1b_7
brotlipy                  0.7.0           py39h2bbff1b_1003
bzip2                     1.0.8                he774522_0
ca-certificates           2023.01.10           haa95532_0
cachetools                5.3.0                    pypi_0    pypi
catalogue                 2.0.8                    pypi_0    pypi
certifi                   2022.12.7        py39haa95532_0
cffi                      1.15.1           py39h2bbff1b_3
cfitsio                   3.470                h2bbff1b_7
charls                    2.2.0                h6c2663c_0
charset-normalizer        2.0.4              pyhd3eb1b0_0
click                     8.1.3                    pypi_0    pypi
cloudpickle               2.0.0              pyhd3eb1b0_0
colorama                  0.4.6            py39haa95532_0
comm                      0.1.2            py39haa95532_0
confection                0.0.4                    pypi_0    pypi
contourpy                 1.0.7                    pypi_0    pypi
cryptography              38.0.4           py39h21b164f_0
cuda                      12.0.1                        0    nvidia
cuda-cccl                 12.0.140                      0    nvidia
cuda-command-line-tools   12.0.1                        0    nvidia
cuda-compiler             12.0.1                        0    nvidia
cuda-cudart               12.0.146                      0    nvidia
cuda-cudart-dev           12.0.146                      0    nvidia
cuda-cuobjdump            12.0.140                      0    nvidia
cuda-cupti                12.0.146                      0    nvidia
cuda-cuxxfilt             12.0.140                      0    nvidia
cuda-demo-suite           12.0.140                      0    nvidia
cuda-documentation        12.0.140                      0    nvidia
cuda-libraries            12.0.1                        0    nvidia
cuda-libraries-dev        12.0.1                        0    nvidia
cuda-nsight-compute       12.0.1                        0    nvidia
cuda-nvcc                 12.0.140                      0    nvidia
cuda-nvdisasm             12.0.140                      0    nvidia
cuda-nvml-dev             12.0.140                      0    nvidia
cuda-nvprof               12.0.146                      0    nvidia
cuda-nvprune              12.0.140                      0    nvidia
cuda-nvrtc                12.0.140                      0    nvidia
cuda-nvrtc-dev            12.0.140                      0    nvidia
cuda-nvtx                 12.0.140                      0    nvidia
cuda-nvvp                 12.0.146                      0    nvidia
cuda-opencl               12.0.140                      0    nvidia
cuda-opencl-dev           12.0.140                      0    nvidia
cuda-profiler-api         12.0.140                      0    nvidia
cuda-runtime              12.0.1                        0    nvidia
cuda-sanitizer-api        12.0.140                      0    nvidia
cuda-toolkit              12.0.1                        0    nvidia
cuda-tools                12.0.1                        0    nvidia
cuda-visual-tools         12.0.1                        0    nvidia
cudatoolkit               11.3.1               h59b6b97_2
cudnn                     8.2.1                cuda11.3_0
cycler                    0.11.0             pyhd3eb1b0_0
cymem                     2.0.7                    pypi_0    pypi
cython                    0.29.33                  pypi_0    pypi
cytoolz                   0.12.0           py39h2bbff1b_0
dask-core                 2022.7.0         py39haa95532_0
debugpy                   1.5.1            py39hd77b12b_0
decorator                 5.1.1              pyhd3eb1b0_0
deepdish                  0.3.7                    pypi_0    pypi
duckduckgo-search         2.8.0                    pypi_0    pypi
entrypoints               0.4              py39haa95532_0
executing                 0.8.3              pyhd3eb1b0_0
fast-histogram            0.9              py39h080aedc_0
fastai                    2.7.10                   pypi_0    pypi
fastcore                  1.5.27                   pypi_0    pypi
fastdownload              0.0.7                    pypi_0    pypi
fastjsonschema            2.16.2                   pypi_0    pypi
fastprogress              1.0.3                    pypi_0    pypi
fftw                      3.3.9                h2bbff1b_1
flatbuffers               23.1.21                  pypi_0    pypi
flit-core                 3.6.0              pyhd3eb1b0_0
fonttools                 4.38.0                   pypi_0    pypi
freetype                  2.12.1               ha860e81_0
frozenlist                1.3.3            py39h2bbff1b_0
fsspec                    2022.11.0        py39haa95532_0
future                    0.18.2           py39haa95532_1
gast                      0.4.0              pyhd3eb1b0_0
giflib                    5.2.1                h8cc25b3_1
google-auth               2.16.0                   pypi_0    pypi
google-auth-oauthlib      0.4.6                    pypi_0    pypi
google-pasta              0.2.0              pyhd3eb1b0_0
grpcio                    1.51.1                   pypi_0    pypi
h5py                      3.7.0            py39h3de5c98_0
hdf5                      1.10.6               h1756f20_1
icc_rt                    2022.1.0             h6049295_2
icu                       68.1                 h6c2663c_0
idna                      3.4              py39haa95532_0
imagecodecs               2021.8.26        py39hc0a7faf_1
imageio                   2.19.3           py39haa95532_0
importlib-metadata        4.11.3           py39haa95532_0
intel-openmp              2021.4.0          haa95532_3556
ipykernel                 6.19.2           py39hd4e2768_0
ipython                   8.7.0            py39haa95532_0
ipython-genutils          0.2.0                    pypi_0    pypi
jedi                      0.18.1           py39haa95532_1
jinja2                    3.1.2                    pypi_0    pypi
joblib                    1.2.0                    pypi_0    pypi
jpeg                      9e                   h2bbff1b_0
jupyter_client            7.4.8            py39haa95532_0
jupyter_core              5.1.1            py39haa95532_0
keras                     2.10.0                   pypi_0    pypi
keras-preprocessing       1.1.2              pyhd3eb1b0_0
kiwisolver                1.4.4            py39hd77b12b_0
langcodes                 3.3.0                    pypi_0    pypi
lcms2                     2.12                 h83e58a3_0
lerc                      3.0                  hd77b12b_0
libaec                    1.0.4                h33f27b4_1
libbrotlicommon           1.0.9                h2bbff1b_7
libbrotlidec              1.0.9                h2bbff1b_7
libbrotlienc              1.0.9                h2bbff1b_7
libclang                  15.0.6.1                 pypi_0    pypi
libcublas                 12.0.2.224                    0    nvidia
libcublas-dev             12.0.2.224                    0    nvidia
libcufft                  11.0.1.95                     0    nvidia
libcufft-dev              11.0.1.95                     0    nvidia
libcurand                 10.3.1.124                    0    nvidia
libcurand-dev             10.3.1.124                    0    nvidia
libcurl                   7.87.0               h86230a5_0
libcusolver               11.4.3.1                      0    nvidia
libcusolver-dev           11.4.3.1                      0    nvidia
libcusparse               12.0.1.140                    0    nvidia
libcusparse-dev           12.0.1.140                    0    nvidia
libdeflate                1.8                  h2bbff1b_5
libnpp                    12.0.1.104                    0    nvidia
libnpp-dev                12.0.1.104                    0    nvidia
libnvjitlink              12.0.140                      0    nvidia
libnvjitlink-dev          12.0.140                      0    nvidia
libnvjpeg                 12.0.1.102                    0    nvidia
libnvjpeg-dev             12.0.1.102                    0    nvidia
libnvvm-samples           12.0.140                      0    nvidia
libpng                    1.6.37               h2a8f88b_0
libprotobuf               3.17.2               h23ce68f_1
libsodium                 1.0.18               h62dcd97_0
libssh2                   1.10.0               hcd4344a_0
libtiff                   4.5.0                h8a3f274_0
libuv                     1.40.0               he774522_0
libwebp                   1.2.4                h2bbff1b_0
libwebp-base              1.2.4                h2bbff1b_0
libzopfli                 1.0.3                ha925a31_0
locket                    1.0.0            py39haa95532_0
lz4-c                     1.9.4                h2bbff1b_0
m2w64-bwidget             1.9.10                        2
m2w64-bzip2               1.0.6                         6
m2w64-expat               2.1.1                         2
m2w64-fftw                3.3.4                         6
m2w64-flac                1.3.1                         3
m2w64-gcc-libgfortran     5.3.0                         6
m2w64-gcc-libs            5.3.0                         7
m2w64-gcc-libs-core       5.3.0                         7
m2w64-gettext             0.19.7                        2
m2w64-gmp                 6.1.0                         2
m2w64-gsl                 2.1                           2
m2w64-libiconv            1.14                          6
m2w64-libjpeg-turbo       1.4.2                         3
m2w64-libogg              1.3.2                         3
m2w64-libpng              1.6.21                        2
m2w64-libsndfile          1.0.26                        2
m2w64-libtiff             4.0.6                         2
m2w64-libvorbis           1.3.5                         2
m2w64-libwinpthread-git   5.0.0.4634.697f757               2
m2w64-libxml2             2.9.3                         4
m2w64-mpfr                3.1.4                         4
m2w64-openblas            0.2.19                        1
m2w64-pcre                8.38                          2
m2w64-speex               1.2rc2                        3
m2w64-speexdsp            1.2rc3                        3
m2w64-tcl                 8.6.5                         3
m2w64-tk                  8.6.5                         3
m2w64-tktable             2.10                          5
m2w64-wineditline         2.101                         5
m2w64-xz                  5.2.2                         2
m2w64-zlib                1.2.8                        10
markdown                  3.4.1            py39haa95532_0
markupsafe                2.1.2                    pypi_0    pypi
matplotlib                3.6.3                    pypi_0    pypi
matplotlib-base           3.6.2            py39h1094b8e_0
matplotlib-inline         0.1.6            py39haa95532_0
mistune                   2.0.4                    pypi_0    pypi
mkl                       2021.4.0           haa95532_640
mkl-service               2.4.0            py39h2bbff1b_0
mkl_fft                   1.3.1            py39h277e83a_0
mkl_random                1.2.2            py39hf11a4ad_0
mpl-scatter-density       0.7                        py_0
msgpack                   1.0.4                    pypi_0    pypi
msys2-conda-epoch         20160418                      1
multidict                 6.0.2            py39h2bbff1b_0
munkres                   1.1.4                      py_0
murmurhash                1.0.9                    pypi_0    pypi
nest-asyncio              1.5.6            py39haa95532_0
networkx                  2.8.4            py39haa95532_0
ninja                     1.10.2               haa95532_5
ninja-base                1.10.2               h6d14046_5
nsight-compute            2022.4.1.6                    0    nvidia
numexpr                   2.8.4                    pypi_0    pypi
numpy                     1.23.5           py39h3b20f71_0
numpy-base                1.23.5           py39h4da318b_0
oauthlib                  3.2.2                    pypi_0    pypi
openjpeg                  2.4.0                h4fc8c34_0
openssl                   1.1.1t               h2bbff1b_0
opt_einsum                3.3.0              pyhd3eb1b0_1
packaging                 22.0             py39haa95532_0
pandas                    1.5.3                    pypi_0    pypi
parso                     0.8.3              pyhd3eb1b0_0
partd                     1.2.0              pyhd3eb1b0_1
pathy                     0.10.1                   pypi_0    pypi
pickleshare               0.7.5           pyhd3eb1b0_1003
pillow                    9.3.0            py39hdc2b20a_1
pip                       22.3.1           py39haa95532_0
platformdirs              2.5.2            py39haa95532_0
pooch                     1.4.0              pyhd3eb1b0_0
preshed                   3.0.8                    pypi_0    pypi
prompt-toolkit            3.0.36           py39haa95532_0
protobuf                  3.19.6                   pypi_0    pypi
psutil                    5.9.0            py39h2bbff1b_0
pure_eval                 0.2.2              pyhd3eb1b0_0
py-cpuinfo                9.0.0                    pypi_0    pypi
pyasn1                    0.4.8              pyhd3eb1b0_0
pyasn1-modules            0.2.8                    pypi_0    pypi
pycparser                 2.21               pyhd3eb1b0_0
pydantic                  1.10.4                   pypi_0    pypi
pygments                  2.11.2             pyhd3eb1b0_0
pyjwt                     2.4.0            py39haa95532_0
pyopenssl                 22.0.0             pyhd3eb1b0_0
pyparsing                 3.0.9            py39haa95532_0
pysocks                   1.7.1            py39haa95532_0
python                    3.9.16               h6244533_0
python-dateutil           2.8.2              pyhd3eb1b0_0
python-flatbuffers        1.12               pyhd3eb1b0_0
pytorch                   1.12.1          cpu_py39h5e1f01c_1
pytz                      2022.7.1                 pypi_0    pypi
pywavelets                1.4.1            py39h2bbff1b_0
pywin32                   305              py39h2bbff1b_0
pyyaml                    6.0              py39h2bbff1b_1
pyzmq                     25.0.0                   pypi_0    pypi
r-base                    3.6.1                hf18239d_1
r-scatterplot3d           0.3_41            r36h6115d3f_0
regex                     2022.10.31               pypi_0    pypi
requests                  2.28.1           py39haa95532_0
requests-oauthlib         1.3.1                    pypi_0    pypi
rfc3339-validator         0.1.4                    pypi_0    pypi
rfc3986-validator         0.1.1                    pypi_0    pypi
rsa                       4.9                      pypi_0    pypi
scikit-image              0.19.3           py39hd77b12b_1
scikit-learn              1.2.0                    pypi_0    pypi
scipy                     1.10.0                   pypi_0    pypi
send2trash                1.8.0                    pypi_0    pypi
sentencepiece             0.1.97                   pypi_0    pypi
setuptools                65.6.3           py39haa95532_0
six                       1.16.0             pyhd3eb1b0_1
smart-open                6.3.0                    pypi_0    pypi
snappy                    1.1.9                h6c2663c_0
sniffio                   1.3.0                    pypi_0    pypi
soupsieve                 2.3.2.post1              pypi_0    pypi
spacy                     3.5.0                    pypi_0    pypi
spacy-legacy              3.0.11                   pypi_0    pypi
spacy-loggers             1.0.4                    pypi_0    pypi
sqlite                    3.40.1               h2bbff1b_0
srsly                     2.4.5                    pypi_0    pypi
stack_data                0.2.0              pyhd3eb1b0_0
tables                    3.8.0                    pypi_0    pypi
tensorboard               2.10.1                   pypi_0    pypi
tensorboard-data-server   0.6.1            py39haa95532_0
tensorboard-plugin-wit    1.8.1            py39haa95532_0
tensorflow                2.11.0                   pypi_0    pypi
tensorflow-base           2.6.0           gpu_py39hb3da07e_0
tensorflow-estimator      2.10.0                   pypi_0    pypi
tensorflow-gpu            2.6.0                h17022bd_0
tensorflow-intel          2.11.0                   pypi_0    pypi
tensorflow-io-gcs-filesystem 0.30.0                   pypi_0    pypi
termcolor                 2.2.0                    pypi_0    pypi
thinc                     8.1.7                    pypi_0    pypi
threadpoolctl             3.1.0                    pypi_0    pypi
tifffile                  2021.7.2           pyhd3eb1b0_2
tinycss2                  1.2.1                    pypi_0    pypi
tk                        8.6.12               h2bbff1b_0
tokenizers                0.13.2                   pypi_0    pypi
toolz                     0.12.0           py39haa95532_0
torch                     1.13.1                   pypi_0    pypi
torchaudio                0.13.1                   pypi_0    pypi
torchvision               0.13.1          cpu_py39h378ed51_0
tornado                   6.2              py39h2bbff1b_0
tqdm                      4.64.1                   pypi_0    pypi
traitlets                 5.7.1            py39haa95532_0
typer                     0.7.0                    pypi_0    pypi
typing-extensions         4.4.0            py39haa95532_0
typing_extensions         4.4.0            py39haa95532_0
tzdata                    2022g                h04d1e81_0
uri-template              1.2.0                    pypi_0    pypi
urllib3                   1.26.14          py39haa95532_0
vc                        14.2                 h21ff451_1
vs2015_runtime            14.27.29016          h5e58377_2
wasabi                    1.1.1                    pypi_0    pypi
wcwidth                   0.2.5              pyhd3eb1b0_0
webcolors                 1.12                     pypi_0    pypi
webencodings              0.5.1                    pypi_0    pypi
websocket-client          1.4.2                    pypi_0    pypi
werkzeug                  2.2.2            py39haa95532_0
wheel                     0.35.1             pyhd3eb1b0_0
win_inet_pton             1.1.0            py39haa95532_0
wincertstore              0.2              py39haa95532_2
wrapt                     1.14.1           py39h2bbff1b_0
xxhash                    3.2.0                    pypi_0    pypi
xz                        5.2.10               h8cc25b3_1
yaml                      0.2.5                he774522_0
yarl                      1.8.1            py39h2bbff1b_0
zeromq                    4.3.4                hd77b12b_0
zfp                       0.5.5                hd77b12b_6
zipp                      3.11.0           py39haa95532_0
zlib                      1.2.13               h8cc25b3_0
zstd                      1.5.2                h19a0ad4_0
