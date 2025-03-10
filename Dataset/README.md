<div align="center">

# 1. Open Dataset

**1️⃣ GovData & NIST CFReDS Project**
</br>
➤ 미국 국립표준기술연구소(NIST)에서 제공하는 법의학 데이터셋
</br>
**[Link]** https://cfreds.nist.gov
</br>
**2️⃣ Digital Corpora**
</br>
➤ 파일 복구 및 포렌식 연구를 위한 공개 데이터셋
</br>
**[Link]** https://digitalcorpora.org
</br>
**3️⃣ The Honeynet Project (Scan of the Month Challenges)**
</br>
➤ 침해 사고 대응과 관련된 디스크 이미지 포함
</br>
**[Link]** https://www.honeynet.org/challenges
</br>
**4️⃣ Forensic Challenge Data from DFRWS**
</br>
➤ 디지털 포렌식 연구 워크샵에서 제공하는 데이터
</br>
**[Link]** https://dfrws.org
</br>

</div>

## 2. Homegrown Dataset

**2-1. Setting Experiments**
</br>
**[FS]** ext4
</br>
**[OS]** Linux_Ubuntu 22.04 LTS
</br>
**[Storage]** SSD, HDD, USB, etc.
</br>
**[Scenario]**
</br>
1️⃣ 일반적인 삭제 (rm, unlink, 휴지통으로 이동, ...)
</br>
2️⃣ 휴지통 비우기 (Shift+Del, ...)
</br>
3️⃣ 파일시스템 포맷 (mkfs, ...)
</br>
4️⃣ 디스크 파티션 삭제 (fdisk, gdisk, ...)
</br>
5️⃣ 스토리지 덮어쓰기 (dd, shred, srm, ...)
</br></br>
**2-2. Generating Data**
</br>
**[Type]**
</br>
**<Document>** .docx / .hwpx / .pdf / .txt / .xlsx / ...
</br>
**<Image>** .jpg / .png / .gif / ...
</br>
**<Video>** .mp4 / .avi / .mov / .wmv / ...
</br>
**<Audio>** .mp3 / .wav / ...
</br>
**<Database>** .csv / ...
</br>
**<Log>** .log / ...
</br>

</div>

## 📌 [Open Dataset] 2️⃣ Digital Corpora

</br>

**<Link>** https://digitalcorpora.org/corpora/file-corpora
</br>
**<Summary>**
</br>
⚫️ **다양한 파일 형식 평가:** Govdocs1
</br>
⚫️ **특정 파일 형식 집중 평가:** SAFEDOCS > PDF, FILETYPES1 > 특정 파일 형식
</br>
**🔴 <Govdocs1>**
</br>
➤ 약 100만 개의 다양한 문서 파일로 구성된 데이터셋으로, 연구 및 테스트 목적으로 널리 사용된다.
</br>
➤ 다양한 파일 형식을 포함하고 있어 복구 도구의 전반적인 성능 평가에 적합하다.
</br>
✔️ 다양한 파일 형식: 문서, 이미지, 스프레드시트 등 다양한 파일 포함
</br>
✔️ 대규모 데이터셋: 총 100만 개의 파일로 구성
</br>
✔️ 연구 친화적: 자유롭게 재배포 가능하며 연구 목적에 적합
</br>
**<SAFEDOCS (CC-MAIN-2021-31-PDF-UNTRUNCATED)>**
</br>
➤ 2021년 7월과 8월에 수집된 약 800만 개의 PDF 파일로 구성된 데이터셋이다.
</br>
➤ PDF 파일 복구 도구의 성능을 집중적으로 평가하고자 할 때 유용하다.
</br>
✔️ 최신 데이터: 2021년에 수집된 최신 PDF 파일 포함
</br>
✔️ 대규모 PDF 컬렉션: 800만 개 이상의 PDF 파일로 구성
</br>
✔️ 메타데이터 제공: 각 파일에 대한 상세한 메타데이터 포함
</br>
**<FILETYPES1>**
</br>
➤ 다양한 파일 형식의 샘플을 포함한 데이터셋으로, 특정 파일 형식의 복구 성능을 평가하는 데 유용하다.
</br>
➤ 각 파일 형식별로 샘플이 정리되어 있어 선택적으로 활용할 수 있다.
</br>
✔️ 다양한 파일 형식 샘플: ASP, AVI, DLL, EXE, JPG, MP3 등 다양한 파일 형식 포함
</br>
✔️ 파일 형식별 정리: 각 파일 형식별로 디렉토리가 구성되어 있어 접근 용이
</br>
✔️ 연구 및 개발에 활용 가능: 파일 형식 분류기 개발 및 테스트에 유용
</br>

</div>

## ❤️‍🔥 [Open Dataset] 2️⃣ Digital Corpora > 🔴 Govdocs1

</br>

**📑 분석 보고서:** https://digitalcorpora.org/corpora/file-corpora/files/govdocs1-simple-statistical-report/
</br>
**<1. Full Dataset>**
</br>
➤ 각각 1,000개의 파일이 존재하는 1,000개의 디렉터리
</br>
**Link** ➤ http://downloads.digitalcorpora.org/corpora/files/govdocs1/
</br>
**<2. ZIP Dataset>**
</br>
➤ 각각 1,000개의 파일이 존재하는 1,000개의 ZIP 파일
</br>
**Link** ➤ http://downloads.digitalcorpora.org/corpora/files/govdocs1/zipfiles/
</br>
**<3. JPEG Dataset>**
</br>
➤ 109,282개의 JPEG 파일이 존재하는 tar 파일
</br>
**Link** ➤ http://downloads.digitalcorpora.org/corpora/files/govdocs1/files.jpeg.tar
</br>
**<4. Random Dataset>**
</br>
➤ 10개의 하위 집합 'threads'(subset0.zip ~ subset9.zip)의 집합으로, 각 하위 집합에는 무작위로 선택된 1000개의 문서가 존재
</br>
➤ 하나의 하위 집합은 개발용으로, 다른 하위 집합은 테스트용으로 사용하도록 권장
</br>
**Link** ➤ https://corp.digitalcorpora.org/corpora/files/govdocs1/threads/
</br>
</br>
**<+> Feature List**
</br>
➤ 상황에 맞는 적절한 feature list
</br>
**Link** ➤ https://corp.digitalcorpora.org/corpora/files/2012-feature-list/
</br>
**<+> Other Metadata**
</br>
**MD5 - Link** ➤ https://digitalcorpora.s3.amazonaws.com/corpora/files/govdocs1/zipfilelist-md5.txt
</br>
**SHA1 - Link** ➤ https://digitalcorpora.s3.amazonaws.com/corpora/files/govdocs1/zipfilelist-sha1.txt
