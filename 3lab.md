Выполняла: Телегина Екатерина (K34212)


Создала топологию сети.
 







<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231988784-c9723c08-b68f-45d5-8a41-83cdaeed88a5.png">






Настроим оконченные устройства сети на DHCP.







<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231988846-3c1a8b40-283d-4a9a-9d83-56ab88806dbe.png">




 

Для роутеров A и B были сконфигурировала и включила интерфейсы, ведущие к внутренним сетям.
 
 
 
 
 
 
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231988913-e087d813-2ca9-4901-b113-708de0c18748.png">






Сконфигурировала интерфейсы, составляющие собой сеть между двумя маршрутизаторами, связывая удаленные подсети. 





<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231988969-5d6d4a2c-9ea7-4034-85c3-867f28f5598b.png">





Для каждой подсети на маршрутизаторах создала пул IP-адресов, поддерживающий IP телефонию. 





<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231989004-6729dd99-0ad6-4bf5-b975-b5d298b0bc56.png">





Затем настроила динамическую маршрутизацию на основе протокола rip для передачи информации между маршрутизаторами в сети. Настроила сервис телефонии задав максимально возможное количество телефонов и номеров, указав источник IP-адресов и настроив автоматическое распределение линий.
 
 
 
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231989048-1e1b5bab-4a91-4c71-98a9-f69426151699.png">






Назначила диапазон портов.






<img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231989118-51b052c3-d476-4b0a-a555-34d2768436ff.png">






 

Указала внутренние номера 1201, 1202, 1203 для IP телефонов.
 
 
 
 
 
 
 
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/53398280/231989167-e4b7bdf6-b455-4937-9d51-4598b771464e.png">







Успешный прозвон между подсетями.
 






<img width="473" alt="image" src="https://user-images.githubusercontent.com/53398280/231989218-0a940e6b-eb2a-4e93-9d3a-e48c9e2a5487.png">






Успешный ping.





<img width="450" alt="image" src="https://user-images.githubusercontent.com/53398280/231989257-60b00026-0bb9-4477-8811-164f51449552.png">










Вывод: в результате выполнения лабораторной работы был изучен алгоритм построения сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т.


