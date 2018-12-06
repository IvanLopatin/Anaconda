
###After install anaconda and if he not found icons anaconda-navigator we can do:
!!!!
Change to your directory
 /D=%UserProfile%\Anaconda
%UserProfile%\Anaconda\Scripts\activate.bat
!!!!

#run scripts
cd %UserProfile%
powershell -command "& { (New-Object Net.WebClient).DownloadFile('https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe', 'mc3.exe') }"
start /wait "" mc3.exe /InstallationType=JustMe /AddToPath=0 /RegisterPython=0 /NoRegistry=0 /S /D=%UserProfile%\Anaconda
%UserProfile%\Anaconda\Scripts\activate.bat
conda install -y anaconda=5.0.1 conda-build _ipyw_jlab_nb_ext_conf






####info in anaconda
conda info
conda list --show-channel-urls
anaconda-navigator

#####Install package when your anaconda navigator not started and his icons not in directoty
pip install pyqt5
conda update conda
conda update --all 
conda install anaconda-navigator=1.8.5
conda update anaconda-navigator

#####start anaconda-navigator
(base) C:\Users\xx>anaconda-navigator


(base) C:\Users\xx>anaconda-navigator


(base) C:\Users\xx>conda install anaconda-navigator=1.8.5
Solving environment: done

## Package Plan ##

  environment location: C:\Users\xx\Anaconda

  added / updated specs:
    - anaconda-navigator=1.8.5


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    certifi-2018.10.15         |           py36_0         138 KB
    python-dateutil-2.7.5      |           py36_0         276 KB
    jupyter_core-4.4.0         |           py36_0          85 KB
    ruamel_yaml-0.15.46        |   py36hfa6e2cd_0         262 KB
    icu-58.2                   |       ha66f8fd_1        21.9 MB
    pyqt-5.9.2                 |   py36h6538335_2         4.2 MB
    pyyaml-3.13                |   py36hfa6e2cd_0         148 KB
    pytz-2018.7                |           py36_0         260 KB
    jpeg-9b                    |       hb83a4c4_2         313 KB
    pycparser-2.19             |           py36_0         174 KB
    sip-4.19.8                 |   py36h6538335_0         282 KB
    clyent-1.2.2               |           py36_1          18 KB
    pillow-5.3.0               |   py36hdc69c19_0         667 KB
    pycosat-0.6.3              |   py36hfa6e2cd_0          98 KB
    conda-4.5.11               |           py36_0         1.0 MB
    freetype-2.9.1             |       ha9979f8_1         470 KB
    traitlets-4.3.2            |   py36h096827d_0         131 KB
    psutil-5.4.8               |   py36he774522_0         333 KB
    asn1crypto-0.24.0          |           py36_0         155 KB
    six-1.11.0                 |           py36_1          21 KB
    wheel-0.32.3               |           py36_0          53 KB
    idna-2.7                   |           py36_0         132 KB
    chardet-3.0.4              |           py36_1         210 KB
    pyopenssl-18.0.0           |           py36_0          83 KB
    pywin32-223                |   py36hfa6e2cd_1         9.3 MB
    libpng-1.6.35              |       h2a8f88b_0         589 KB
    qtpy-1.5.2                 |           py36_0          53 KB
    qt-5.9.6                   |   vc14h1e9a669_2        93.9 MB
    sqlite-3.25.3              |       he774522_0         937 KB
    ipython_genutils-0.2.0     |   py36h3c5d0ee_0          39 KB
    wincertstore-0.2           |   py36h7fe50ca_0          13 KB
    cffi-1.11.5                |   py36h74b6da3_1         213 KB
    olefile-0.46               |           py36_0          49 KB
    tk-8.6.8                   |       hfa6e2cd_0         3.8 MB
    pysocks-1.6.8              |           py36_0          23 KB
    jsonschema-2.6.0           |   py36h7636477_0         104 KB
    zlib-1.2.11                |       h62dcd97_3         128 KB
    libtiff-4.0.9              |       h36446d0_2         829 KB
    decorator-4.3.0            |           py36_0          16 KB
    pip-18.1                   |           py36_0         1.8 MB
    anaconda-client-1.7.2      |           py36_0         200 KB
    menuinst-1.4.14            |   py36hfa6e2cd_0          92 KB
    cryptography-2.3.1         |   py36h74b6da3_0         509 KB
    anaconda-navigator-1.8.5   |           py36_0         4.7 MB
    win_inet_pton-1.0.1        |           py36_1           6 KB
    setuptools-40.6.2          |           py36_0         646 KB
    requests-2.20.1            |           py36_0          85 KB
    python-3.6.7               |       h33f27b4_1        20.9 MB
    urllib3-1.23               |           py36_0         152 KB
    nbformat-4.4.0             |   py36h3a5bc1b_0         157 KB
    ------------------------------------------------------------
                                           Total:       170.5 MB

The following NEW packages will be INSTALLED:

    anaconda-client:    1.7.2-py36_0
    anaconda-navigator: 1.8.5-py36_0
    clyent:             1.2.2-py36_1
    decorator:          4.3.0-py36_0
    freetype:           2.9.1-ha9979f8_1
    icu:                58.2-ha66f8fd_1
    ipython_genutils:   0.2.0-py36h3c5d0ee_0
    jpeg:               9b-hb83a4c4_2
    jsonschema:         2.6.0-py36h7636477_0
    jupyter_core:       4.4.0-py36_0
    libpng:             1.6.35-h2a8f88b_0
    libtiff:            4.0.9-h36446d0_2
    nbformat:           4.4.0-py36h3a5bc1b_0
    olefile:            0.46-py36_0
    pillow:             5.3.0-py36hdc69c19_0
    psutil:             5.4.8-py36he774522_0
    pyqt:               5.9.2-py36h6538335_2
    python-dateutil:    2.7.5-py36_0
    pytz:               2018.7-py36_0
    pyyaml:             3.13-py36hfa6e2cd_0
    qt:                 5.9.6-vc14h1e9a669_2
    qtpy:               1.5.2-py36_0
    sip:                4.19.8-py36h6538335_0
    sqlite:             3.25.3-he774522_0
    tk:                 8.6.8-hfa6e2cd_0
    traitlets:          4.3.2-py36h096827d_0
    zlib:               1.2.11-h62dcd97_3

The following packages will be UPDATED:

    asn1crypto:         0.24.0-py37_0          --> 0.24.0-py36_0
    certifi:            2018.10.15-py37_0      --> 2018.10.15-py36_0
    cffi:               1.11.5-py37h74b6da3_1  --> 1.11.5-py36h74b6da3_1
    chardet:            3.0.4-py37_1           --> 3.0.4-py36_1
    conda:              4.5.11-py37_0          --> 4.5.11-py36_0
    idna:               2.7-py37_0             --> 2.7-py36_0
    menuinst:           1.4.14-py37hfa6e2cd_0  --> 1.4.14-py36hfa6e2cd_0
    pip:                18.1-py37_0            --> 18.1-py36_0
    pycosat:            0.6.3-py37hfa6e2cd_0   --> 0.6.3-py36hfa6e2cd_0
    pycparser:          2.19-py37_0            --> 2.19-py36_0
    pyopenssl:          18.0.0-py37_0          --> 18.0.0-py36_0
    pysocks:            1.6.8-py37_0           --> 1.6.8-py36_0
    pywin32:            223-py37hfa6e2cd_1     --> 223-py36hfa6e2cd_1
    requests:           2.20.1-py37_0          --> 2.20.1-py36_0
    ruamel_yaml:        0.15.46-py37hfa6e2cd_0 --> 0.15.46-py36hfa6e2cd_0
    setuptools:         40.6.2-py37_0          --> 40.6.2-py36_0
    six:                1.11.0-py37_1          --> 1.11.0-py36_1
    urllib3:            1.23-py37_0            --> 1.23-py36_0
    wheel:              0.32.3-py37_0          --> 0.32.3-py36_0
    win_inet_pton:      1.0.1-py37_1           --> 1.0.1-py36_1
    wincertstore:       0.2-py37_0             --> 0.2-py36h7fe50ca_0

The following packages will be DOWNGRADED:

    cryptography:       2.4.1-py37h7a1dbc1_0   --> 2.3.1-py36h74b6da3_0
    openssl:            1.1.1a-he774522_0      --> 1.0.2p-hfa6e2cd_0
    python:             3.7.1-he44a216_5       --> 3.6.7-h33f27b4_1

Proceed ([y]/n)? y


Downloading and Extracting Packages
certifi-2018.10.15   | 138 KB    | ############################################################################ | 100%
python-dateutil-2.7. | 276 KB    | ############################################################################ | 100%
jupyter_core-4.4.0   | 85 KB     | ############################################################################ | 100%
ruamel_yaml-0.15.46  | 262 KB    | ############################################################################ | 100%
icu-58.2             | 21.9 MB   | ############################################################################ | 100%
pyqt-5.9.2           | 4.2 MB    | ############################################################################ | 100%
pyyaml-3.13          | 148 KB    | ############################################################################ | 100%
pytz-2018.7          | 260 KB    | ############################################################################ | 100%
jpeg-9b              | 313 KB    | ############################################################################ | 100%
pycparser-2.19       | 174 KB    | ############################################################################ | 100%
sip-4.19.8           | 282 KB    | ############################################################################ | 100%
clyent-1.2.2         | 18 KB     | ############################################################################ | 100%
pillow-5.3.0         | 667 KB    | ############################################################################ | 100%
pycosat-0.6.3        | 98 KB     | ############################################################################ | 100%
conda-4.5.11         | 1.0 MB    | ############################################################################ | 100%
freetype-2.9.1       | 470 KB    | ############################################################################ | 100%
traitlets-4.3.2      | 131 KB    | ############################################################################ | 100%
psutil-5.4.8         | 333 KB    | ############################################################################ | 100%
asn1crypto-0.24.0    | 155 KB    | ############################################################################ | 100%
six-1.11.0           | 21 KB     | ############################################################################ | 100%
wheel-0.32.3         | 53 KB     | ############################################################################ | 100%
idna-2.7             | 132 KB    | ############################################################################ | 100%
chardet-3.0.4        | 210 KB    | ############################################################################ | 100%
pyopenssl-18.0.0     | 83 KB     | ############################################################################ | 100%
pywin32-223          | 9.3 MB    | ############################################################################ | 100%
libpng-1.6.35        | 589 KB    | ############################################################################ | 100%
qtpy-1.5.2           | 53 KB     | ############################################################################ | 100%
qt-5.9.6             | 93.9 MB   | ############################################################################ | 100%
sqlite-3.25.3        | 937 KB    | ############################################################################ | 100%
ipython_genutils-0.2 | 39 KB     | ############################################################################ | 100%
wincertstore-0.2     | 13 KB     | ############################################################################ | 100%
cffi-1.11.5          | 213 KB    | ############################################################################ | 100%
olefile-0.46         | 49 KB     | ############################################################################ | 100%
tk-8.6.8             | 3.8 MB    | ############################################################################ | 100%
pysocks-1.6.8        | 23 KB     | ############################################################################ | 100%
jsonschema-2.6.0     | 104 KB    | ############################################################################ | 100%
zlib-1.2.11          | 128 KB    | ############################################################################ | 100%
libtiff-4.0.9        | 829 KB    | ############################################################################ | 100%
decorator-4.3.0      | 16 KB     | ############################################################################ | 100%
pip-18.1             | 1.8 MB    | ############################################################################ | 100%
anaconda-client-1.7. | 200 KB    | ############################################################################ | 100%
menuinst-1.4.14      | 92 KB     | ############################################################################ | 100%
cryptography-2.3.1   | 509 KB    | ############################################################################ | 100%
anaconda-navigator-1 | 4.7 MB    | ############################################################################ | 100%
win_inet_pton-1.0.1  | 6 KB      | ############################################################################ | 100%
setuptools-40.6.2    | 646 KB    | ############################################################################ | 100%
requests-2.20.1      | 85 KB     | ############################################################################ | 100%
python-3.6.7         | 20.9 MB   | ############################################################################ | 100%
urllib3-1.23         | 152 KB    | ############################################################################ | 100%
nbformat-4.4.0       | 157 KB    | ############################################################################ | 100%
Preparing transaction: done
Verifying transaction: done
Executing transaction: \ menuinst Exception
Traceback (most recent call last):
  File "C:\Users\xx\Anaconda\lib\site-packages\conda\gateways\disk\create.py", line 206, in make_menu
    import menuinst
  File "C:\Users\xx\Anaconda\lib\site-packages\menuinst\__init__.py", line 23, in <module>
    from .win32 import Menu, ShortCut
  File "C:\Users\xx\Anaconda\lib\site-packages\menuinst\win32.py", line 19, in <module>
    from .winshortcut import create_shortcut
ModuleNotFoundError: No module named 'menuinst.winshortcudone



(base) C:\Users\xx>pip install tensorflow


(base) C:\Users\xx>pip install tensorflow
Collecting tensorflow
  Downloading https://files.pythonhosted.org/packages/05/cd/c171d2e33c0192b04560ce864c26eba83fed888fe5cd9ded661b2702f2ae/tensorflow-1.12.0-cp36-cp36m-win_amd64.whl (45.9MB)
    100% |████████████████████████████████| 45.9MB 672kB/s
Collecting grpcio>=1.8.6 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/2f/bc/671ce1e13032cfaf6d4d8901019d376f8ce7f18ee046435bf18ee5782630/grpcio-1.17.0-cp36-cp36m-win_amd64.whl (1.5MB)
    100% |████████████████████████████████| 1.5MB 2.6MB/s
Collecting keras-applications>=1.0.6 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/3f/c4/2ff40221029f7098d58f8d7fb99b97e8100f3293f9856f0fb5834bef100b/Keras_Applications-1.0.6-py2.py3-none-any.whl (44kB)
    100% |████████████████████████████████| 51kB 4.2MB/s
Collecting astor>=0.6.0 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/35/6b/11530768cac581a12952a2aad00e1526b89d242d0b9f59534ef6e6a1752f/astor-0.7.1-py2.py3-none-any.whl
Collecting protobuf>=3.6.1 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/e8/df/d606d07cff0fc8d22abcc54006c0247002d11a7f2d218eb008d48e76851d/protobuf-3.6.1-cp36-cp36m-win_amd64.whl (1.1MB)
    100% |████████████████████████████████| 1.1MB 2.2MB/s
Collecting tensorboard<1.13.0,>=1.12.0 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/e0/d0/65fe48383146199f16dbd5999ef226b87bce63ad5cd73c840cf722637969/tensorboard-1.12.0-py3-none-any.whl (3.0MB)
    100% |████████████████████████████████| 3.1MB 2.7MB/s
Collecting gast>=0.2.0 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/5c/78/ff794fcae2ce8aa6323e789d1f8b3b7765f601e7702726f430e814822b96/gast-0.2.0.tar.gz
Collecting numpy>=1.13.3 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/51/70/7096a735b27359dbc0c380b23b9c9bd05fea62233f95849c43a6b02c5f40/numpy-1.15.4-cp36-none-win_amd64.whl (13.5MB)
    100% |████████████████████████████████| 13.5MB 2.2MB/s
Collecting keras-preprocessing>=1.0.5 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/fc/94/74e0fa783d3fc07e41715973435dd051ca89c550881b3454233c39c73e69/Keras_Preprocessing-1.0.5-py2.py3-none-any.whl
Collecting termcolor>=1.1.0 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/8a/48/a76be51647d0eb9f10e2a4511bf3ffb8cc1e6b14e9e4fab46173aa79f981/termcolor-1.1.0.tar.gz
Requirement already satisfied: wheel>=0.26 in c:\users\xx\anaconda\lib\site-packages (from tensorflow) (0.32.3)
Collecting absl-py>=0.1.6 (from tensorflow)
  Downloading https://files.pythonhosted.org/packages/0c/63/f505d2d4c21db849cf80bad517f0065a30be6b006b0a5637f1b95584a305/absl-py-0.6.1.tar.gz (94kB)
    100% |████████████████████████████████| 102kB 4.1MB/s
Requirement already satisfied: six>=1.10.0 in c:\users\xx\anaconda\lib\site-packages (from tensorflow) (1.11.0)
Collecting h5py (from keras-applications>=1.0.6->tensorflow)
  Downloading https://files.pythonhosted.org/packages/12/6c/00c38c5ce9322f1cc421d93217c44739646a106c61859622eccc297a5c05/h5py-2.8.0-cp36-cp36m-win_amd64.whl (2.3MB)
    100% |████████████████████████████████| 2.3MB 3.3MB/s
Requirement already satisfied: setuptools in c:\users\xx\anaconda\lib\site-packages (from protobuf>=3.6.1->tensorflow) (40.6.2)
Collecting werkzeug>=0.11.10 (from tensorboard<1.13.0,>=1.12.0->tensorflow)
  Downloading https://files.pythonhosted.org/packages/20/c4/12e3e56473e52375aa29c4764e70d1b8f3efa6682bef8d0aae04fe335243/Werkzeug-0.14.1-py2.py3-none-any.whl (322kB)
    100% |████████████████████████████████| 327kB 3.8MB/s
Collecting markdown>=2.6.8 (from tensorboard<1.13.0,>=1.12.0->tensorflow)
  Downloading https://files.pythonhosted.org/packages/7a/6b/5600647404ba15545ec37d2f7f58844d690baf2f81f3a60b862e48f29287/Markdown-3.0.1-py2.py3-none-any.whl (89kB)
    100% |████████████████████████████████| 92kB 3.0MB/s
Building wheels for collected packages: gast, termcolor, absl-py
  Running setup.py bdist_wheel for gast ... done
  Stored in directory: C:\Users\xx\AppData\Local\pip\Cache\wheels\9a\1f\0e\3cde98113222b853e98fc0a8e9924480a3e25f1b4008cedb4f
  Running setup.py bdist_wheel for termcolor ... done
  Stored in directory: C:\Users\xx\AppData\Local\pip\Cache\wheels\7c\06\54\bc84598ba1daf8f970247f550b175aaaee85f68b4b0c5ab2c6
  Running setup.py bdist_wheel for absl-py ... done
  Stored in directory: C:\Users\xx\AppData\Local\pip\Cache\wheels\18\ea\5e\e36e1b8739e78cd2eba0a08fdc602c2b16a4b263912af8cb64
Successfully built gast termcolor absl-py
Installing collected packages: grpcio, numpy, h5py, keras-applications, astor, protobuf, werkzeug, markdown, tensorboard, gast, keras-preprocessing, termcolor, absl-py, tensorflow
