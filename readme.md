AMD 5800X3D


AMD RX7800XT


SYSTEM ENDEVOUR


OS Kernel 6.6.4-arch1-1


git clone https://github.com/lllyasviel/Fooocus.git
cd Fooocus
python3 -m venv fooocus_env
source fooocus_env/bin/activate
pip install -r requirements_versions.txt
pip uninstall torch torchvision torchaudio torchtext functorch xformers 
NO->pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/rocm5.6
pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/rocm5.7
