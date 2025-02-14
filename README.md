# Localization Practice!  
실습환경: ubuntu 20.04 및 ros-noetic  
**실습하실 분들은 위의 환경 구현을 권장드립니다.  
현재 이미 다른 버전의 우분투나 ros를 사용중이시라 위의 환경 구현이 어렵다면 Docker를 이용해 가상환경 구축을 추천드립니다.**   

## 1️⃣ 필수 패키지 설치
```bash
sudo apt update && sudo apt install -y git-lfs  
git lfs install
sudo apt install ros-noetic-ublox
```

## 2️⃣ 프로젝트 클론 및 의존성 설치
```bash
cd /catkin_ws/src  
git clone https://github.com/n-submarine/Localization_practice.git     
cd ..    
catkin_make  
source devel/setup.bash
cd src/Localization_practice
pip install -r requirements.txt
```
