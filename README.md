# zotero-style-korean
A CSL citation style for Korean linguistics research (Zotero and Mendeley compatible)
이 CSL(Citation Style Language) 스타일은 **한국어학 연구**를 위한 인용 및 참고문헌 양식을 제공합니다.  
Zotero와 Mendeley와 같은 CSL 표준을 지원하는 서지 관리 프로그램에서 사용할 수 있습니다.

이 스타일은 다음 자료 유형에 맞춘 인용 형식을 포함합니다:
- 학술지 논문 (Journal Article)
- 학위논문 (Thesis)
- 단행본 (Book)

---

## 1. 설치 방법

### Zotero
1. 이 저장소에서 `korean_bibliography.csl` 파일을 다운로드합니다.
2. Zotero를 열고, 상단 메뉴에서 `Edit > Settings > Cite > Style Manager(편집 > 설정 > 인용)`로 이동합니다.
3. **Style Manager** 화면에서 오른쪽 하단의 **`+` 버튼**을 클릭합니다.
4. 다운로드한 `korean_bibliography.csl` 파일을 선택하여 추가합니다.
5. 목록에 추가된 스타일을 선택하고 적용합니다.


---

## 2. 자료 유형별 인용 양식
- 용어는 [저장 요소 (Item Type별)](https://github.com/go00ood/zotero-translators-kr?tab=readme-ov-file#%EC%A0%80%EC%9E%A5-%EC%9A%94%EC%86%8C-item-type%EB%B3%84) 참고
- Item Type 별로 저장 요소가 포함되어 있다면 정상적으로 작동합니다. 

### **(1) 학술지 논문 (Journal Article)**
- **본문 인용**:
  ```plaintext
  (저자명, 연도)
  ```

- **참고문헌**:
  ```plaintext
  저자명(연도), 논문 제목, 학술지명 권(호), 학회명, 페이지.
  ```
  <조테로 기준>
  ```plaintext
  저자(날짜), 제목, 시리즈 제목 권(호), 간행, 쪽.
  Author(Date), Title, Series Title Volume(Issue), Publication, Pages.
  ```

  예시
  ```plaintext
  황국정(2005), 조사 ‘-로’의 ‘대상성’에 관한 통시적 연구, 형태론 7(1), 111–134.
  김민국(2017), ‘에서’ 주어의 통사와 의미, 국어학 81, 국어학회, 145–189.
  ```

---

### **(2) 학위논문 (Thesis)**
- **본문 인용**:
  ```plaintext
  (저자명, 연도)
  ```
- **참고문헌**:
  ```plaintext
  저자명(연도), 논문 제목, 소속대학 석사/박사학위논문.
  ```
  <조테로 기준>
  ```plaintext
  저자(날짜), 제목, 대학 형식+학위논문.
  Author(Date), Title, University Type학위논문.
  ```

  예시
  ```plaintext
  김미경(2013), '뵙다' 동사의 통시 통사론, 서울대학교 석사학위논문.
  정연주(2015), '하다'의 기능에 대한 구문 기반 연구, 고려대학교 박사학위논문.
  ```

---

### **(3) 단행본 (Book)**
- **본문 인용**:
  ```plaintext
  (저자명, 연도)
  ```
- **참고문헌**:
  ```plaintext
  저자명(연도), 책 제목, 출판사.
  ```
  <조테로 기준>
  ```plaintext
  저자(날짜), 제목, 출판사.
  Author(Date), Title, Publisher.
  ```
  
  예시
  ```plaintext
  가와사키 케이고(2017), 중세한국어 감동법이란 무엇인가, 신구문화사.
  ```

---
