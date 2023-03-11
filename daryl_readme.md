# visual_chatgpt

# create a new env
python3 -m venv visual_chatgpt_1 --system-site-packages
source visual_chatgpt_1/bin/activate

#  prepare the basic environments
pip install -r requirement.txt

# download the visual foundation models
bash download.sh

# prepare your private openAI private key
export OPENAI_API_KEY={Your_Private_Openai_Key}

# create a folder to save images
mkdir ./image

# Start Visual ChatGPT !
python visual_chatgpt.py