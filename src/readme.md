**Create**

createProductTest - позитивный тест Создание продукта  
createProductWithIdTest - негативный тест Создание продукта с указанным id в запросе  
createProductWithNullFieldTest - негативный тест Создание продукта с пустыми полями цены и названия  
createProductWithOtherCategoryTest - позитивный тест Создание продукта с категорией "Other" (если я правильно понял, то нигде не указано, что могут быть только определённые категории)

**Get**

getProductsByIdTest - позитивный тест Получить продукт по id  
getAllProductsTest - позитивный тест Получить все продукты  
getAfterDeleteProductTest - негативный тест Получить продукт по id после удаления этого продукта   
getADeleteProductTest - негативный тест Получить продукт по несуществующему id   
??? получить все продукты когда нет ни одного

**Update**

updateProductTest - позитивный тест Изменить продукт
updateProductWithoutIdTest - негативный тест Изменить продукт с неуказанным id в запросе  
updateWithNullFieldTest - негативный тест Изменить продукт с пустыми полями цены и названия   
updateProductAfterDeleteTest - негативный тест Изменить удалённый продукт

**Delete**

deleteProductTest  - позитивный тест Удалить продукт по id   
deleteAfterDeleteProductTest - негативный тест Удалить удалённый продукт   



