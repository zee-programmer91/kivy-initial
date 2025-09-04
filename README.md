# kivy-initial

## Setup Environment

### Virtual Environment

```shell
python -m venv kivy_venv
kivy_venv\Scripts\activate
```

```bash
source kivy_venv/Scripts/activate (Windows bash terminal)
source kivy_venv/bin/activate (Linux/macOS)
```

### Install Dependencies

```shell
python -m pip install "kivy[full]"
```

### Note

When using Raspberry Pi OS Lite or similar Linux-based headless systems, it may be necessary to install additional dependencies to ensure Kivy functions properly.

For instance, on Raspberry Pi OS Lite, you will be required to install the following dependencies:

```bash
apt-get install libgl1-mesa-glx libgles2-mesa libegl1-mesa libmtdev1
