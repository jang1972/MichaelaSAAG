## MichaelaSAAG (Société anonyme Aktiengesellschaft)
MichaelaSAAG는 19명의 머신러닝 기반 투자자와 경쟁하는 30년 기간의 TUI(터미널 사용자 인터페이스) 기반 가상 주식 시장 시뮬레이션 게임입니다.
## 주요 기능

* 금융 상품 지원: 국채, 예금, 적금, 주식, ETF, FX(외환), 선물거래를 지원합니다.
* AI 경쟁자: 전통적인 머신러닝 알고리즘으로 학습된 19명의 개인화된 경쟁자가 플레이어와 함께 시장에 참여합니다.
* 구현 특징: 모델 학습 과정에서 Jupyter Notebook 시리즈를 철저히 배제하고 순수 .py 스크립트만을 사용했습니다. 학습된 모델은 ONNX 포맷으로 변환되어 Golang 런타임 환경에서 추론을 수행합니다.
* 사용 언어: 한국어 환경을 최우선으로 고려하여 개발되었습니다.

## 시스템 요구사항 및 호환성

* 터미널 크기: 최소 너비 100자 이상 확보가 가능한 터미널 환경이 필요합니다.
* 하드웨어 아키텍처: amd64-v3 마이크로아키텍처 레벨 이상을 지원하는 CPU가 필요합니다.
* 시뮬레이션 타임라인: 1995년부터 2025년까지의 기간을 시뮬레이션하는 것을 목표로 합니다.

## 프로젝트 현황 및 라이선스

* 개발 상태: 현재 프로토타이핑 단계로 코드베이스는 비공개 상태입니다.
* 라이선스: 별도의 라이선스 파일은 부재하나, 향후 독점적 소스 공개 프리웨어 라이선스인 자작 Modern Defensive License를 적용할 예정입니다.
* 개발 도구: 코드 생성에 Gemini 3.6 Flash 및 Gemini 3.1 Pro가 활용되었으며, 아스키 아트는 Nano Banana 2 모델을 통해 생성되었습니다.

------------------------------
## English Description
MichaelaSAAG is a 30-year virtual stock market simulation game based on a Terminal User Interface (TUI), in which the player competes against 19 machine learning-driven investors.
## Key Features

* Financial Instruments: Supports government bonds, time deposits, savings accounts, stocks, ETFs, FX, and futures trading.
* AI Competitors: Features 19 distinct competitors trained using traditional machine learning algorithms to simulate market competition.
* Technical Architecture: Model training completely excludes the Jupyter ecosystem, relying strictly on .py scripts. Trained models are converted to the ONNX format and executed within a Golang runtime environment.
* Language Support: Localization prioritizes the Korean language.

## System Requirements & Compatibility

* Terminal Dimensions: Requires a terminal window with a minimum width of 100 characters.
* Hardware Architecture: Requires a CPU supporting the amd64-v3 microarchitecture level or higher.
* Simulation Timeline: Targeted to cover the historical and modern market period from 1995 to 2025.

## Project Status & Licensing

* Current Status: The repository is currently private as it is in the prototyping stage.
* Licensing: No standard license file is present. The project plans to adopt a custom proprietary source-available freeware license named Modern Defensive License.
* Development Toolkit: Code generation was assisted by Gemini 3.6 Flash and Gemini 3.1 Pro. ASCII art assets were generated using the Nano Banana 2 model.

