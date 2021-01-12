# Отчёт о тестировании *KeyValidator*

## Краткое описание
- Дата начала: 10.01.2020 г. 
- Дата окончания: 10.01.2020 г. 
было проведено *Smoke Test* приложения *KeyValidator*.

**На тестирование затрачено: 1 час.**

## В результате тестирования выявлены следующие дефекты:

- [Ошибка в валидных значениях при тестировании](https://github.com/rabmail/Java_DZ1.1/issues/1#issue-782803360)

- [Ошибка в невалидных значениях при тестировании](https://github.com/rabmail/Java_DZ1.1/issues/2#issue-782804651)


## В качестве тестовых данных использовались данные:

### Валидные ключи:

1. 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998+
1. 80b427f8-92cd-3aae-ba04-3927fbe17c6-
1. b295bc63-9f03-3b4b-af80-969b39f8c262+
1. 387eedc6-12e9-3b32-9881-63b6b5e85317+
1. c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180+

### Невалидные ключи:

1. 18252235-78e0-44a5-8720-556f0c7da17a+
1. e66075b6-ddad-445e-baf6-161b3289522b+
1. b6d53250-f07e-4352-a293-6102ddf7f1ca+
1. c2bc778a-1cb9-46c6-b435-0489649d2a42+
1. 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1-

## Тестирование производилось в следующем окружении:

# версия и разрядность ОС: 
- Windows 10 PRO, 64, версия 1909
# версия Java:
- openjdk version "11.0.9.1" 2020-11-04
- OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
- OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)