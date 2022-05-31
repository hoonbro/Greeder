## 1. 프로젝트 개요
 
- 사용자 텍스트 기반 감성 이미지, BGM 추천 시스템 
    - 이미지 제공
        - 이미지에 대한 키워드로 새로운 이미지를 크롤링 해서 추가 제공 
        - 직접 이미지 업로드 가능
    - 배경 음악 추천
        - 텍스트에 적합한 감정 기반 추천
        - librosa를 사용해 feature 추출 후 코사인 유사도 측정
        
- 추천한 이미지, 음악으로 다이어리 페이지를 완성하여 제공
    
<img width="80%" src="https://user-images.githubusercontent.com/37919421/137606329-194be27c-e40d-4142-99a5-24fb2835d10f.png"/>


## 2. 프로젝트 구조

<img width="80%" src="https://user-images.githubusercontent.com/37919421/137606239-e71ed2b1-6f36-42aa-bb62-021fde02251f.png"/>
<img width="80%" src="https://user-images.githubusercontent.com/37919421/137606585-b5771e0b-1fda-44fa-b1fa-46588e160b96.png"/>

## 3. 프로젝트 동작 영상

### 1) 회원가입 및 로그인
![1 회원가입 및 로그인](https://user-images.githubusercontent.com/66583397/171165800-b5d190a5-d465-4168-a56f-7e98bb7d124a.gif)

### 2) 회원정보 수정
![2 회원정보 수정](https://user-images.githubusercontent.com/66583397/171166041-2bd9f059-b8ed-4be7-9609-4c3e8a183fbf.gif)

### 3) 다이어리
![3 다이어리](https://user-images.githubusercontent.com/66583397/171166020-d4e50f76-b795-42ce-bd03-07f5bd23bfdc.gif)

### 4) 일기 작성1
![4 일기 작성](https://user-images.githubusercontent.com/66583397/171166054-35ce9a2c-df45-4f57-82d7-75563287c2a3.gif)

### 5) 일기 수정 및 일기 작성2
![5 일기 수정 및 일기 작성](https://user-images.githubusercontent.com/66583397/171167322-a78d549c-3a80-4669-a1a2-d1ebafbf72eb.gif)

### 6) 일기 목록
![6  전체 일기 및 일기 목록](https://user-images.githubusercontent.com/66583397/171165859-c838a04a-f2f4-439d-ac4e-ffffab39fd26.gif)




<!-- # APIs and server urls still alive...;;
- [API_명세서.pdf](https://github.com/Seungyeup/Recommender/files/7358467/API_.pdf)
- Semetric Server URL : http://8a59-42-82-239-228.ngrok.io/emotion
    - if you send json { "writing" : "감정 분석하고자 하는 글"} -> this link will return 0 | 1 | 2  (중립,긍정,부정)
- Backend Server API : http://52.79.40.167:9000/docs#/default -->

<!-- 
![our goal](https://user-images.githubusercontent.com/37919421/137606329-194be27c-e40d-4142-99a5-24fb2835d10f.png)
![what we used](https://user-images.githubusercontent.com/37919421/137606239-e71ed2b1-6f36-42aa-bb62-021fde02251f.png)
![what i did](https://user-images.githubusercontent.com/37919421/137606585-b5771e0b-1fda-44fa-b1fa-46588e160b96.png)
![how this works](https://user-images.githubusercontent.com/37919421/137607023-21c010f1-127e-461b-9db3-23b987fa1ec3.gif) -->
