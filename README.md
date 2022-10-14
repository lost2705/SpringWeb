# SpringWeb
Блоговый движок, написанный на Java с использованием фреймворка Spring.
Для использования программы требуется:
1. Поднять собственный сервер с базой данных. В моем случае использовалась программа MAMP. 
 
 1.1. StartServer, вас перепрасывает на localhost
  
![image](https://user-images.githubusercontent.com/65293449/195877931-42552fa1-c3f5-4800-8f3d-c8bfbd45a148.png)
  
  1.2. Необходимо скопировать порт и вставить его в applicationProperties (в моем случае это 3306)
  
![image](https://user-images.githubusercontent.com/65293449/195878905-b9a02083-7111-478b-8c53-69170f590725.png)
  
![image](https://user-images.githubusercontent.com/65293449/195879290-9849cb20-644a-4be2-8fb2-bfa40eda1254.png)
  
2. Запустить BlogApplication
3. Перейти на localhost:8080 (это стандартный порт, однако его можно поменять в applicationProperties, внеся изменения в строчку server.port)

![image](https://user-images.githubusercontent.com/65293449/195880719-a9dedcea-e0fb-4c07-968e-e041b6fbc8b7.png)

  


