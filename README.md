<div align="center">

# 2025-OS-Project

1️⃣ 2025-1 SW중심대학사업단 > 산학협력 프로젝트 (2025.03 ~ 2025.06)
</br>
2️⃣ [미정] 2025 WISET > 여대학원생 공학연구팀제 심화과정 (2025.04 ~ 2025.10)

</div>

## Subject

1️⃣ **산학협력 프로젝트** 
</br>
➤ 파일 복구를 위한 효율적인 하이브리드 복구 기법 연구
</br>
</br>
2️⃣ **여대학원생 공학연구팀제 심화과정** 
</br>
➤ AI-Driven Digital Forensics: 딥러닝을 활용하여 삭제된 파일의 복구를 최적화하는 하이브리드 복구 기법 연구
</br>
</br>
📌 산학협력 프로젝트 VS 여대학원생 공학연구팀제 심화과정
</br>
➤ AI 도입의 차이

</br>
</br>

## Summary of Projects

1️⃣ **산학협력 프로젝트** 
</br>➤ 기존 복구 도구의 성능 평가 및 ext4의 메타데이터 구조 분석을 통한 성능 및 한계 도출
</br>➤ 메타데이터 기반 + 파일 시그니처 기반의 하이브리드 복구 알고리즘 제안
</br>➤ CLI 기반 복구 도구를 구현하여, 기존 복구 대비 성능 향상률 평가

2️⃣ **여대학원생 공학연구팀제 심화과정** 
</br>➤ 기존의 파일 복구 기법을 분석하여 한계점 규명 및 문제 정의
</br>➤ AI 기반의 삭제되어 조각난 파일 복구 모델 설계 및 학습
  </br>(메타데이터 기반 + 파일 시그니처 기반 + AI)
</br>➤ 파일 무결성 검증 프로세스 구축 및 복구 성능 평가

</div>

## Project Plan - 1️⃣ 산학협력 프로젝트


| 주차 | 일자                     | 내용                                                                                      |
|:---:|:---------------:|------------------------------------------------------------------------------------------|
|  1  |  03.05 ~ 03.11  | <strong>기존 복구 도구 분석</strong> <br/> foremost, scalpel, testdisk, extundelete 조사 |
| 2    | 24.12.30 ~ 25.01.05      | <strong>[OS] 학습 및 자료 제작</strong> <br/> Chapter 14 - 파일 시스템 구현               |
| 3    | 25.01.06 ~ 25.01.12      | <strong>[OS] 학습 및 자료 제작</strong> <br/> Chapter 15 - 파일 시스템 내부구조           |
| 4    | 25.01.13 ~ 25.01.19      | <strong>[PL] 학습 및 자료 제작</strong> <br/> Chapter 09 - The Extended Filesystem Family <br/> > 9.2 Second Extended Filesystem |
| 5    | 25.01.20 ~ 25.02.02      | <strong>[PL] 학습 및 자료 제작</strong> <br/> Chapter 09 - The Extended Filesystem Family <br/> > 9.3 Third Extended Filesystem  |
| 6    | 25.02.03 ~ 25.02.09      | <strong>ext2 코드 리뷰</strong> <br/> > unlink 함수 위주                                |
| 7    | 25.02.10 ~ 25.02.16      | <strong>ext2 코드 리뷰</strong> <br/> > rmdir 함수 위주                                 |
| 8    | 25.02.17 ~ 25.02.23      | ext2 에서의 파일 복구 관련 아이디어 토의                                                 |
| 9    | 25.02.24 ~ 25.03.02      | 1) 아이디어를 실현하기 위한 코드 수정 방안 제시 <br/> 2) 2025-1 학기 계획 토의           |
