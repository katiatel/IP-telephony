Часть 1



Создала топологию сети, состоящую из роутера, коммутатора и трех IP-телефонов.



 
<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231985899-5e777ab9-da62-470c-aa09-9a46932d09c9.png">




В консоли отключила синтаксис ввода слов от DNS серверов. На физическую консоль и на 5 самых используемых при подключении по SSH и Telnet установила пароль.




<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231986162-bb71ace6-788f-4d88-87ff-1cace9f5a49d.png">






 

Назначила интерфейсу маршрутизатора IP-адрес.







<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231986247-b6016a7b-4f78-4f6b-a194-a34468c08432.png">






 

Настроила dhcp сервер.





<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231986304-0f87b5a9-ac6a-42d7-a697-d5f34f80674d.png">


 

Затем настроила CallManager Express. Задала максимальное количество IP-телефонов и автоматическое назначение внешних номеров.


<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231986373-e9de103f-d0cb-46ad-8a08-55cb860d1f3b.png">


 

Назначила диапазон VLAN портов на коммутаторе.
 
 
 
 
 
 
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231986443-84a359c9-ce4f-402c-a80f-bab8d1611366.png">








Задала номера телефонов: 54001, 54002 и 54003 и осуществила тестовый звонок.
 
 
 
 
 
 
 
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231986492-e02c298e-49e5-4f2d-89cf-1ed74012698c.png">






Часть 2







Создала топологию сети, состоящую из роутера, коммутатора, трех IP-телефонов и трех PC.




<img width="412" alt="image" src="https://user-images.githubusercontent.com/53398280/231986554-7f47cc88-8881-4b6b-835a-6f4cb2efc308.png">







На коммутаторе создала виртуальные локальные сети для того, чтобы разделить сеть, которая связывает коммутатор и роутер, телефонную сеть и компьютерную сеть.
 
 
 
 
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231986605-51fe6404-7ba6-4887-8c24-1c42d6ad3108.png">






Интерфейс коммутатора, подключенный к роутеру, настроила как транк, пропускающий трафик из всех vlan. 





<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231986647-bbb4548a-27d6-40f1-b4c2-92a7f7c879d9.png">








Интерфейсы коммутатора, подключенные к IP-телефонам, перевела в режим access с поддержкой двух vlan.





<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231986693-2cf8db36-36ec-4d16-be36-87f2aa5ae745.png">



 

На маршрутизаторе настроила подинтерфейсы для интерфейса FastEthernet0/0, каждый из которых соответствует определенной vlan. 




<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231986727-e74f418a-a469-408d-a795-896e9b519f94.png">




На маршрутизаторе настроила подинтерфейсы для интерфейса FastEthernet0/0, каждый из которых соответствует определенной vlan. 




Добавила раздельные пулы IP-адресов для каждой отдельно взятой виртуальной подсети и настроила dhcp сервера для передачи голоса и данных на маршрутизаторе Cisco 2811.
 

Назначила компьютерам IP-адреса через DHCP.
 

Задала номера телефонов и совершила звонок между IP телефонами.
 

Протестировала передачу данных с помощью ping.
 

Вывод: в результате выполнения лабораторной работы было изучено построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.




