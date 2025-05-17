# final_assignment_pnu
 부산대학교 졸업과제 강화학습 자율주차

- 강화학습
- ppo알고리즘


requirements
```
conda= ?
unity= ??
MLAgents= 2.0.1
pytorch= 1.10.x
numpy= 1.23
```

아래 명령어를 입력하여 가상환경 생성 후 mlagent 설치(Anaconda 사용)
```
conda create -n <venv name> python=3.8
conda activate <venv name>
pip install mlagents
```

사용하시는 플랫폼에 따라 시스템마다 다를 수 있습니다. PyTorch 웹사이트를 사용하여 사용자에게 맞는 설치 명령어를 생성하세요. 팀원의 컴퓨터의 경우(Windows/Nvidia)에는 다음과 같았습니다:
```
conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
```

강화 학습 시작하기

```
mlagents-learn
```
