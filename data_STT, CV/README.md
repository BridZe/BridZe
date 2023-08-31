# Whisper 음성인식 모델

### Whisper용 원천 데이터(샘플 100개)
- 음성 데이터의 수가 워낙 방대하다보니 샘플 데이터 100개씩만 업로드하였습니다.
- 전체 데이터가 필요하시다면 구글 드라이브 링크를 따로 제공하는 식으로 드리겠습니다.
  
### Whisper_코드.ipynb
- 기존 whisper모델을 그대로 쓸 수 있었지만, 조금이라도 베트남 사람의 발화 특성을 더 반영하기 위해
베트남인의 한국어 발화 음성 데이터셋을 활용해 **fine tuning**을 진행하였습니다.
- 코드에 대한 자세한 설명은 주석으로 달아 놓았습니다!

### Whisper_finetuned
- 저희가 구축한 데이터셋으로 Whisper 모델을 fine tuning 하였고,
여러 스텝 중 **손실값**과 **cer오류율**이 가장 낮은 스텝(3000스텝)을 저장하여 모델로 활용할 예정입니다.