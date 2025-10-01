# LunarLander PPO (Gymnasium + Stable-Baselines3)

This notebook trains a PPO agent on **LunarLander-v3** using parallel envs + VecNormalize, logs to TensorBoard, and records a short demo MP4 (best-of-N seeds). Optional reward shaping nudges the policy to land between the flags.

## How to run (Colab)
1. Open `notebook_colab.ipynb` in Google Colab.
2. Run cells top → bottom (setup → train → eval → video).  
3. MP4 saves under `./logs/<run>/video/…`.

## Local quickstart
```bash
python -m venv venv && source venv/bin/activate   # (Windows: venv\Scripts\activate)
pip install -r requirements.txt
# open the notebook in Jupyter/VSCode and run
