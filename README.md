# Voice Synthesis for Maho from Steins;Gate 0

## Requirements

* [Anaconda](https://www.anaconda.com/)
* NVIDIA GPU with CUDA (Optional, but recommended)

## Initial Setup

```bash
git clone --recursive https://github.com/HumanGamer/VoiceSynthesisMaho
cd VoiceSynthesisMaho
conda create -n maho_ai python=3.7
conda activate maho_ai
conda install cudatoolkit=10.0
pip install tensorflow-gpu==1.15 gdown
```

## When re-using

```bash
conda activate maho_ai
```

## Usage

```bash
python synthesis.py
```
