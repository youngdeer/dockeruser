# dockeruser
use docker start webapp:
docker run --rm -it -p 3100:3000 --name dockerusetest -v "$(pwd)":/webapp -w /webapp node npm start

the follwing job is edit dockerfile to build images,then i can run this image in anywhere.

--add Dockerfile \n
docker build -t mywebapp .    (�����¾���) \n
docker run -it --rm -p 3000:3000 -v "$(pwd)":/src mywebapp  �������������˳���ɾ�����о���\n
docker run -itd -p 3000:3000 -v "$(pwd)":/src mywebapp   ����̨������
