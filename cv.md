# **Nikita Usov**

## **Contacts**

* **Location:** Dnipro, Ukraine
* **Phone:** +38(066)-601-66-20
* **Email:** nikitariusov@gmail.com
* **GitHub:**  [nikitariusov](https://github.com/nikitariusov)
* **Discord:** Nikita Usov (@nikitariusov)

## **About Me**

I am rapidly moving towards backend development, making parsers for collecting data on the Internet. I create document processors, parsers for collecting data for business. I am constantly developing and I believe that nothing is impossible. To accomplish this task, I am ready to learn new material, all new technologies are amenable to mastery.

## **Skills**

* Python 3 
* Python libraries: BeautifulSoup, Request, openpyxl
* HTML
* CSS
* Git

## **Code Example**

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

## **Experience**

1. [Software for collecting data about companies](https://github.com/nikitariusov/Company_data_parser)
2. [Content generator from shabolne and data table](https://github.com/nikitariusov/content_creator)
3. [Program for collecting photos from xml base by article and writing them to Excel](https://github.com/nikitariusov/find_photo_from_geyser)

## **Education**

* **University**
    * Dnipro, NATIONAL METALLURGICAL ACADEMY OF UKRAINE, Department of metallurgical production machines and units
* **Courses**
    * Cursera: Fundamentals of Python Programming

## **English**

**Elementary (A2)**
