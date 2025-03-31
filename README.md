# Aksenova_bank

**1. Обозреватель решений**

![изображение](https://github.com/user-attachments/assets/80bc8e2a-c5c3-45e4-a056-a878a8e7c301)

**2. Вывод в консоль BankAccounts.cs**

![изображение](https://github.com/user-attachments/assets/feda52df-3884-4f59-b32f-ff6550673857)

**3. Результаты выполнения тестов**

![изображение](https://github.com/user-attachments/assets/173ae283-d2b6-43e3-abee-e7e8b5e2b408)


**4. Выводы**
Credit_WhenAmountIsLessThanZero_ShouldThrowArgumentOutOfRange вызвал затрудения при тестировании
1. Забыл подставлят return, что приводило к использованию метода Assert.Fail, приводивший к неуспешному выполнению теста
2. Забыл возращать в методе описание ошибки, оставив только возврат ("amount"), изменил на ("amount", amount, CreditAmountLessThanZeroMessage)
Тесты помогли выявить проблемы в коде и быстро их решить. Я вижу огромный потенциал у тестов и теперь осознаю всю важность их использования в программном продукте
