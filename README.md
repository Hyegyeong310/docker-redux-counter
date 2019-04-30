# Redux-counter

- Redux를 이용한 counters state 관리 연습.
- 왼쪽 마우스 클릭 -> +1, 오른쪽 마우스 클릭 -> -1, 더블 클릭 -> 색상 변경

### docker image 받기

- `docker pull hyegyeong310/redux-counter`

### docker container 생성 후 실행

- `docker run -it -p ${PORT}:80 --name ${container_name} hyegyeong310/redux-counter`
- localhost:\${PORT}에서 확인 가능

### docker container 재실행

- `docker start ${container_id} 또는 ${container_name}`

### docker container 중단

- `docker stop ${container_id} 또는 ${container_name}`

### docker image 확인 / docker image id 확인

- `docker images`

### docker container 확인

- `docker ps` // 실행 중인 container만
- `docker ps -a` // 모든 container 확인
