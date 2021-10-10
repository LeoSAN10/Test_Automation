#Functional Test Cases

## Test case 1
  Steps:  
    1. Go to https://atlasbus.by/  
    2. Select the city in "Откуда" field.<br>
    3. Select the city in "Куда" field.<br>
    4. Click "Найти" button.<br>
  Expected Result:<br>  
    List of minibuses. 
    
## Test case 2
  Steps:<br>  
    1. Go to https://atlasbus.by/.<br> 
    2. Select the city in "Откуда" field.<br>
    3. Select the city in "Куда" field.<br>
    4. Select date in "Дата" field.<br> 
    5. Click "Найти" button.<br>
  Expected Result:<br>  
    list of minibuses for the specified date. 
    
 ## Test case 3. 
   Steps:<br>  
    1. Go to https://atlasbus.by/.<br> 
    2. Click on one popular direction in "Популярные направление" list.<br>
   Expected Result:  <br>
    list of minibuses for today in this direction. 
 
 ## Test case 4. 
   Steps:  <br>
    1. Go to https://atlasbus.by/.<br> 
    2. Select the city in "Откуда" field.<br>
    3. Select the city in "Куда" field.<br>
    4. Select date in "Дата" field.<br> 
    5. Click "Найти" button.<br>
    6. Select one of the offers.<br>
    7. Click "Показать детали" button.<br>
   Expected Result:  <br>
    All information about this offer.

 ## Test case 5. 
   Steps:  <br>
    1. Go to https://atlasbus.by/.<br> 
    2. Select the city in "Откуда" field.<br>
    3. Select the city in "Куда" field.<br>
    4. Select date in "Дата" field.<br> 
    5. Click "Найти" button.<br>
   Expected Result:  <br>
    Should be redirect to page this all offers for specified route. 
    
 ## Test case 6. 
   Steps:  <br>
    1. Go to https://atlasbus.by/.<br> 
    2. Select the city in "Откуда" field.<br>
    3. Select the city in "Куда" field.<br>
    4. Select date in "Дата" field.<br> 
    5. Click "Найти" button.<br>
    6. Select one of the offers.<br>
    7. Click "Заказать" button.<br>
   Expected Result:  <br>
    Should be redirect to the order page. 

## Test case 7
   Steps:<br>
    1. Go to https://atlasbus.by/.<br> 
    2. Select the city in "Откуда" field.<br>
    3. Select the city in "Куда" field.<br>
    4. Select date in "Дата" field.<br> 
    5. Click "Найти" button.<br>
    6. Select one of the offers.<br>
    7. Click "Заказать" button.<br>
    8. Click "Продолжить" button.<br>
   Expected Result:<br>
    Validation of required fields "Контактный телефон" and "Имя Фамилия" are show.
    
## Test case 8
   Steps:<br>
    1. Go to https://atlasbus.by/.<br> 
    2. Select the city in "Откуда" field.<br>
    3. Select the city in "Куда" field.<br>
    4. Select date in "Дата" field.<br> 
    5. Click "Найти" button.<br>
    6. Return on previous page
   Expected Result:<br>
    All fields saved entered data.
    
## Test case 9
   Steps:<br>
    1. Go to https://atlasbus.by/.<br>
    2. Click "Помощь" button.<br>
   Expected Result:<br>
    Return https://atlasbus.by/help with contacts and form for written request.
    
## Test case 10
   Steps:<br>
    1. Go to https://atlasbus.by/.<br>
    2. Click "Помощь" button.<br>
    3. Click "Для водителей" button.<br>
   Expected Result:<br>
    Return https://atlasbus.by/drivers with form for employmentю
