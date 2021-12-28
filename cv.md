# **Nikita Usov**

## **Contacts**
***
* **Location:** Dnipro, Ukraine
* **Phone:** +38(066)-601-66-20
* **Email:** nikitariusov@gmail.com
* **GitHub:**  [nikitariusov](https://github.com/nikitariusov)
* **Discord:** Nikita Usov (@nikitariusov)

## **About Me**
***
Краткая информация о себе (ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении учиться и узнавать новое)

## **Skills**
***
Навыки (языки программирования, фреймворки, методологии, системы контроля версий и инструменты разработки, которыми вы владеете)
* Python 3 
* Python libraries: BeautifulSoup, Request, openpyxl
* HTML
* CSS
* Git

## **Code Example**
***
```
from bs4 import BeautifulSoup
from Request import get_html, get_response


def pars_info(html_data):

    soup = BeautifulSoup(html_data, 'html.parser')
    cards_company = soup.find_all('div', class_='cart-company-lg')

    dict_keys = ["Название", "Сайт", "Почта", "Телефон",
                 "Вид деятельности"]
    data_base = []
    
    for card in cards_company:
        data_company = {}
        dict_value = []
        
        mail = card.find('a', target="_blank", rel=None)
        site = card.find('a', rel="nofollow", target="_blank")
```
***
## **Experience**
***
## **Education**
***
* University
* Courses

## **English**
***
