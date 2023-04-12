# Product_metrics
Имеются данные по доставке продуктов на дом. Сервис доступен как в приложении на ios, так и на android. В конце квартала необходимо проанализировать поведение пользователей, а также оценить эффективность каналов их привлечения. 

## Описание данных 

- **date** – дата совершения события  

- **event** - событие  

*app_install* – установка приложения  
*app_start* – открыть приложения  
*registration* – зарегистрироваться  
*search* – перейти на страницу поиска товаров (каталог)  
*open_item* – открыть товар  
*choose_item* – отправить товар в корзину  
*tap_basket* – перейти в корзину  
*purchase* – подтверждение покупки  
- **gender** – пол пользователя  

- **os_name** – платформа пользователя  

- **city** – город пользователя  

- **device_id** – идентификатор устройства пользователя  

- **urm_source** – канал, с которого пришел пользователь  

*yandex-direct* – Яндекс директ  
*google_ads* – реклама в Google  
*vk_ads* – реклама в ВК  
*instagram_ads* – реклама в instagram  
*facebook_ads* – реклама в facebook  
*referral* – акция «приведи друга»  
Если стоит ‘-’, то канал не определен или это скачивание приложения напрямую или посещение не с рекламы    
- **purchase_sum** – стоимость покупки (при совершении события ‘purchase’)
