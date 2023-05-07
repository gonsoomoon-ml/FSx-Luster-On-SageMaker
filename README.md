# FSx for Luster 를 이용한 SageMaker 모델 훈련 워크샵

# 1. 환결 설정
아래를 클릭하여 VPC, FSx for Luster 의 기본 환경 설정을 하세요.
- [기본 인프라 환경 설정, VPC, SageMaker Notebook 및 FSx for Luster ](0_setup_environment/1.VPC_SM_Notebook/README.md)

# 2. 노트북 개용 (1_lab_1_xgboost 폴더)
- 1.1.SageMaker-Local-Training.ipynb
    - 로컬머신에서 로컬 모드 및 클라우드 모드로 모델 훈련
- 1.2.SageMaker-Training-Warm-Pool
    - 클라우드 모드에서 Warm Pool 로 모델 훈련
- 2.0.SageMaker-Training-S3-VPC.ipynb
    - VPC 모드로 S3 의 데이터 사용하여 모델 훈련
- 2.1.SageMaker-Training-FSx-Luster.ipynb
    - VPC 모드로 FSx for Luster 데이터 사용하여 모델 훈련
    
    
# A. Reference
- [로컬 머신에서 Visual Studio Code 를 사용하여 SageMaker 훈련 코드 작성 하기](https://github.com/gonsoomoon-ml/Self-Study-On-SageMaker/blob/main/Environment/README-Local-VS-Code.md)
- SageMaker Warm Pool 기능을 사용하여 학습 합니다.
    - [Train Using SageMaker Managed Warm Pools](https://docs.aws.amazon.com/sagemaker/latest/dg/train-warm-pools.html)
