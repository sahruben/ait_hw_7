# Employee Management System

## Описание проекта

Проект "Employee Management System" представляет собой простую систему управления информацией о сотрудниках компании. В основе системы лежит класс `Employee`, предназначенный для хранения данных о сотруднике.

## Класс Employee

### Описание

Класс `Employee` представляет собой модель данных о сотруднике компании. Он содержит следующие атрибуты:

- `id` (int): уникальный идентификатор сотрудника.
- `firstName` (String): имя сотрудника.
- `lastName` (String): фамилия сотрудника.
- `position` (String): должность сотрудника.
- `salary` (double): заработная плата сотрудника.

### Методы

1. **Конструкторы:**
    - `Employee(int id, String firstName, String lastName, String position, double salary)`: Создает новый объект с указанными параметрами.

2. **Геттеры и Сеттеры:**
    - `getId()`: Возвращает уникальный идентификатор сотрудника.
    - `getFirstName()`: Возвращает имя сотрудника.
    - `getLastName()`: Возвращает фамилию сотрудника.
    - `getPosition()`: Возвращает должность сотрудника.
    - `getSalary()`: Возвращает заработную плату сотрудника.
    - `setFirstName(String firstName)`: Устанавливает новое значение для имени сотрудника.
    - `setLastName(String lastName)`: Устанавливает новое значение для фамилии сотрудника.
    - `setPosition(String position)`: Устанавливает новое значение для должности сотрудника.
    - `setSalary(double salary)`: Устанавливает новое значение для заработной платы сотрудника.

3. **Методы:**
    - `toString()`: Возвращает строковое представление объекта `Employee`.

## Пример использования

```java
public class Main {
    public static void main(String[] args) {
        // Создание объекта Employee
        Employee employee = new Employee(1, "John", "Doe", "Developer", 50000.0);

        // Вывод информации о сотруднике
        System.out.println("Employee Information:");
        System.out.println(employee.toString());

        // Изменение заработной платы сотрудника
        employee.setSalary(55000.0);
        System.out.println("Updated Salary: " + employee.getSalary());
    }
}
```

## Лицензия

Этот проект распространяется под лицензией MIT. Подробности смотрите в файле `LICENSE`.gi