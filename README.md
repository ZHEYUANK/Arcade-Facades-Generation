# Arcade-Facades-Generation

![image](https://github.com/ZHEYUANK/Arcade-Facades-Generation/blob/main/Title%20Image.png)

Initial paper：[Advancing Urban Renewal: An Automated Approach to Generating Historical Arcade Facades with Stable Diffusion Models](https://arxiv.org/abs/2311.11590)

In urban renewal, it's essential to preserve the architectural style of historical districts. Traditional design methods, which involve in-depth studies of city history and culture, are time-consuming and often subjective. Although data-driven design methods exist, they require complex, labor-intensive dataset construction and often do not produce high-quality images. Recent research shows that stable diffusion models have potential in generating high-fidelity images based on prompts, but their application in renewing urban historical districts is still limited. Addressing these challenges, our study introduces a framework that combines stable diffusion models with expert system-based digital generative techniques to automatically generate architectural facades with specific styles from professional prompts. We developed a dataset of traditional arcade building facades, trained multiple Low-Rank Adaptation (LoRA) models, and integrated ControlNet models to enhance control over the facade generation. Quantitative evaluation and practical application tests have proven that our approach not only provides valuable references for designers and prompt engineers but also contributes to the preservation of traditional architectural heritage and the renewal of urban historical districts.

# Install

1. Clone this repository and navigate to Quantitative_Evaluation folder
```bash
git clone https://github.com/ZHEYUANK/Arcade-Facades-Generation.git

cd Quantitative_Evaluation
```

2. Install Package
 ```bash
 # Create a new conda environment
 conda create -n pytorch python=3.8
 
 # Activate the newly created environment
 conda activate pytorch
 
 # Install PyTorch, torchvision, torchaudio, and CUDA toolkit
 conda install pytorch==2.1.2 torchvision==0.16.2 torchaudio==2.1.2 cudatoolkit=11.2 -c pytorch
 
 # Install additional packages
 pip install -r requirements.txt
