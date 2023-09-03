# fineDustFollowUp

## openweathermap
#### 1. 아래에 있는 OpenWeather 사이트로 들어간다.
[https://openweathermap.org/](https://openweathermap.org/)
![](https://github.com/mtinet/fineDustFollowUp/blob/main/images/openWeather.png?raw=true)

#### 2. 우측 상단에 있는 Sign In 버튼을 누르면 회원가입을 하거나, 로그인을 할 수 있다. 계정이 없다면 Create an Account 버튼을 눌러 회원가입을 하자. 회원가입은 이메일 인증까지 완료가 되어야 한다.
![](https://github.com/mtinet/fineDustFollowUp/blob/main/images/signUp.png?raw=true)

#### 3. 회원가입이 되어 있는 사람은 로그인을 한다.
![](https://github.com/mtinet/fineDustFollowUp/blob/main/images/login.png?raw=true)

#### 4. 로그인이 완료되면 우측 상단의 자기 계정 이름을 클릭하고 My API Keys 버튼을 누른다. 
![](https://github.com/mtinet/fineDustFollowUp/blob/main/images/myAPIkey.png?raw=true)

#### 5. 왼쪽에 Key란에 있는 OpenWeather API Key를 복사해서 자신의 프로젝트에 활용한다.
![](https://github.com/mtinet/fineDustFollowUp/blob/main/images/apiKey.png?raw=true)


## fineDustFollowUp
#### 1. 이 폴더에는 Raspberry Pi Pico W를 활용해 OpenWeather에서 제공하는 정보를 가져와서 서비스 하는 예제 파일들이 담겨 있다. 각 파일에 대한 설명은 다음과 같다. 
1. wifiConnect.py: Pico W를 와이파이에 연결하는 방법
2. getTime.py: 시간정보(그리니치 기준시)를 가져오는 방법
3. setTimezone.py: 시간정보를 서울시간으로 바꾸는 방법
4. getWeather.py: OpenWeather에서 날씨 정보를 가져오는 방법
5. getPolution.py: OpenWeather에서 공기오염 정보를 가져오는 방법
6. neopixelControl.py: 네오픽셀을 다루는 방법
7. neopixelExtension1.py: 네오픽셀의 각 셀에 불빛을 빙글빙글 돌리는 방법
8. neopixelExtension2.py: 색깔을 부드럽게 전환하는 방법
9. neopixelExtension3.py: 색깔을 무지개 빛깔로 제어하는 방법
10. base.py: 미세먼지 정보, 위치 정보, 시간정보를 활용해 원하는 위치의 미세먼지 수준을 네오픽셀의 빛깔로 표현하는 방법
11. baseExtension.py: 미세먼지 정보, 위치 정보, 시간정보를 활용해 원하는 위치의 미세먼지 수준을 네오픽셀의 빛깔로 표현할 때 점점 밝아졌다가 점점 어두워지게 하는 방법
12. autoFineDustCheckByPicoW.py: 자동으로 사용자가 지정한 세 곳의 미세먼지 수준을 순환하며 보여주는 방법
- neopixel.py: 네오픽셀을 사용할 때 필요한 라이브러리
- timezoneChange.py: 그리니치 기준시를 서울 시간으로 바꿔주는 라이브러리
