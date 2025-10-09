# 2025B2PW-cabinetry-tutorial
Hands-on session for evaluation of systematic uncertainties in profile likelyhood fits with cabinetry and pyhf.

# link to this repository
<img width="450" height="450" alt="изображение" src="https://github.com/user-attachments/assets/d747a305-3d13-4a4d-8b8b-7dd73c6bf8c8" />


# To start:

Clone this repository:
```
git clone https://github.com/igartiy/2025B2PW-cabinetry-tutorial.git

cd 2025B2PW-cabinetry-tutorial
```

Make a virtual environment and install the prerequisites:
```
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -U pip
python3 -m pip install -r requirements.txt
```

You can start the notebook:

```
 python -m notebook

 # optional (if on remote cluster)
 python -m notebook --no-browser --port {port_number}
```

