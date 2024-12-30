docker iamge                                    //собранные контейнеры
docker build -t <container_name> .              //сборка
docker run -d -p 8080:80 <container_name>       //запуск
docker stop <image_id>                          //остановка
docker rmi -f <image_id>                        //удаление