# sukjulyo

<center>
	
![head_image_1](https://user-images.githubusercontent.com/61046271/139574437-2c27c059-8b2e-4689-afa3-a8342f2149f8.png)
	
![head_image_2](https://user-images.githubusercontent.com/61046271/139574438-1aed1392-88c2-4fd8-be6d-8841bba90baa.png)
	
![head_image_3](https://user-images.githubusercontent.com/61046271/139574440-ad129b42-8c0f-44f4-910f-211b05f76300.png)
</center>

## 1. Topic
기간 내 이슈가 되는 뉴스 선정.<br/>

	언론사에서 재공하는 RSS를 통해 뉴스를 수집 후 NER를 통해 각 뉴스의 해시태그 추출.
	일정 수준 이상 모인 해시태그를 이슈 키워드로 지정 후 해당 키워드 뉴스 추천

- [eagle705/pytorch-bert-crf-ner](https://github.com/eagle705/pytorch-bert-crf-ner, 'pytorch-bert-crf-ner github link')

## 2. Latent Factor Based Filtering
취향이 유사한 다른 유저들을 찾아 유저들이 선호하는 뉴스에서 사용자가 아직 보지 않은 뉴스 추천.

## 3. Contents Based Filtering
유저가 선호하는 해시태그와 가장 근접한 뉴스를 선정

	뉴스 장르의 코사인 유사도를 계산하여 가장 유사한 뉴스 추천
