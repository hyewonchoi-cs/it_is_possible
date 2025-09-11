# 
2025학년도 졸업프로젝트를 위해 운영되는 36조 "이게되네"팀 프로젝트 저장소입니다.  
본 프로젝트는 AI 기반 웹/앱 서비스 개발을 목표로 하며 데이터 분석과 협업 개발을 통해 완성도를 높이고자 합니다.

# On-Device AI Security Project

프로젝트 개요

본 프로젝트는 온디바이스 AI 기반 보안 앱 서비스 개발을 목표로 합니다.  
개인정보 유출 및 피싱과 같은 사회적 문제를 해결하기 위해, 민감한 데이터를 클라우드에 전송하지 않고 사용자 기기 내부(On-Device)에서  
실시간으로 위협을 탐지하고 대응하는 AI 서비스를 구현합니다.  

🛠️ 기술 스택
- AI/모델: 
  - 온디바이스에서 동작 가능한 경량화 언어 모델(예: Phi-3-mini, Mistral 등 후보) 
  - 음성 인식(STT) 모델(Whisper-small 등 경량 버전) 
  - 기본적인 규칙 기반 탐지 로직 병행

- **온디바이스 추론**: 
  - 모바일/웹 환경에 맞춘 추론 프레임워크 
  - (예: TensorFlow Lite, ONNX Runtime, Core ML 중 선택 예정)

- **백엔드(보조 역할)**: 
  - 퍼블릭 클라우드(AWS, GCP, Azure 등) 활용  
  - 모델/룰 업데이트 배포, 익명화된 탐지 통계 관리, 간단한 API 제공

- **프론트엔드/앱**: 
  - 모바일 앱(Android Kotlin / iOS Swift) 개발 
  - 웹 브라우저 확장 프로그램(Chrome/Firefox Extension) 후보



Innovating at the intersection of Cloud ☁️, AI 🤖, and Real-World Solutions 🚀

(Version 0.9 Draft)
