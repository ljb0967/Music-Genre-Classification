# Music-Genre-Classification
- Classify music genres using datasets collected from a variety of sources, including personal CDs, radio, microphone recordings, and more
- 주의사항 (필독)
- 제출 시, 입력값의 타입 확인 요망 (submit.csv의 열 데이터별 타입)

- music: char
- genre: char
- GTZAN Dataset - Music Genre Classification 데이터 셋
- GTZAN 데이터셋은 음악 장르 분류 문제를 다루는 데이터셋입니다. 이 데이터셋은 머신 러닝 및 딥 러닝 알고리즘을 사용하여 음악의 장르를 자동으로 분류하는 모델을 학습하고 평가하는 데 널리 사용됩니다.

- 이 데이터셋에는 10개의 장르가 포함되어 있으며, 각 장르는 100개의 30초 길이의 오디오 파일로 구성되어 있습니다. 데이터는 원래 Marsyas 소프트웨어 프레임워크의 일부로 제공되었으며, 다양한 연구 및 학습 목적으로 사용됩니다.

- 제공되는 폴더외 파일 설명
- train: 학습 데이터
- test: 테스트 데이터
- sample_submission.csv: 제출 파일 예시
- 컬럼 설명
- id: 오디오 파일의 ID
- feature1, feature2, …, featureN: 오디오 파일의 다양한 특성 (예: MFCC, 스펙트로그램 등)
- genre: 음악 장르 라벨 (train.csv에만 존재)
- 라벨 정보
- 데이터 셋의 10가지 장르는 아래와 같습니다.

- Blues
- Classical
- Country
- Disco
- Hiphop
- Jazz
- Metal
- Pop
- Reggae
- Rock
