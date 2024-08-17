# Study_RabbitMQ
✍🏻 [Study] SpringBoot와 연동하여 RabbitMQ 학습과 실습을 위한 Repository입니다.

## 아키텍처
![스크린샷](/ReadMe-img/rabbitmq-drawio.png)
* RabbitMQ는 Docker Compose up을 하여 컨테이너로 띄웠습니다.
* Application은 총 4개 Order, Payment, Product-1, Product-2로 생성하였습니다.
* Order쪽에서 `market` exchange을 통해 market.payment쪽으로 메세지를 전달하는 기본적인 메시징 큐 형식으로 받아보는 실습을 진행했습니다.
* Order쪽에서 `market` exchange을 통해 market.product쪽으로 라운드 로빈 형식으로 메세지를 받아보는 실습을 진행했습니다.

## 기록한 블로그 링크
1. [👉🏻 [RabbitMQ] RabbitMQ란??](https://jiminchur.github.io/my-first-article/rabbitmq1/)
2. [👉🏻 [RabbitMQ] RabbitMQ 실습 (1)](https://jiminchur.github.io/my-first-article/rabbitmq2/)
2. [👉🏻 [RabbitMQ] RabbitMQ 실습 (2)](https://jiminchur.github.io/my-first-article/rabbitmq3/)

