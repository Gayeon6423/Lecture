**[강의명]**

Generative AI with Large Language Models

**[수강일시]**

2024년 1월 ~ 2024년 2월

**[강의내용]**

<Lab_1_summarize_dialogue>

- Prompt Engineering 없이 대화 요약
- Zero Shot Inference 사용해서 Prompt 구성 후 대화 요약
- FLAN-T5로 부터 Prompt Template 전달
- One shot & Few shot Inference 사용해서 대화 요약
- 추론을 위한 Configuration Parameters 생성 

<Lab_2_fine_tune_generative_ai_model>

- Dataset과 LLM 로드
- Zero Shot Inferencing으로 Test Model
- Full Fine-Tuning 수행
  - Dialog-Summary Dataset 전처리
  - 전처리된 Dataset으로 Fine Tuning 수행
  - Human Evaluation 사용해서 Model Quanlitatively 평가
  - ROUGE Metric 사용해서 Model Quantitavely 평가
- Parameter Efficient Fne-Tuning(PEFT) 수행
  - PEFT/LoRA model 준비
  - PEFT Adapter 훈련
  - Human Evaluation 사용해서 Model Quanlitatively 평가
  - ROUGE Metric 사용해서 Model Quantitavely 평가

<Lab_3_fine_tune_model_to_detoxify_summaries>
- Data 및 Fine-Tuning된 Summarization instruction FLAN-T5 Model 불러오기  
- Reward Model 준비
- Toxicity 평가
- PPO Trainer 객체 초기화
- Detoxify summaries를 위한 fine-tuning 수행
- Model Quantitaviely 평가
- Model Qualitiviely 평가
