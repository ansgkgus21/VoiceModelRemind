[마크다운 사용법 총정리](https://www.heropy.dev/p/B74sNE)
# 1. Instruction
번역과 동시에 내 목소리를 클론해 출력해주는 음성인식모델 
STT, 양방향 다국어 번역과 TTS+보이스클론
# 2. 개발 기간
2026.04.16 ~ 2026.04.30
# 3. 팀원 소개
| 이름 | 역할 |
|---|---|
| 박시영 | 프로젝트 총괄, 파이프라인 구축, 보이스클론 모델 담당, 회의록 및 figma 정리 |
| 박은희 | tts 모델 담당, 음성 데이터셋 수집 및 전처리 |
| 정재승 | stt 모델 담당, 프로젝트 방향성 제시 및 진행 |
| 문하현 | nlp 및 llm 기반 번역 모델 담당, 발표 및 ppt 제작 |
# 4. 주제 선정
- 기획 배경
<img width="634" height="396" alt="image" src="https://github.com/user-attachments/assets/761e3e45-bf18-4caf-a445-7628a601b042"/> <br>
- 국내 거주 외국인 수가 매년 꾸준히 증가하고 있음<br> 
- 특히 안산 다문화거리는 한국에서 외국인 거주 비율이 가장 높은 곳이고 안산시 전체의 외국인 주민 수도 전국 지자체 중 최고 수준<br>
-> 따라서 거주 외국인 수가 증가함에 따라 주변 상권의 손님들은 외국인이 많을 것이고 소통에 어려움을 겪는 소상공인도 분명히 있을 것이다 <br>

# 5. 주요 기능
- STT : 음성 → 텍스트 변환
- nlp 및 llm : 다국어 번역
- TTS : 기본 음성 생성
- VoiceClone : 참조 음성 기반 보이스클론 <br>
// TTS + VoiceClone
- 기능 및 결과 시각화
# 6. 기술 스택
- 데이터셋 : HuggingFace, AI-HUB
- 모델 : HuggingFace
- 통합개발환경(IDE) : VSCode
- UI : Gradio
- Collaborate : GITHUB, Figma
# 7. 시스템 구조
<img width="1505" height="847" alt="KakaoTalk_20260429_152807279" src="https://github.com/user-attachments/assets/f1d96084-3a72-4ede-bb42-584efb02542f" /><br>
# 8. 실행 화면
<img width="1835" height="703" alt="KakaoTalk_20260429_094531096" src="https://github.com/user-attachments/assets/8e687cc8-5991-49a8-ba81-d3454cb7cdbc" /><br>
<img width="1831" height="918" alt="KakaoTalk_20260429_094531096_01" src="https://github.com/user-attachments/assets/a1e35b27-337e-401f-b5cc-478b388b21df" />
# 9. 활용 방안
- 상용화를 한다면 구독형 서비스를 제공하여 GPU나 LLM모델의 사용료같은 것들을 지불하여 사용하게 하기<br>
ex)<br>
  1 FREE : M2M100 (로컬, 무료) <br>
  2 BASIC : OpenAI 번역 + 기본 TTS <br>
  3 PREMIUM : OPENAI + 보이스클론 + 전 언어
# 10. 프로젝트 회고


