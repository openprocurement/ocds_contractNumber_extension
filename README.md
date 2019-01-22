# Contact Number
This extension introduces one field that can be used to provide editable number 
of the contract.
## Overview
The field introduced by this extension is `contracts/contractNumber`. 
It can be represented as string.
## Example
The following extract illustrates this property in use within the contract block.
```
  "contracts": [
    {
      "status": "active",
      "documents": [
        {
          "hash": "md5:6e2f437f7b4080d5c482fd3a5c50c688",
          "format": "application/msword",
          "url": "https://public.docs.openprocurement.org/get/cbe33e83148445669c1f3cccc54c142e?KeyID=52462340&Signature=Esn5qEng9zJt0XUg3MJ3wjsktPwbLy8kHFSkbSBfGSi6h0%252BphiPc%252BVNqDm9GAIm2A0vKvcfJNyyvdtUJd1FKCA%253D%253D",
          "title": "ЗУД ВТ 493-03 3.doc",
          "documentOf": "tender",
          "datePublished": "2018-04-05T17:15:21.021191+03:00",
          "dateModified": "2018-04-05T17:15:21.021211+03:00",
          "id": "1e496cf8808b46e18c882af24377d365"
        },
      ],
      "items": [
        {
          "description": "Послуги з ремонту гідропередачі тепловозу",
          "classification": {
            "scheme": "ДК021",
            "description": "Послуги з ремонту, технічного обслуговування залізничного транспорту і пов’язаного обладнання та супутні послуги",
            "id": "50220000-3"
          },
          "deliveryAddress": {
            "countryName": "Україна",
            "region": "Відповідно до документації"
          },
          "deliveryDate": {
            "startDate": "2018-03-23T00:00:00+02:00",
            "endDate": "2018-12-31T00:00:00+02:00"
          },
          "id": "bf4cc8c1d0684679b68674607d5a7874",
          "unit": {
            "code": "E48",
            "name": "послуга"
          },
          "quantity": 1
        }
      ],
      "suppliers": [
        {
          "contactPoint": {
            "name_ru": " ",
            "name": "Павлов Ігор Миколайович",
            "telephone": "+380512443239",
            "faxNumber": "+380512443164",
            "name_en": " ",
            "email": "magistral-yug2000@ukr.net"
          },
          "identifier": {
            "scheme": "UA-EDR",
            "id": "31096185",
            "legalName": "ТОВ Магістраль-Юг"
          },
          "name": "ТОВ Магістраль-Юг",
          "address": {
            "postalCode": "54025",
            "countryName": "Україна",
            "streetAddress": "проспект Героїв Сталінграду 87 В квартира 29",
            "region": "Миколаївська область",
            "locality": "місто Миколаїв"
          }
        }
      ],
      "contractNumber": "ВТ 493-03/3",
      "period": {
        "startDate": "2018-04-05T00:00:00+03:00",
        "endDate": "2018-12-31T00:00:00+02:00"
      },
      "dateSigned": "2018-04-05T12:00:00+03:00",
      "value": {
        "currency": "UAH",
        "amount": 445000.0,
        "valueAddedTaxIncluded": true
      },
      "date": "2018-04-05T17:16:43.511190+03:00",
      "awardID": "ef8731881ada403e86c099c199b78fbb",
      "id": "035fdb8434694e56bc7a6c31ee7403d9",
      "contractID": "UA-2018-02-05-001488-a-c2"
    }
  ],
```