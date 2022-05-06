# twenty-questions
## 코드 
![image](https://user-images.githubusercontent.com/93521131/167050442-2c0abaa7-32b2-4205-83a1-9ecc5764c2c8.png)
## 코드 설명
![image](https://user-images.githubusercontent.com/93521131/167050537-c5fe8611-4f21-403b-9644-779199f52aa0.png)

사용자에게 이름을 묻고, Scanner를 통해 이름을 입력받는다.

![image](https://user-images.githubusercontent.com/93521131/167050678-2d108a2e-c846-46eb-8227-a590d7a454b8.png)

Random 클래스를 불러와 정수형 변수에 넣고, 랜덤값은 0부터 시작하여서 +1를 하는 코드이다
boolean은 true로 해준 후,  보기 코드와 같이 두가지 선택지를 만들어 주었다.

![image](https://user-images.githubusercontent.com/93521131/167054919-2eff622b-23d7-46e6-9f11-e917d40233e2.png)


Scanner로 입력받은 변수값이 1과 일치하면 시작 , 2번이면 종료 하는 코드이다
while문 안에서  입력하는 변수와 rns변수가 같을 경우 종료, 아닐 경우 계속 반복하는 코드 이다.
## 출력화면

###  1번을 선택하였을때

![image](https://user-images.githubusercontent.com/93521131/167054800-caf69dfc-3a58-4e0c-9108-29824661a327.png)

잘 실행되는걸 볼 수 있다.

### 2번을 선택하였을때

![image](https://user-images.githubusercontent.com/93521131/167054962-3f328535-40e4-412e-909c-cc4330401707.png)

잘 종료 되는걸 볼 수 있다.

## 예외 처리
보기 코드는 취소 숫자를 2말고 다른 숫자를 입력하여도 종료된다.

![image](https://user-images.githubusercontent.com/93521131/167055198-1e823a1a-e50c-4ef0-8091-e780ed22002b.png)

그래서 2를 누를 경우에만 제대로 종료되게 코드를 다시 짜보았다.

![image](https://user-images.githubusercontent.com/93521131/167055343-fd3f3c7e-bcb8-4859-af4e-f20cd8c4ec5a.png)

else if문과 else의 값을 바꿔서 실행해 보았다.

![image](https://user-images.githubusercontent.com/93521131/167055387-3c602ed4-8da8-404c-b389-cb1d65e15d5f.png)

다른값을 입력하는 경우 "잘못선택하였습니다 종료합니다"라는 메세지가 뜨는것을 볼 수 있다.





