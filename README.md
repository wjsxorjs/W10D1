# W10D1
> Day 1 of Docker

# Docker
> docker run --name [container_name] -d -p [port_num] [image_name] <br>
> > [container_name]의 이름으로 container 생성. 해당 container는 [image_name] 이미지를 통해 생성됨. <br>
> > localhost:[port_num]으로 정상 작동이 되는 지 확인 가능
> 
> docker container ls (또는 docker ps) : container 목록 확인<br>
> docker image ls : image 목록 확인<br>
> docker container stop [id] : id값에 해당하는 container를 정지. id값은 구별이 가능할 정도로만 작성 가능(3~4자)<br>
> docker container start [id] : id값에 해당하는 container를 시작. id값은 구별이 가능할 정도로만 작성 가능(3~4자)<br>
> docker restart [id] : id값에 해당하는 container를 재시작. id값은 구별이 가능할 정도로만 작성 가능(3~4자)<br>
> > restart는 container만 갖고있는 기능이어서 대상을 명시하지 않아도 된다.
>
> docker rm [id] : id값에 해당하는 container를 삭제. id값은 구별이 가능할 정도로만 작성 가능(3~4자)<br>
