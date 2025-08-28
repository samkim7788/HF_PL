# HF_PL - 맟춤형 위로 멘트 생성<br>

<br />

### ▶️ 사용 데이터 설명

[https://huggingface.co/datasets/passing2961/KorEmpatheticDialogues]

출처 : Chatbot_data_for_Korean v1.0


데이터 출처 및 범위

데이터 설명 : 
KorEmpatheticDialogues는 DeepL 번역기 API를 사용하여 원본 EmpatheticDialogues 데이터에서
번역된 공개적으로 사용 가능한 한국어 공감 대화 데이터이다. .
언어 - 한국

| 필드명       | 유형           | 설명                                                                 |
|--------------|----------------|----------------------------------------------------------------------|
| dialogue_id  | int            | 대화의 고유 식별자                                                   |
| dialogue     | list of dict   | 대화 발화 목록. 각 항목은 `{utter_idx, utter, user_id}` 구조의 사전   |
| situation    | str            | 감정적 상황을 설명하는 문장                                          |
| emotion      | str            | 감정 범주 (예: 죄책감, 배려, 슬픔, 기쁨 등)                          |


### ▶️ 사용 모델
monologg/kobert [https://huggingface.co/monologg/kobert]

# 결과<br />

<img width="616" height="324" alt="image" src="https://github.com/user-attachments/assets/bdd002ba-98df-4725-80f6-5821ee72bc3a" />

