# Voice Synthesis for Maho from Steins;Gate 0

## Requirements

* [Anaconda](https://www.anaconda.com/)
* NVIDIA GPU with CUDA (Optional, but recommended)

## Initial Setup

Run the following commands:

```bash
git clone --recursive https://github.com/HumanGamer/VoiceSynthesisMaho
cd VoiceSynthesisMaho
conda create -n maho_ai python=3.7
conda activate maho_ai
```

If you have an NVIDIA GPU run the following:

```bash
conda install cudatoolkit=10.0
pip install tensorflow-gpu==1.15 gdown
```

Otherwise run these:

```bash
pip install tensorflow==1.15 gdown
```

## When re-using

```bash
conda activate maho_ai
```

## Usage

```bash
python synthesis.py
```
