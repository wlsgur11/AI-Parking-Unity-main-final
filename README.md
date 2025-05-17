# final_assignment_pnu
 부산대학교 졸업과제 강화학습 자율주차

- 강화학습
- ppo알고리즘

requirements
```
unity= ??
MLAgents= 2.0.1
pytorch= 1.10.x
numpy= 1.23
```

```
conda create -n <venv name> python=3.8
conda activate <venv name>
pip install mlagents
```

This can be different for your system depending on which platform you are, use the PyTorch website to create the install command for you. In my case (Windows/Nvidia) this was:

conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
Verify the installation by trying the command:

mlagents-learn
