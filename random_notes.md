```bash
python3.11 -m venv venv
pip install langflow --pre --force-reinstall
deactivate
./configure --enable-optimizations
make -j$(sysctl -n hw.ncpu)
sudo make install
python3.10 --version
rm -rf venv`

clear
ctrl +U
ctrl +C

pip list

curl -LsSf https://astral.sh/uv/install.sh | sh
source $HOME/.local/bin/env
uv --version
```