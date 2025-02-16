# <img width="30" height="30" src="https://img.icons8.com/nolan/64/sorting-arrows-horizontal--v1.png" alt="traffic"/> Перехват и изменение трафика

В рамках учебного проекта я использовала инструмент Charles Proxy для анализа, перехвата и изменения HTTP/HTTPS запросов.

Посмотрите следующие видеоролики, в которых я меняю данные запросов для WEB-приложения [demoshopping.ru](https://qa.demoshopping.ru/) с помощью Charles Proxy на компьютере и эмуляторе Android Studio:

## Перехват и изменение трафика на компьютере

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="25" height="25" src="https://img.icons8.com/nolan/64/sorting-arrows-horizontal--v1.png" alt="traffic"/> [Изменение количества товаров в корзине](https://drive.google.com/file/d/1-6iReNR3q-0XAWosnNlahvupXsWH6Vhg/view?usp=sharing). При добавлении товара в корзину в запросе отправляется 1 товар, а в ответе возвращается 500.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="25" height="25" src="https://img.icons8.com/nolan/64/sorting-arrows-horizontal--v1.png" alt="traffic"/> [Моделирование ошибки доступа (403)](https://drive.google.com/file/d/19uFvF9S7sy6sJXVByVO20awcg5qK0XFH/view?usp=sharing) при обращении к ресурсу [demoshopping.ru](https://qa.demoshopping.ru/)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="25" height="25" src="https://img.icons8.com/nolan/64/sorting-arrows-horizontal--v1.png" alt="traffic"/> [Перенаправление запроса c Prod на QA](https://drive.google.com/file/d/1yoYslyuhUW5MPnTp9WlckgqddNWu-mDc/view?usp=sharing).

## Перехват и изменение трафика на эмуляторе Android Studio

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="25" height="25" src="https://img.icons8.com/nolan/64/sorting-arrows-horizontal--v1.png" alt="traffic"/> [Изменение запроса на удаление товара из корзины](https://drive.google.com/file/d/1UmND46bgYevL90TM6Y4ufyQckqjoi7yp/view?usp=sharing) таким образом, чтобы удалился другой товар.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="25" height="25" src="https://img.icons8.com/nolan/64/sorting-arrows-horizontal--v1.png" alt="traffic"/> [Подмена контента](https://drive.google.com/file/d/1o4hhRBCdtXXM1SlmkpUEog2r2FrgzH7M/view?usp=sharing) при обращении к ресурсу [demoshopping.ru](https://qa.demoshopping.ru/)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="25" height="25" src="https://img.icons8.com/nolan/64/sorting-arrows-horizontal--v1.png" alt="traffic"/> [Скрин запроса](https://github.com/NikolaevaAR/traffic/blob/main/User%20Agent%20%D0%B2%20Header.png), подтверждающий, что трафик был перехвачен с мобильного устройства.

