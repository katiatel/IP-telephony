Часть 1
Создала топологию сети, основанная на 4 коммутаторах.


 
<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231983898-7c692dcf-08c0-48d2-9636-d1b033374962.png">


Каждому PC в этой сети присвоила ip адрес от 192.168.0.1 до 192.168.0.7 соответственно.



<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231984107-ca410727-c0f8-4ee0-b7e2-23e5d946f7d7.png">



<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231984153-f3912143-7dc0-4451-bd7b-dfdb7e30bf59.png">




Успешно провела ping между устройствами.




<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231984227-2e4e4c54-fdeb-44a9-aa0d-a3c4b91b87bd.png">



<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231984271-93ea8952-640a-435e-af2b-9dad64ff2d6e.png">


 
 

2 часть
Создала новую топологию сети, с маршрутизатором, коммутатором и двумя IP-телефонами.




<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231984320-ace8ed32-f139-47e9-bebc-01fd0153cc93.png">




 

Подключаем ip телефоны к блоку питания в разделе физического предтавления.
 
 
 
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231984636-78f2bc9b-3c8a-4261-8d1e-f662433f6a4b.png">




Задала адресацию для интерфейса роутера. 




<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231984665-0f6a6aaa-59d1-4965-a330-d742cc06bdad.png">






Настроила интерфейс fa0/0, а затем dhcp сервер на маршрутизаторе Cisco 2811. Cоздала новый DHCP-пул phones, в который вошли все адреса из сети, кроме адреса маршрутизатора. Его назначила дефолтным.



<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231984734-34c65489-4617-4d03-ab0f-05ff68888822.png">


  

Создала новый сервис IP-телефонии, указав максимальное кол-во устройств и телефонных номеров. Роутер настроен.
 
 
 
 
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231984787-f3a248cf-d200-41d4-b9f3-b7930e5467f7.png">





Включила на коммутаторе поддержку VoIP-интерфейсов.




<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231984868-61744cb3-549d-4324-a688-aa15c49ae665.png">


 

Задала устройствам телефонные номера и успешно совершила звонок с одного телефона на другой.



<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231984942-ca09f92b-f088-49fd-8abe-0f143450f844.png">



 

Вывод: в результате лабораторной работы я освоила работу с IP-телефонией на базе Cisco, настройку vlan и dhcp, смоделировала две топологии сети. 
