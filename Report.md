1. Создать 2 виртуальные машины на базе ОС Debian 12
Одна была создана в предыдущей работе, другая была развернута заново.
2. Обеспечить между ними сетевой обмен https://www.virtualbox.org/manual/ch06.html
![image](https://github.com/Vibronic1/Create_clocksync/assets/70960285/3e4bbd4d-114f-4de8-8571-2bb3550fe68e)
Подключили машинки в одну подсеть и проверили, что они действительно в одной подсети, заодно пинганули друг-друга.
3. Установить keycloak на ВМ 1, произвести первоначальную настройку, добавить realm и
пользователей appadmin, user в него. https://www.keycloak.org/docs/latest/server_admin/
![image](https://github.com/Vibronic1/Create_clocksync/assets/70960285/0c86d7c3-46c3-4e57-9c98-f1455123f2b0)
![image](https://github.com/Vibronic1/Create_clocksync/assets/70960285/f91849da-5752-4f3f-a4c5-766d7904be21)
![image](https://github.com/Vibronic1/Create_clocksync/assets/70960285/778330fb-2e56-44bc-848b-fe3f7e83b9b9)
![image](https://github.com/Vibronic1/Create_clocksync/assets/70960285/db277dc5-3d0a-4c1e-9962-bb79f6afe7ff)
![image](https://github.com/Vibronic1/Create_clocksync/assets/70960285/845086aa-41b9-47fd-a755-405683f38d50)
![image](https://github.com/Vibronic1/Create_clocksync/assets/70960285/7f828230-8459-443a-a121-4e89ca862cd2)

4. Развернуть на ВМ 2 тестовое приложение и подключить его к keycloak
https://kzhekov.medium.com/introduction-to-iam-with-keycloak-7b1127a16e0e
(приложение выбрать самостоятельно)

5. Подключить двухфакторную аутентификацию OTP для защищаемого приложения
https://ultimatesecurity.pro/post/2fa/
https://www.mastertheboss.com/keycloak/how-to-enable-two-factor-authentication-in-keycloak/
