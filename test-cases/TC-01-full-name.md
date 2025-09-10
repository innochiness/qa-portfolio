## TC-01: Проверка успешного заполнения всех полей формы
**Предусловие**: Открыта страница https://demoqa.com/text-box
**Шаги**:
1. В поле "Full Name" ввести "Alice"
2. В поле "Email" ввести "alice@example.com"
3. В поле "Current Address" ввести "Current Address 123"
4. В поле "Permanent Address" ввести "Permanent Address 456"
5. Нажать кнопку "Submit"

**Ожидаемый результат**:
Под формой отображается блок с текстом:
- Name: Alice
- Email: alice@example.com
- Current Address: Current Address 456
