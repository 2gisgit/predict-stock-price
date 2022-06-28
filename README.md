# predict-stock-price
fft를 활용해 주식 가격을 분석하고 예측합니다.

# info
분석할 주식 선택시 앞에는 종목코드(삼성의 경우 005930), 뒤에는 주가 지수(코스피의 경우 ks)

분석이 뛰어나지는 못해서 가격이 음수로 가기도 하는데 이는 0으로 처리함<br>
또한 `predict = predict_fft(stock['Close'], 100)` 에서 100을 더 큰 숫자로 바꾸면, 증가하는 주식 그래프은 계속 증가함

# reference
https://leengine.tistory.com/9<br>
https://gist.github.com/tartakynov/83f3cd8f44208a1856ce
