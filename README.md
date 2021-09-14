# Setting up Environments and Installing Packages Using Conda

## Summary of steps to complete

- [ ] Fork this repository so you have your own copy to work on.
- [ ] Clone the repository on your local machine. 
- [ ] Edit this README.md file on your machine.
- [ ] Run the Conda commands shown in the video and describe them in the table below.
- [ ] Push your changes to your GitHub repository.
- [ ] Submit a link to this GitHub repository in Canvas.

## 1. Fork & Clone this repository

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/exerGitPractice
* This can also be done directly in VSCode
  * Create a new folder on your machine where you want to put this repository if you don't already have one you want to use.
  * Copy the Clone or Download path for this repository from GitHub.
  * In VSCode from the command pallette (Ctrl-Shift-P) run Git: Clone
  * Paste the path into the path field which pops up
  * Select your new folder you created on your machine
  * A new folder for the repository with the repository files should be in the folder you selected showing in the Explorer window in VSCode on the left side.
  
## Edit your README.md file

* [ ] In an editor of your choice (i.e. VSCode) edit this README.md file to add the answers requested in the tables.

## Follow along with this tutorial

* Conda What and Why? (27 min): https://www.youtube.com/watch?v=23aQdrS58e0&list=PLG9A6ovzPqX6d9uWzx0UYN9pm0zzl5ofA&index=13&t=0s
  * He installs Miniconda. We will be using Anaconda. Don't install Miniconda.
  * Follow along with the rest of the tutorial.
  * Go ahead and create the environments as he creates them in the tutorial.
  * (2021 update: I recommend managing environments as shown in the new Anaconda introduction video. https://anaconda.cloud/tutorials/getting-started-with-anaconda-individual-edition%3Fsource%3Dindividual-edition-tutorial) If you want to try creating the environments using the user interface for Anaconda Navigator instead of the command line shown in the Conda What and Why tutorial, that's fine. But watch the Conda What and Why tutorial to understand some of the differences between Conda environments and other types of virtual environments available in Python.

## Conda Concepts

* [ ] Describe the Conda concepts used in the video and listed in the table below.

|   Concept   |         Description or short answer         |
|     ---     |                     ---                     |
|What is the purpose of having different environments?     |(So you can do different tasks like web development, data analysis, and A.I.)|
|What is the default package manager in Python?            |(pip)|
|How do you manage environments and packages in Anaconda?  |(install virtualenv, or with anaconda you get conda, which acts as a package manager and a virtual environment)|
|`conda list`       |(# Name                    Version                   Build  Channel
_ipyw_jlab_nb_ext_conf    0.1.0                    py38_0
alabaster                 0.7.12             pyhd3eb1b0_0
anaconda                  2021.05                  py38_0
anaconda-client           1.7.2                    py38_0
anaconda-navigator        2.0.3                    py38_0
anaconda-project          0.9.1              pyhd3eb1b0_1
anyio                     2.2.0            py38haa95532_2
appdirs                   1.4.4                      py_0
argh                      0.26.2                   py38_0
argon2-cffi               20.1.0           py38h2bbff1b_1
asn1crypto                1.4.0                      py_0
astroid                   2.5              py38haa95532_1
astropy                   4.2.1            py38h2bbff1b_1
async_generator           1.10               pyhd3eb1b0_0
atomicwrites              1.4.0                      py_0
attrs                     20.3.0             pyhd3eb1b0_0
autopep8                  1.5.6              pyhd3eb1b0_0
babel                     2.9.0              pyhd3eb1b0_0
backcall                  0.2.0              pyhd3eb1b0_0
backports                 1.0                pyhd3eb1b0_2
backports.functools_lru_cache 1.6.4              pyhd3eb1b0_0
backports.shutil_get_terminal_size 1.0.0              pyhd3eb1b0_3
backports.tempfile        1.0                pyhd3eb1b0_1
backports.weakref         1.0.post1                  py_1
bcrypt                    3.2.0            py38he774522_0
beautifulsoup4            4.9.3              pyha847dfd_0
bitarray                  1.9.2            py38h2bbff1b_1
bkcharts                  0.2                      py38_0
black                     19.10b0                    py_0
blas                      1.0                         mkl
bleach                    3.3.0              pyhd3eb1b0_0
blosc                     1.21.0               h19a0ad4_0
bokeh                     2.3.2            py38haa95532_0
boto                      2.49.0                   py38_0
bottleneck                1.3.2            py38h2a96729_1
brotli                    1.0.9                ha925a31_2
brotlipy                  0.7.0           py38h2bbff1b_1003
bzip2                     1.0.8                he774522_0
ca-certificates           2021.4.13            haa95532_1
certifi                   2020.12.5        py38haa95532_0
cffi                      1.14.5           py38hcd4344a_0
chardet                   4.0.0           py38haa95532_1003
charls                    2.2.0                h6c2663c_0
click                     7.1.2              pyhd3eb1b0_0
cloudpickle               1.6.0                      py_0
clyent                    1.2.2                    py38_1
colorama                  0.4.4              pyhd3eb1b0_0
comtypes                  1.1.9           py38haa95532_1002
conda                     4.10.3           py38haa95532_0
conda-build               3.21.4           py38haa95532_0
conda-content-trust       0.1.1              pyhd3eb1b0_0
conda-env                 2.6.0                         1
conda-package-handling    1.7.3            py38h8cc25b3_1
conda-repo-cli            1.0.4              pyhd3eb1b0_0
conda-token               0.3.0              pyhd3eb1b0_0
conda-verify              3.4.2                      py_1
console_shortcut          0.1.1                         4
contextlib2               0.6.0.post1                py_0
cryptography              3.4.7            py38h71e12ea_0
curl                      7.71.1               h2a8f88b_1
cycler                    0.10.0                   py38_0
cython                    0.29.23          py38hd77b12b_0
cytoolz                   0.11.0           py38he774522_0
dask                      2021.4.0           pyhd3eb1b0_0
dask-core                 2021.4.0           pyhd3eb1b0_0
decorator                 5.0.6              pyhd3eb1b0_0
defusedxml                0.7.1              pyhd3eb1b0_0
diff-match-patch          20200713                   py_0
distributed               2021.4.0         py38haa95532_0
docutils                  0.17             py38haa95532_1
entrypoints               0.3                      py38_0
et_xmlfile                1.0.1                   py_1001
fastcache                 1.1.0            py38he774522_0
filelock                  3.0.12             pyhd3eb1b0_1
flake8                    3.9.0              pyhd3eb1b0_0
flask                     1.1.2              pyhd3eb1b0_0
freetype                  2.10.4               hd328e21_0
fsspec                    0.9.0              pyhd3eb1b0_0
future                    0.18.2                   py38_1
get_terminal_size         1.0.0                h38e98db_0
gevent                    21.1.2           py38h2bbff1b_1
giflib                    5.2.1                h62dcd97_0
glob2                     0.7                pyhd3eb1b0_0
greenlet                  1.0.0            py38hd77b12b_2
h5py                      2.10.0           py38h5e291fa_0
hdf5                      1.10.4               h7ebc959_0
heapdict                  1.0.1                      py_0
html5lib                  1.1                        py_0
icc_rt                    2019.0.0             h0cc432a_1
icu                       58.2                 ha925a31_3
idna                      2.10               pyhd3eb1b0_0
imagecodecs               2021.3.31        py38h5da4933_0
imageio                   2.9.0              pyhd3eb1b0_0
imagesize                 1.2.0              pyhd3eb1b0_0
importlib-metadata        3.10.0           py38haa95532_0
importlib_metadata        3.10.0               hd3eb1b0_0
iniconfig                 1.1.1              pyhd3eb1b0_0
intel-openmp              2021.2.0           haa95532_616
intervaltree              3.1.0                      py_0
ipykernel                 5.3.4            py38h5ca1d4c_0
ipython                   7.22.0           py38hd4e2768_0
ipython_genutils          0.2.0              pyhd3eb1b0_1
ipywidgets                7.6.3              pyhd3eb1b0_1
isort                     5.8.0              pyhd3eb1b0_0
itsdangerous              1.1.0              pyhd3eb1b0_0
jdcal                     1.4.1                      py_0
jedi                      0.17.2           py38haa95532_1
jinja2                    2.11.3             pyhd3eb1b0_0
joblib                    1.0.1              pyhd3eb1b0_0
jpeg                      9b                   hb83a4c4_2
json5                     0.9.5                      py_0
jsonschema                3.2.0                      py_2
jupyter                   1.0.0                    py38_7
jupyter-packaging         0.7.12             pyhd3eb1b0_0
jupyter_client            6.1.12             pyhd3eb1b0_0
jupyter_console           6.4.0              pyhd3eb1b0_0
jupyter_core              4.7.1            py38haa95532_0
jupyter_server            1.4.1            py38haa95532_0
jupyterlab                3.0.14             pyhd3eb1b0_1
jupyterlab_pygments       0.1.2                      py_0
jupyterlab_server         2.4.0              pyhd3eb1b0_0
jupyterlab_widgets        1.0.0              pyhd3eb1b0_1
keyring                   22.3.0           py38haa95532_0
kiwisolver                1.3.1            py38hd77b12b_0
krb5                      1.18.2               hc04afaa_0
lazy-object-proxy         1.6.0            py38h2bbff1b_0
lcms2                     2.12                 h83e58a3_0
lerc                      2.2.1                hd77b12b_0
libaec                    1.0.4                h33f27b4_1
libarchive                3.4.2                h5e25573_0
libcurl                   7.71.1               h2a8f88b_1
libdeflate                1.7                  h2bbff1b_5
libiconv                  1.15                 h1df5818_7
liblief                   0.10.1               ha925a31_0
libpng                    1.6.37               h2a8f88b_0
libsodium                 1.0.18               h62dcd97_0
libspatialindex           1.9.3                h6c2663c_0
libssh2                   1.9.0                h7a1dbc1_1
libtiff                   4.2.0                hd0e1b90_0
libxml2                   2.9.10               hb89e7f3_3
libxslt                   1.1.34               he774522_0
libzopfli                 1.0.3                ha925a31_0
llvmlite                  0.36.0           py38h34b8924_4
locket                    0.2.1            py38haa95532_1
lxml                      4.6.3            py38h9b66d53_0
lz4-c                     1.9.3                h2bbff1b_0
lzo                       2.10                 he774522_2
m2w64-gcc-libgfortran     5.3.0                         6
m2w64-gcc-libs            5.3.0                         7
m2w64-gcc-libs-core       5.3.0                         7
m2w64-gmp                 6.1.0                         2
m2w64-libwinpthread-git   5.0.0.4634.697f757               2
markupsafe                1.1.1            py38he774522_0
matplotlib                3.3.4            py38haa95532_0
matplotlib-base           3.3.4            py38h49ac443_0
mccabe                    0.6.1                    py38_1
menuinst                  1.4.16           py38he774522_1
mistune                   0.8.4           py38he774522_1000
mkl                       2021.2.0           haa95532_296
mkl-service               2.3.0            py38h2bbff1b_1
mkl_fft                   1.3.0            py38h277e83a_2
mkl_random                1.2.1            py38hf11a4ad_2
mock                      4.0.3              pyhd3eb1b0_0
more-itertools            8.7.0              pyhd3eb1b0_0
mpmath                    1.2.1            py38haa95532_0
msgpack-python            1.0.2            py38h59b6b97_1
msys2-conda-epoch         20160418                      1
multipledispatch          0.6.0                    py38_0
mypy_extensions           0.4.3                    py38_0
navigator-updater         0.2.1                    py38_0
nbclassic                 0.2.6              pyhd3eb1b0_0
nbclient                  0.5.3              pyhd3eb1b0_0
nbconvert                 6.0.7                    py38_0
nbformat                  5.1.3              pyhd3eb1b0_0
nest-asyncio              1.5.1              pyhd3eb1b0_0
networkx                  2.5                        py_0
nltk                      3.6.1              pyhd3eb1b0_0
nose                      1.3.7           pyhd3eb1b0_1006
notebook                  6.3.0            py38haa95532_0
numba                     0.53.1           py38hf11a4ad_0
numexpr                   2.7.3            py38hb80d3ca_1
numpy                     1.20.1           py38h34a8a5c_0
numpy-base                1.20.1           py38haf7ebc8_0
numpydoc                  1.1.0              pyhd3eb1b0_1
olefile                   0.46                       py_0
openjpeg                  2.3.0                h5ec785f_1
openpyxl                  3.0.7              pyhd3eb1b0_0
openssl                   1.1.1k               h2bbff1b_0
packaging                 20.9               pyhd3eb1b0_0
pandas                    1.2.4            py38hd77b12b_0
pandoc                    2.12                 haa95532_0
pandocfilters             1.4.3            py38haa95532_1
paramiko                  2.7.2                      py_0
parso                     0.7.0                      py_0
partd                     1.2.0              pyhd3eb1b0_0
path                      15.1.2           py38haa95532_0
path.py                   12.5.0                        0
pathlib2                  2.3.5            py38haa95532_2
pathspec                  0.7.0                      py_0
patsy                     0.5.1                    py38_0
pep8                      1.7.1                    py38_0
pexpect                   4.8.0              pyhd3eb1b0_3
pickleshare               0.7.5           pyhd3eb1b0_1003
pillow                    8.2.0            py38h4fa10fc_0
pip                       21.0.1           py38haa95532_0
pkginfo                   1.7.0            py38haa95532_0
pluggy                    0.13.1           py38haa95532_0
ply                       3.11                     py38_0
powershell_shortcut       0.0.1                         3
prometheus_client         0.10.1             pyhd3eb1b0_0
prompt-toolkit            3.0.17             pyh06a4308_0
prompt_toolkit            3.0.17               hd3eb1b0_0
psutil                    5.8.0            py38h2bbff1b_1
ptyprocess                0.7.0              pyhd3eb1b0_2
py                        1.10.0             pyhd3eb1b0_0
py-lief                   0.10.1           py38ha925a31_0
pycodestyle               2.6.0              pyhd3eb1b0_0
pycosat                   0.6.3            py38h2bbff1b_0
pycparser                 2.20                       py_2
pycurl                    7.43.0.6         py38h7a1dbc1_0
pydocstyle                6.0.0              pyhd3eb1b0_0
pyerfa                    1.7.3            py38h2bbff1b_0
pyflakes                  2.2.0              pyhd3eb1b0_0
pygments                  2.8.1              pyhd3eb1b0_0
pylint                    2.7.4            py38haa95532_1
pyls-black                0.4.6                hd3eb1b0_0
pyls-spyder               0.3.2              pyhd3eb1b0_0
pynacl                    1.4.0            py38h62dcd97_1
pyodbc                    4.0.30           py38ha925a31_0
pyopenssl                 20.0.1             pyhd3eb1b0_1
pyparsing                 2.4.7              pyhd3eb1b0_0
pyqt                      5.9.2            py38ha925a31_4
pyreadline                2.1                      py38_1
pyrsistent                0.17.3           py38he774522_0
pysocks                   1.7.1            py38haa95532_0
pytables                  3.6.1            py38ha5be198_0
pytest                    6.2.3            py38haa95532_2
python                    3.8.8                hdbf39b2_5
python-dateutil           2.8.1              pyhd3eb1b0_0
python-jsonrpc-server     0.4.0                      py_0
python-language-server    0.36.2             pyhd3eb1b0_0
python-libarchive-c       2.9                pyhd3eb1b0_1
pytz                      2021.1             pyhd3eb1b0_0
pywavelets                1.1.1            py38he774522_2
pywin32                   227              py38he774522_1
pywin32-ctypes            0.2.0                 py38_1000
pywinpty                  0.5.7                    py38_0
pyyaml                    5.4.1            py38h2bbff1b_1
pyzmq                     20.0.0           py38hd77b12b_1
qdarkstyle                2.8.1                      py_0
qt                        5.9.7            vc14h73c81de_0
qtawesome                 1.0.2              pyhd3eb1b0_0
qtconsole                 5.0.3              pyhd3eb1b0_0
qtpy                      1.9.0                      py_0
regex                     2021.4.4         py38h2bbff1b_0
requests                  2.25.1             pyhd3eb1b0_0
rope                      0.18.0                     py_0
rtree                     0.9.7            py38h2eaa2aa_1
ruamel_yaml               0.15.100         py38h2bbff1b_0
scikit-image              0.18.1           py38hf11a4ad_0
scikit-learn              0.24.1           py38hf11a4ad_0
scipy                     1.6.2            py38h66253e8_1
seaborn                   0.11.1             pyhd3eb1b0_0
send2trash                1.5.0              pyhd3eb1b0_1
setuptools                52.0.0           py38haa95532_0
simplegeneric             0.8.1                    py38_2
singledispatch            3.6.1           pyhd3eb1b0_1001
sip                       4.19.13          py38ha925a31_0
six                       1.15.0           py38haa95532_0
snappy                    1.1.8                h33f27b4_0
sniffio                   1.2.0            py38haa95532_1
snowballstemmer           2.1.0              pyhd3eb1b0_0
sortedcollections         2.1.0              pyhd3eb1b0_0
sortedcontainers          2.3.0              pyhd3eb1b0_0
soupsieve                 2.2.1              pyhd3eb1b0_0
sphinx                    4.0.1              pyhd3eb1b0_0
sphinxcontrib             1.0                      py38_1
sphinxcontrib-applehelp   1.0.2              pyhd3eb1b0_0
sphinxcontrib-devhelp     1.0.2              pyhd3eb1b0_0
sphinxcontrib-htmlhelp    1.0.3              pyhd3eb1b0_0
sphinxcontrib-jsmath      1.0.1              pyhd3eb1b0_0
sphinxcontrib-qthelp      1.0.3              pyhd3eb1b0_0
sphinxcontrib-serializinghtml 1.1.4              pyhd3eb1b0_0
sphinxcontrib-websupport  1.2.4                      py_0
spyder                    4.2.5            py38haa95532_0
spyder-kernels            1.10.2           py38haa95532_0
sqlalchemy                1.4.7            py38h2bbff1b_0
sqlite                    3.35.4               h2bbff1b_0
statsmodels               0.12.2           py38h2bbff1b_0
sympy                     1.8              py38haa95532_0
tbb                       2020.3               h74a9793_0
tblib                     1.7.0                      py_0
terminado                 0.9.4            py38haa95532_0
testpath                  0.4.4              pyhd3eb1b0_0
textdistance              4.2.1              pyhd3eb1b0_0
threadpoolctl             2.1.0              pyh5ca1d4c_0
three-merge               0.1.1              pyhd3eb1b0_0
tifffile                  2021.4.8           pyhd3eb1b0_2
tk                        8.6.10               he774522_0
toml                      0.10.2             pyhd3eb1b0_0
toolz                     0.11.1             pyhd3eb1b0_0
tornado                   6.1              py38h2bbff1b_0
tqdm                      4.59.0             pyhd3eb1b0_1
traitlets                 5.0.5              pyhd3eb1b0_0
typed-ast                 1.4.2            py38h2bbff1b_1
typing_extensions         3.7.4.3            pyha847dfd_0
ujson                     4.0.2            py38hd77b12b_0
unicodecsv                0.14.1                   py38_0
urllib3                   1.26.4             pyhd3eb1b0_0
vc                        14.2                 h21ff451_1
vs2015_runtime            14.27.29016          h5e58377_2
watchdog                  1.0.2            py38haa95532_1
wcwidth                   0.2.5                      py_0
webencodings              0.5.1                    py38_1
werkzeug                  1.0.1              pyhd3eb1b0_0
wheel                     0.36.2             pyhd3eb1b0_0
widgetsnbextension        3.5.1                    py38_0
win_inet_pton             1.1.0            py38haa95532_0
win_unicode_console       0.5                      py38_0
wincertstore              0.2                      py38_0
winpty                    0.4.3                         4
wrapt                     1.12.1           py38he774522_1
xlrd                      2.0.1              pyhd3eb1b0_0
xlsxwriter                1.3.8              pyhd3eb1b0_0
xlwings                   0.23.0           py38haa95532_0
xlwt                      1.3.0                    py38_0
xmltodict                 0.12.0                     py_0
xz                        5.2.5                h62dcd97_0
yaml                      0.2.5                he774522_0
yapf                      0.31.0             pyhd3eb1b0_0
zeromq                    4.3.3                ha925a31_3
zfp                       0.5.5                hd77b12b_6
zict                      2.0.0              pyhd3eb1b0_0
zipp                      3.4.1              pyhd3eb1b0_0
zlib                      1.2.11               h62dcd97_4
zope                      1.0                      py38_1
zope.event                4.5.0                    py38_0
zope.interface            5.3.0            py38h2bbff1b_0
zstd                      1.4.5                h04227a9_0)|
|`conda env list`       |(C:\Users\steph\anaconda3.8)|
|How do you keep your base environment unchanged?       |(create environment with package and then other environment for other packages. Install seperately. )|
|What is the link to the Conda cheat sheet? (link in video notes is broken)      |(https://conda.io/projects/conda/en/latest/user-guide/cheatsheet.html)|
|`conda create --name XXXX`       |(ai1 python=3.8)|
|`source activate XXXX`       |(* just type * activate ai1)|
|`conda install YYYY`       |(python 3.8.11)|
|channels in Conda       |(defaults)|
|`conda install -c ZZZZ YYYY`       |(pytorch pytorch)|
|`conda config --show channels`       |(defaults)|
|`conda config --add channels ZZZZ`       |(conda-forge)|
|conda-forge.org       |(https://conda-forge.org/feedstock-outputs/)|
|`source deactivate`       |(deactivates the environment, not the channel)|
|`conda config --get channels`       |(will look at forge channel first, then defaults)|

* After creating the environments he created in the video on your computer, what would the results of running the command `conda env list` look like with the da35 environment activated. Paste the output from your command prompt in the code block below.

```
base                     C:\Users\steph\anaconda3.8
ai1                      C:\Users\steph\anaconda3.8\envs\ai1
da35                  *  C:\Users\steph\anaconda3.8\envs\da35.


```
* What command would you use to remove the environments you created for this exercise from your computer?

```
 deactivate.

```
## 2021 Update
Python, Anaconda, and many programming languages are constantly evolving. The video Conda What and Why provides a great explanation of why you may want to use virtual environments for your Python projects, and it provides a nice demonstration of how to work in the command line. However, environment management using Anaconda Navigator is more user friently than ever. I personally will be using Anaconda Navigator to manage environments and packages since it seems easier to see what is going on using the GUI. If you haven't done so already watch the introduction to Anaconda video and pay close attention to the section on using Anaconda Navigator to create environments and install packages. https://anaconda.cloud/tutorials/getting-started-with-anaconda-individual-edition%3Fsource%3Dindividual-edition-tutorial
