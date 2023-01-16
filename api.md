# API 
<br/>

### Application Programming Interface
##### 컴퓨터나 컴퓨터 프로그램 사이의 연결 
<br/>

#### API 활용시 확인 사항 
##### 요청하는 방식 - 인증 방식, URL 생성 (기본 주소, 원하는 기능에 대한 경로, 요청 변수)
##### 응답 결과에 대한 이해 - 응답 결과 타입 (JSON), 응답 결과 구조 
<br/>

```
import requests

URL = 'https://api...'
response = requests.get(URL)
data = response.json()

print(data.get('data').get('BTC').get('closing_price'))
```
<br/>

```
import requests

def get_btc_krw():
    order_currency = "BTC"
    payment_currency = "KRW"
    url = f"https://api.bithumb.com/public/ticker/{order_currency}_{payment_currency}"

    res = requests.get(url=url).json()
    data = res["data"]
    prev_closing_price = data["prev_closing_price"]

    return prev_closing_price

if __name__ == "__main__":
    print(get_btc_krw())
```
<br/>