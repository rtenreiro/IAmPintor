Repositorio del libro La Inteligencia Artifical con la mirada de un pintor
INSTALAR y ENTORNO VIRTUAL

A. Descargar e Instalar Python
1. Descargar Python 3.9:
   - Ve al sitio web oficial Python: https://www.python.org/downloads/release/python-3913/
   - Descarga el instalador de Python 3.9.13 para Windows.
2. Instalar Python:
   - Ejecuta el instalador descargado.
   - Asegúrate de seleccionar Add Python to PATH antes de hacer clic en Install Now.
   - Sigue las instrucciones para completar la instalación.
     
B. Configurar un Entorno Virtual
1. Abrir PowerShell o Terminal:
  	 - Presiona `Win + X` y selecciona Windows PowerShell.
2. Crear el Entorno virtual:
python -m venv tensorflow-env
3. Activar Entorno Virtual:
    	tensorflow-env\Scripts\activate
   
C: Instalar TensorFlow, Jupyter notebook y Otras Bibliotecas
1. Instalar TensorFlow:  
pip install tensorflow==2.6.0
pip install absl-py==0.10 flatbuffers==1.12.0 h5py==3.1.0 keras==2.6 numpy==1.19.5 typing-extensions==3.7.4.3
2. Instalar Jupyter:
pip install jupyter
3. Instalar Bibliotecas Adicionales:
pip install matplotlib==3.4.3
pip install tensorflow_hub==0.12.0
pip install validators

D: Ejecutar los programas
- Abre Terminal y sitúate en el directorio donde tienes las aplicaciones:
   	cd tensorflow-env   
- Activa el entorno virtual:
   	tensorflow-env\Scripts\activate
   - Abre jupyter notebook en el entorno virtual:
   	jupyter notebook  
   - En el notebook ejecuta el programa que te interese:
 	RT_Style_Transfer_Eager.ipynb		
    
Se adjunta contenido requirements.txt
absl-py==0.10.0
anyio==3.7.1
argon2-cffi==23.1.0
argon2-cffi-bindings==21.2.0
arrow==1.3.0
asttokens==2.4.1
astunparse==1.6.3
attrs==23.2.0
Babel==2.15.0
beautifulsoup4==4.12.3
bleach==6.1.0
certifi==2024.2.2
cffi==1.16.0
charset-normalizer==3.3.2
clang==5.0
colorama==0.4.6
comm==0.2.2
cycler==0.12.1
debugpy==1.8.1
decorator==5.1.1
defusedxml==0.7.1
entrypoints==0.4
exceptiongroup==1.2.1
executing==2.0.1
fastjsonschema==2.19.1
flatbuffers==1.12
fonttools==4.52.4
fqdn==1.5.1
gast==0.4.0
google-pasta==0.2.0
grpcio==1.64.0
h11==0.14.0
h5py==3.1.0
httpcore==1.0.5
httpx==0.27.0
idna==3.7
importlib_metadata==7.1.0
importlib_resources==6.4.0
ipykernel==6.29.4
ipython==8.18.1
ipython-genutils==0.2.0
ipywidgets==8.1.3
isoduration==20.11.0
jedi==0.19.1
Jinja2==3.1.4
json5==0.9.25
jsonpointer==2.4
jsonschema==4.22.0
jsonschema-specifications==2023.12.1
jupyter-console==6.6.3
jupyter-events==0.10.0
jupyter-lsp==2.2.5
jupyter-server==1.24.0
jupyter_client==7.4.9
jupyter_core==5.7.2
jupyter_server_terminals==0.5.3
jupyterlab==3.4.8
jupyterlab_pygments==0.3.0
jupyterlab_server==2.27.2
jupyterlab_widgets==3.0.11
keras==2.6.0
Keras-Preprocessing==1.1.2
kiwisolver==1.4.5
libclang==18.1.1
Markdown==3.6
markdown-it-py==3.0.0
MarkupSafe==2.1.5
matplotlib==3.4.3
matplotlib-inline==0.1.7
mdurl==0.1.2
mistune==3.0.2
namex==0.0.8
nbclassic==1.1.0
nbclient==0.10.0
nbconvert==7.16.4
nbformat==5.10.4
nest-asyncio==1.6.0
notebook==6.5.7
notebook_shim==0.2.4
numpy==1.19.5
opencv-python==4.5.3.56
opt-einsum==3.3.0
overrides==7.7.0
packaging==24.0
pandocfilters==1.5.1
parso==0.8.4
pillow==10.3.0
platformdirs==4.2.2
prometheus_client==0.20.0
prompt_toolkit==3.0.45
protobuf==3.20.3
psutil==5.9.8
pure-eval==0.2.2
pycparser==2.22
Pygments==2.18.0
pyparsing==3.1.2
python-dateutil==2.9.0.post0
python-json-logger==2.0.7
pywin32==306
pywinpty==2.0.13
PyYAML==6.0.1
pyzmq==26.0.3
qtconsole==5.5.2
QtPy==2.4.1
referencing==0.35.1
requests==2.32.3
rfc3339-validator==0.1.4
rfc3986-validator==0.1.1
rich==13.7.1
rpds-py==0.18.1
Send2Trash==1.8.3
six==1.15.0
sniffio==1.3.1
soupsieve==2.5
stack-data==0.6.3
tensorboard==2.16.2
tensorboard-data-server==0.7.2
tensorflow==2.6.0
tensorflow-estimator==2.6.0
tensorflow-hub==0.12.0
tensorflow-io-gcs-filesystem==0.31.0
termcolor==1.1.0
terminado==0.18.1
tinycss2==1.3.0
tomli==2.0.1
tornado==6.4
traitlets==5.14.3
types-python-dateutil==2.9.0.20240316
typing-extensions==3.7.4.3
uri-template==1.3.0
urllib3==2.2.1
validators==0.28.3
wcwidth==0.2.13
webcolors==1.13
webencodings==0.5.1
websocket-client==1.8.0
Werkzeug==3.0.3
widgetsnbextension==4.0.11
wrapt==1.12.1
zipp==3.19.0

