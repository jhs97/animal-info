# 동물정보 페이지
demo:  https://jhs97.github.io/animal-info/

## 구성
1. 메인, 서브 페이지 구성
2. 모바일 텝 메뉴 구현
3. 이미지요소 + 텍스트 정보의 동물 썹네일 구성
4. 데이터로 가공하여 서버에서 불러오기(자바스크립트) <br>
   - DB URL: https://raw.githubusercontent.com/csslick/animal-mobile/main/animal-data.json <br>
   - 서버(db) ---> 클라이언트 <br>
   - 자바스크립트 fatch API
   - 자바스크립트로 동물정보 출력
5. 카테고리 별로 동물 표시(카테고리 필터링)
   - location.search로 페이지별 요청 파마리터(query) 확인
   - new URLSearchParams(search param).get(key)
6. 시작페이지(index.html) 기본값 params = dog


![animal-info preview](https://user-images.githubusercontent.com/105402450/176827813-78eec6cd-6be9-4a5a-99b1-d9f244fae1db.JPG)
