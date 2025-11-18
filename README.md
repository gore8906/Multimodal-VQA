# 2025 SCPC AI Source Code

## 요약
- Qwen-1.8B-Chat을 기반으로 한 멀티모달 VQA(Visual Question Answering) 모델 학습 및 제출 파일 생성.
- 아키텍처: InstructBLIP Vision Encoder + 축소된 Q-Former + Qwen-1.8B-Chat (LLM).

## 실행 순서
  1. Pre-training: share_instructblip_qwen_pt.ipynb
     - Vision-Language 초기 정렬
  2. SFT: share_instructblip_qwen_sft.ipynb
     - VQA 및 대화 능력 미세 조정
  3. Inference: share_instructblip_qwen_pt_inference.ipynb
     - 최종 예측 및 제출 파일 생성
     
## (Qwen-1.8B-Chat 모델의 라이선스 정책을 준수해야 합니다.)
