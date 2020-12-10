# ndi-python
NewTek NDI Python wrapper

## Setup
Donwload and install [NDI SDK](https://ndi.tv/sdk/).
## Clone and build
```
git clone https://github.com/akarak/ndi-python.git

cd ndi-python
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt

mkdir build
cd build
cmake -A x64 ..
cmake --build . --config Release
```
After build copy binary from `.\Release\NDIlib.cp39-win_amd64.pyd` and NDI binary from `%NDI_SDK_DIR%\Bin\x64` to execute directory.  
Enjoy!  

## License
ndi-python is MIT License  
NDI follows NDI's license