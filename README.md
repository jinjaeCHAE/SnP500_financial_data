# SnP500_financial_data
야후 파이낸스를 크롤링하고 라이브러리를 합쳐 해외 주식 종목의 재무 데이터를 정리합니다.

## 국내 주식 데이터는 키움 등을 통해 쉽게 정리된 데이터를 찾을 수 있지만 미국 주식 종목은 그렇지 않습니다.
## 이러한 점을 문제로 직접 크롤링과 라이브러리를 통해 제가 원하는 데이터를 수집하고자 했습니다.

## 이 크롤러를 제작한 것은 21년 1월 말입니다.
## 문제는 Yahho Finance의 JavaScript 코드에서 id값이 바뀝니다. 그래서 언제 하느냐에 따라서 약간의 오류가 있을 수 있습니다.
### 이 문제에 대해선 첫 번째와 두 번째를 참고하여 잘 조정하시면 될 것 같습니다. 두 번째의 for 문의 범위가 36-76인데 이걸 잘 조정해보세요.
### 혹은 정교하게 if문을 조정하시면 됩니다. 물론 지금은 잘 됩니다! 안되었을 때를 말하고 있는 것입니다.

## csv 파일은 하나도 포함 안했습니다. 직접 해보시길 바랍니다. 끝까지 잘 따라왔다면 아래와 같은 데이터를 얻을 수 있을 것입니다.
<div>
<img width="1000" src="https://user-images.githubusercontent.com/68219216/106378498-b1b62980-63e8-11eb-8940-2b44c6308e5b.JPG">
</div>

## 제가 종목을 선별하는 내용은 따로 담지 않았습니다. 데이터를 수집하고 각자 필요에 따라 분석하시길 바랍니다.
