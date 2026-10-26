# BitWave 기반 DNN 가속기 — 데이터 처리 Python 코드

0인 bit-column을 건너뛰는 DNN 가속기를 Verilog로 구현한 팀 프로젝트 중,
제가 맡은 **데이터 전처리와 RTL 검증용 golden 값 생성** 코드입니다.

- 구조 출처: M. Shi et al., *"BitWave: Exploiting Column-Based Bit-Level Sparsity for Deep Learning Acceleration"* (KU Leuven · NXP)

## 내용

`DNN_data.ipynb`: MNIST MLP 학습 → int8 양자화 → Bit-flip → ZCI 압축 → golden 값 검증 → testbench 파일 생성
