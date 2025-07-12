# 🏫 AARRR 프레임워크 기반 온라인 교육 플랫폼 구독서비스 개선 전략
<div align="center">
  
|#1|#2|
|:---:|:---:|
|![project_02_보고서_1](https://github.com/user-attachments/assets/f52c9df5-a38f-4486-b02a-97075202264d)|![project_02_보고서_2](https://github.com/user-attachments/assets/d8b89aac-847a-4828-af24-50d365a0dbf5)|


</div>

## ✅ Key Project Details
- AARRR 프레임워크를 기반으로 온라인 교육 플랫폼 구독 서비스의 개선 전략을 수립 프로젝트
- 사용자 로그 데이터를 분석한 결과, 무료 체험 기간 동안의 콘텐츠 이용 경험이 유료 결제 전환에 큰 영향을 미치는 것으로 확인
- 이에, 사용자가 원하는 강의 커리큘럼을 쉽게 찾을 수 있도록 돕는 ‘학습 루트 가이드 맵’을 도입하는 A/B 테스트를 설계
- A/B 테스트의 목표는 기존 대비 콘텐츠 완강률을 5%p 이상 향상시키는 것
- 이 프로젝트는 무료 체험 기간 동안 사용자 경험을 개선하고, 궁극적으로 유료 구독 전환율과 서비스 리텐션을 높이는 것을 목표로 함

<br />

## 📖 Table of Contents
- [📨 Project Overview](#📨-project-overview)  
- [🎯 목표](#🎯-목표-objective)  
- [🧪 분석 프로세스](#🧪-분석-프로세스)  
- [📊 사용 데이터 (Dataset)](#📊-사용-데이터-dataset)  
- [🔍 주요 분석 결과](#🔍-주요-분석-결과)  
- [👥 유저 세그먼트 유형](#👥-유저-세그먼트-유형)  
- [💡 개선 전략 제안](#💡-개선-전략-제안)  
- [🧪 A/B 테스트 요약](#🧪-A/B-테스트-요약)  
- [📁 프로젝트 구조](#📁-프로젝트-구조-directory-structure)
- [🛠️ Development Environment and Tools](#🛠️-Development-Environment-and-Tools)
- [🍀 Team Members](#🍀-Team-Members)  

<br />

## 📨 Project Overview
본 프로젝트는 온라인 교육 플랫폼의 구독 서비스 개선을 목표로, 무료 체험 기간 동안의 사용자 경험을 향상시키는 데 중점을 두었습니다. 사용자 행동 데이터 분석 결과, 개인화된 강의 커리큘럼을 찾는 데 어려움을 겪는 것이 낮은 완강률과 유료 구독 전환율 감소의 원인으로 파악되었습니다.

이를 해결하기 위해, 사용자가 자신에게 맞는 강의를 쉽게 탐색하고 선택할 수 있도록 돕는 '학습 루트 가이드 맵'을 도입하는 A/B 테스트를 설계하고 실행했습니다. 목표는 기존 디자인 대비 완강률을 최소 5%p 이상 향상시키는 것입니다.

주요 활동으로는 클러스터링을 통한 사용자 세분화, 완강률 및 클릭률과 같은 핵심 성공 지표 정의, 그리고 무작위 사용자 그룹을 대상으로 한 달간의 실험 진행이 포함되었습니다. 이러한 접근 방식은 보다 체계적이고 개인화된 학습 경험을 제공함으로써 사용자 유지율과 유료 구독 전환율을 높이는 데 기여할 것으로 기대됩니다.

<br />

## 🎯 목표 (Objective)
- AARRR 프레임워크 기반으로 유저 행동 분석
- 무료 체험 이후 낮은 유료 전환율 문제 해결
- 유저 세그먼트를 나누고 이탈 원인을 진단
- A/B 테스트 설계를 통한 서비스 개선안 제안

## 🧪 분석 프로세스
- 로그 데이터 EDA 및 전처리
- AARRR 단계별 행동 분석 (획득 → 활성화 → 유지 → 수익 → 추천)
- 유저 행동 기반 클러스터링 (5개 유형)
- 이탈 유저 시퀀스 및 전환 유저 시퀀스 비교
- A/B 테스트 설계 및 가설 설정

## 🔍 주요 분석 결과
- 무료 체험 후 유료 전환율: 17.79%
- 많은 유저가 다양한 콘텐츠를 수강 시작하나 완강률 낮음
- 유저가 적절한 콘텐츠를 찾지 못하는 ‘콘텐츠 길치’ 현상 존재

## 👥 유저 세그먼트 유형
- 짧은 탐색 유저: 흥미 잃고 금방 이탈
- 반복 유저: 콘텐츠 여러 개 시작하지만 완강 없음
- 잠재적 충성 유저: 입문 콘텐츠 후 결제 안함
- 충성 유저: 꾸준한 학습과 높은 몰입도
- 탐색 실패자: 다양한 콘텐츠 탐색하지만 결국 이탈

## 💡 개선 전략 제안
- 학습 루트 가이드 맵 제공으로 콘텐츠 탐색 시간 단축
- 완강률 향상 → 전환율 증가를 목표로 A/B 테스트 설계
- 클러스터별 맞춤 UX 및 인센티브 전략 수립

## 🧪 A/B 테스트 요약
| 구분	| A안(기존안) |	B안(개선안) |
|:---:|:---:|:---:|
| 메인 페이지 | 인기 콘텐츠 5개 노출 |	학습 루트 가이드 맵 버튼 추가 |
| 주요 지표 |콘텐츠 완강률 | 완강률 + 가이드 맵 클릭률 |

<br />

## 📁 프로젝트 구조 (Directory Structure)
```
📄 README.md
📄 분석파일.ipynb
📄 원페이퍼_보고서.pdf
```

<br />

## 🛠️ Development Environment and Tools
- Data Analysis: 	<img src="https://img.shields.io/badge/python-%233776AB.svg?&style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/mysql-%234479A1.svg?&style=for-the-badge&logo=mysql&logoColor=white" />
- Data Visualization: 	<img src="https://img.shields.io/badge/python-%233776AB.svg?&style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/tableau-%23E97627.svg?&style=for-the-badge&logo=tableau&logoColor=white" />
- Collaboration Tools: <img src="https://img.shields.io/badge/discord-%237289DA.svg?&style=for-the-badge&logo=discord&logoColor=white" />	<img src="https://img.shields.io/badge/notion-%23000000.svg?&style=for-the-badge&logo=notion&logoColor=white" />

## 🍀 Team Members
#### 🐻 윤영서
#### 🦊 송지혜
#### 🐶 권정은

## ✈️ Project Duration
- 2025.04.07 - 2025.04.30

## ⛓️ Project Collaboration
- Google Colab을 통해 ipynb 파일로 code를 공유했습니다.
- Discord를 통해 일간화의를 진행하며 작업 순서와 진행 사항을 파악하였으며, Notion에 회의 내용을 기록했습니다. 
