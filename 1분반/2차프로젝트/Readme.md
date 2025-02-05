## 분석보고서

[보러가기](./BOOKTREE_분석보고서.pptx)

---

**visualize.ipynb**

* 2020년부터 2023년까지의 도서관내 프로그램 수와 도서관 회원수를 Linechart를 통해 표현

**extract_keywords.ipynb**

* BeautifulSoup를 통한 yes24리뷰 데이터 크롤링
* huggingface에서 불러온 kobert와 keybort를 통한 키워드 추출
* DBSCAN을 통한 대표 키워드 추출

**clustering.ipynb**

* k-means를 통한 소비그룹 분류

**suggest_challenge.ipynb**

* zero-shot 분류
* bart모델을 통해 키워드와 주요 소비 가맹업종분류가 담긴 리스트와 챌린지간의 유사도를 기반으로 챌린지 추천
