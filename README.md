# 👋 Hello, I'm Jungjae Lee

<p align="left">
  <a href="mailto:내이메일@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=Gmail&logoColor=white"/></a>
  <a href="https://www.notion.so/AI-Engineer-c7bd4b7cc1b882fda87681e2467fdf5a?source=copy_link"><img src="https://img.shields.io/badge/Portfolio-0078D4?style=flat-square&logo=Microsoft-SharePoint&logoColor=white"/></a>
  <a href="https://velog.io/@jeongjae/posts"><img src="https://img.shields.io/badge/Blog-11B48A?style=flat-square&logo=Velog&logoColor=white"/></a>
</p>

> **AI Engineer**
> Moving beyond simply utilizing models, I focus on understanding core principles to implement optimal AI systems tailored to real-world constraints. 
> Centered on Computer Vision, Robotics AI, and LLM Agents, I specialize in defining real-world problems from a data and model perspective, building production-ready End-to-End pipelines.

---

## 🌐 Korean Version (한국어 버전 보기)

<details>
<summary><b>🇰🇷 이곳을 클릭하면 한국어 소개가 펼쳐집니다 (Click to expand)</b></summary>
<br>

> 기술을 단순히 사용하는 데서 멈추지 않고, 원리를 이해해 문제에 맞는 AI 시스템으로 구현합니다.
> Computer Vision, Robotics AI, LLM Agent 프로젝트를 중심으로 실제 환경의 문제를 데이터와 모델 관점에서 정의하고, 동작하는 전체 개발 파이프라인을 구축하는 것에 집중하고 있습니다.

### 🎯 Core Strengths
* **Problem to AI** : 실제 환경에서 발생하는 제약(저조도, 오클루전 등)을 데이터와 모델 관점으로 재정의합니다.
* **Model to System** : 모델 구현을 넘어 데이터 전처리, 시스템 연동, DB 적재, 대시보드 시각화까지의 End-to-End 흐름을 고려합니다.

### 🚀 Main Projects
#### 1. RGB-IR Fusion 기반 Pose Estimation 모델
* **설명**: 저조도, 가림(Occlusion), 객체-배경 간 색상 유사성 문제를 해결하기 위한 멀티모달 Fusion 모델 설계
* **주요 성과**:
  * RGB Baseline 대비 End-to-End **mAP 0.638 → 0.932 개선**
  * False Positive **535 → 11 대폭 감소** 및 Keypoint Localization 안정성 확보
* **Keywords**: `PyTorch` `MobileNetV3` `RGB-IR Fusion` `AlphaPose`

#### 2. Aspect-Based Sentiment Analysis 기반 리뷰 분석 시스템
* **설명**: 리뷰 문맥에서 주요 속성(Aspect)을 동적으로 추출하고 긍부정을 평가하는 Multi-Agent 기반 시스템 구축
* **주요 특징**:
  * Analyzer–Critic–Supervisor 구조의 **LangGraph Workflow** 구현 및 **LangSmith** 추적 적용
  * 분석 결과를 **SQLite DB**에 누적 적재하고 **Streamlit 대시보드**로 시각화 연동
* **Keywords**: `LangGraph` `LangChain` `SQLite` `Streamlit` `LLMOps`

#### 3. Vision 기반 자율주행 로봇 인식 및 경로 추정 시스템
* **설명**: RGB-D 카메라 중심 좌표와 Depth 정보를 결합하여 주행 좌표계 기반 위치 정보로 변환하는 시스템 설계
* **주요 성과**:
  * 내부 반복 주행 테스트 기준 **주행 성공률 90% 이상 개선**
  * **농업용 로봇 경진대회 대상(농림축산식품부장관상) 및 우수상(농촌진흥청장상) 수상** 🥇
* **Keywords**: `YOLOv5/v7` `RGB-D Camera` `OpenCV` `ROS` `Jetson` `Path Estimation`

### 📝 Paper Implementation (From Scratch)
* **ResNet Implementation**: 구조와 원리를 깊게 이해하기 위해 PyTorch 기반으로 `BasicBlock`, `Bottleneck`, `Skip Connection`을 직접 구현하고 Plain CNN과의 학습 안정성을 CIFAR-10 데이터셋으로 비교 분석 중입니다.

</details>

---

## 🎯 Core Strengths (English)

* **Problem to AI**: Redefining complex real-world challenges (e.g., low-light environments, occlusions) into structured data and model tasks.
* **Model to System**: Extending beyond model deployment to architect comprehensive AI solutions, incorporating data preprocessing, system integration, database architecture, and dashboard visualization.

---

## 🚀 Main Projects (English)

### 1. RGB-IR Fusion based Pose Estimation Model
* **Description**: Designed a multimodal fusion framework to overcome the vulnerability of RGB-only models in low-light, occluded, and low-contrast environments.
* **Key Results**:
  * Improved End-to-End performance with **mAP increasing from 0.638 to 0.932** compared to the RGB baseline.
  * Drastically reduced False Positives from **535 to 11**, ensuring robust keypoint localization stability.
* **Keywords**: `PyTorch` `MobileNetV3` `RGB-IR Fusion` `AlphaPose`

### 2. Aspect-Based Sentiment Analysis via LLM Agents
* **Description**: Built a Multi-Agent system that dynamically extracts product features (Aspects) from unstructured reviews and evaluates localized sentiment.
* **Key Points**:
  * Orchestrated a dynamic Multi-Agent architecture (Analyzer–Critic–Supervisor) using **LangGraph** and monitored data flows via **LangSmith**.
  * Persistent storage with **SQLite** to log transaction history and built an interactive analytical dashboard using **Streamlit**.
* **Keywords**: `LangGraph` `LangChain` `SQLite` `Streamlit` `LLMOps`

### 3. Vision-based Autonomous Robot Perception & Path Estimation System
* **Description**: Developed a robust navigation perception system that combines RGB-D bounding box tracking with depth heuristics to project target coordinates onto the robot's driving frame, overcoming traditional 2D LiDAR constraints.
* **Key Results**:
  * Enhanced field reliability, achieving an **over 90% increase in navigation success rate** under intensive closed-loop tests.
  * **Grand Prize (Minister of Agriculture, Food and Rural Affairs Award) 🥇** & **Excellence Prize (Administrator of Rural Development Administration Award) 🥈** at the Agricultural Robotics Competition.
* **Keywords**: `YOLOv5/v7` `RGB-D Camera` `OpenCV` `ROS` `Jetson` `Path Estimation`

---

## 📝 Paper Implementation (From Scratch)
* **ResNet Architecture**: Implementing `BasicBlock`, `Bottleneck`, and `Skip Connection` structural elements from scratch using PyTorch. Actively analyzing training stability and bottleneck dynamics on the CIFAR-10 dataset compared to standard Plain CNNs.

---

## 🛠️ Tech Stacks

### AI & Computer Vision
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white"/>
</p>

### LLM & Data/App Systems
<p align="left">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=LangChain&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=Streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=SQLite&logoColor=white"/>
</p>

---

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=I2J2J&show_icons=true&theme=vivid&hide_border=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=I2J2J&layout=compact&theme=vivid&hide_border=true" height="150" />
</p>
