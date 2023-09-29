# example-using-other-chatbots
Follwong this step we can isntall llama-2 and use it localy

conda create -n textgen python=3.10.9
conda activate textgen
install pytorch: pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu117
git clone https://github.com/oobabooga/text-generation-webui
cd text-generation-webui
pip install -r requirements.txt
python server.py
# download model
# refresh model list
# load model
# switch to chat mode
