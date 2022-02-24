# 크롤링을 이용한 개체명 인식 모델 
## Named-Entity recognition

이 프로젝트는 K-Digital 빅데이터 과정 수강생 7명이 공동으로 작업한 프로젝트입니다.

프로젝트 수행과정에 대한 더욱 세부적인 사항은 .ipynb 파일에서 확인하실 수 있습니다.

### 팀원 소개
>김준기 star956733@gmail.com
>
>엄성현 tjdgus510@gmail.com
>
>이경진 kungjin0119@naver.com
>
>이상화 templas332@naver.com
>
>임혜림 eim0801@naver.com
>
>조민지 study.minji.study@gmail.com
>
>하은겸 foreverek4th@naver.com

### 프로젝트 기여부분
형태소 분석기 체택, 태깅,하이퍼 파라미터 적용해보며 최적의 정확도 모델 검색

![슬라이드1](https://user-images.githubusercontent.com/83121895/150081129-8a46c978-6535-4775-b652-2f9f013832ab.GIF)

![슬라이드4](https://user-images.githubusercontent.com/83121895/150081177-942bbdc5-a847-4ee0-9130-7d6145a3e1cd.GIF)

![슬라이드5](https://user-images.githubusercontent.com/83121895/150081207-900e6c18-44d9-4be6-9ae6-7a72ad08bc95.GIF)

![슬라이드6](https://user-images.githubusercontent.com/83121895/150081244-c71af820-8b2c-4211-9e06-1e14600c877c.GIF)

![슬라이드12](https://user-images.githubusercontent.com/83121895/150081311-ef8ebdc3-4dae-4e98-8135-d175e3c4d873.GIF)

![슬라이드16](https://user-images.githubusercontent.com/83121895/150081389-782df664-d600-4cd5-9d16-e57675fcb74b.GIF)

![슬라이드16](https://user-images.githubusercontent.com/83121895/150081408-a76ad62c-3911-4385-93db-c7e278341cb7.GIF)

![슬라이드18](https://user-images.githubusercontent.com/83121895/150081438-c6e449d6-4cd8-4434-bb17-2f7b4045fb31.GIF)

![슬라이드20](https://user-images.githubusercontent.com/83121895/150081465-a20652ab-6ecb-4fbe-a40c-c688359f3560.GIF)

![슬라이드23](https://user-images.githubusercontent.com/83121895/150081513-e7c90b02-b42e-44c7-915e-83fe553d95d4.GIF)

![슬라이드28](https://user-images.githubusercontent.com/83121895/150081561-f8dbf054-d1eb-4cc3-bd79-c9c10572d98d.GIF)

![슬라이드29](https://user-images.githubusercontent.com/83121895/150081599-76aaf758-5045-4b20-972c-0390b582ed28.GIF)

![슬라이드32](https://user-images.githubusercontent.com/83121895/150081616-3f0a4b0e-7530-4922-9737-d157e2d07e54.GIF)

![슬라이드34](https://user-images.githubusercontent.com/83121895/150081650-e6610a35-9454-4b7e-9cad-cf4bb0f48736.GIF)

![슬라이드35](https://user-images.githubusercontent.com/83121895/150081662-9a185e86-3911-4d68-a002-36d7e289dd26.GIF)

![슬라이드37](https://user-images.githubusercontent.com/83121895/150081682-932bc807-228d-4e99-bf90-97e15b640bb3.GIF)

![슬라이드39](https://user-images.githubusercontent.com/83121895/150081704-14972186-dabf-486f-843c-8455376c6e99.GIF)

### 개선 방향 내용 추가(2022. 01. 10.)  
사람이 직접 모든 문장에 태깅을 하는 작업은 데이터 확보나 태그의 일관성 확보에 있어서 상당히 비효율적이었습니다.

이는 확보할 수 있는 데이터의 절대적인 수를 현저히 감소시켰으며, 사람의 주관이 주입된 태깅은 모델의 정확도가 더 이상 높아지지 못하도록 제한하였습니다.

이에 따라 k평균과 같은 군집화(Clustering) 알고리즘을 적용하는 방안을 추후 모색하고자 합니다.

비지도학습으로 모델링한다면, 태깅 작업에 따른 한계로 발생하는 문제들을 대거 해결할 수 있을 것으로 기대하고 있습니다.
