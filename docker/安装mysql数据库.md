## ��ȡ����:
docker pull daocloud.io/library/mysql:latest

docker pull daocloud.io/library/mysql:5.7.5

## ��������
docker run --name mysqlb -p 33306:3306 -e MYSQL_ROOT_PASSWORD=root -d daocloud.io/library/mysql:latest


������ֱ������localhost:33306 root root  ���ɳɹ�


















