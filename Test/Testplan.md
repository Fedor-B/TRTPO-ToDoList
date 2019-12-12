# План тестирования  
## Содержание    

1. [Введение](#par1) 
2. [Объект тестирования](#par2)
3. [Риски](#par3)
4. [Аспекты тестирования](#par4)
5. [Подходы к тестированию](#par5)
6. [Представление результатов](#par6)
7. [Выводы](#par7)

## <a name="par1">1. Введение</a>
Основная цель данного документа состоит в том, чтобы описать план тестирования мобильного приложения "TodoList". Эта информация предназначена для команды, которая будет тестировать данное программное обеспечение на соответствие.

## <a name="par2">2. Объект тестирования</a>
В качестве объекта тестирования следует выделить функциональное тестирование, а также тестирование удобства и простоты использования. К атрибутам качеcтва относятся следующие характеристики:
1.	Функциональная корректность.
2.	Удобство использования.

## <a name="par3">3. Риски</a>
Для работы приложение необходимо наличие версии Android не ниже 4.0.3, работающего сенсорного экрана либо другого устройства ввода на устройстве с оболочкой Android.

## <a name="par4">4. Аспекты тестирования</a>
В процессе тестирования предполагается проверить соответствие системы требованиям, на основе которых она была спроектирована и реализована. Для данного приложения являются следующие:
1.	Добавить дело
2.	Удалить дело
3.	Очистка списка дел

Также необходимо проверить соответствие системы:
1.	Сохранение списка дел после перезапуска приложения
2.	Правильность отображения окна приложения со скрытой панелью состояния устройства
3.	Просмотр полного списка добавленных дел с помощью перемотки в конец списка.

## <a name="par5">5. Подходы к тестированию</a>
Для тестирования приложения необходимо использовать ручное тестирование, чтобы проверить все аспекты тестирования.

## <a name="par6">6. Представление результатов</a>
Результаты тестирования представлены в документе [Test](https://github.com/stasfedorenko/TRTPO-ToDoList/blob/master/Test/Test.md).

## <a name="par7">7. Выводы</a>
Данный тестовый план позволяет протестировать основной функционал приложения. Успешное прохождение всех тестов не гарантирует полной работоспособности на всех платформах и архитектурах, однако позволяет полагать, что данное программное обеспечение работает корректно.
