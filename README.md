## 1. 프로젝트 개요

- 사용자 텍스트 기반 감성 이미지, BGM 추천 시스템
    - 이미지 추천
        - 텍스트에 적합한 감정 기반 추천
        - 비슷한 감정의 다른 사용자가 선택한 이미지 추천
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

![how this works](https://user-images.githubusercontent.com/37919421/137607023-21c010f1-127e-461b-9db3-23b987fa1ec3.gif)


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
