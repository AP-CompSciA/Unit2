
# Simple Classes Reference

These classes are provided for practice with **objects, classes, instance variables, constructors, and object creation**.

The classes contain only `int` and `double` instance variables. They do not contain methods.

---

## Car

Represents a car.

### Instance Variables

| Variable  | Type     | Description         |
| --------- | -------- | ------------------- |
| `year`    | `int`    | The year of the car |
| `mileage` | `double` | The car's mileage   |

### Constructors

```java
Car()
```

Creates a Car with `year` and `mileage` set to `0`.

```java
Car(int year, double mileage)
```

Creates a Car with the given year and mileage.

### Example

```java
Car car = new Car(2020, 45000);
```

---

## Student

Represents a student.

### Instance Variables

| Variable | Type     | Description       |
| -------- | -------- | ----------------- |
| `age`    | `int`    | The student's age |
| `gpa`    | `double` | The student's GPA |

### Constructors

```java
Student()
```

Creates a Student with `age` and `gpa` set to `0`.

```java
Student(int age, double gpa)
```

Creates a Student with the given age and GPA.

### Example

```java
Student student = new Student(16, 3.5);
```

---

## BankAccount

Represents a bank account.

### Instance Variables

| Variable        | Type     | Description         |
| --------------- | -------- | ------------------- |
| `accountNumber` | `int`    | The account number  |
| `balance`       | `double` | The account balance |

### Constructors

```java
BankAccount()
```

Creates a BankAccount with both values set to `0`.

```java
BankAccount(int accountNumber, double balance)
```

Creates a BankAccount with the given account number and balance.

### Example

```java
BankAccount account = new BankAccount(12345, 500.0);
```

---

## Product

Represents a product.

### Instance Variables

| Variable   | Type     | Description              |
| ---------- | -------- | ------------------------ |
| `quantity` | `int`    | The number of products   |
| `price`    | `double` | The price of one product |

### Constructors

```java
Product()
```

Creates a Product with both values set to `0`.

```java
Product(int quantity, double price)
```

Creates a Product with the given quantity and price.

### Example

```java
Product product = new Product(10, 4.99);
```

---

## Rectangle

Represents a rectangle.

### Instance Variables

| Variable | Type  | Description |
| -------- | ----- | ----------- |
| `width`  | `int` | The width   |
| `height` | `int` | The height  |

### Constructors

```java
Rectangle()
```

Creates a Rectangle with both dimensions set to `0`.

```java
Rectangle(int width, int height)
```

Creates a Rectangle with the given width and height.

### Example

```java
Rectangle rectangle = new Rectangle(10, 5);
```

---

## Circle

Represents a circle.

### Instance Variables

| Variable   | Type     | Description  |
| ---------- | -------- | ------------ |
| `radius`   | `double` | The radius   |
| `diameter` | `double` | The diameter |

### Constructors

```java
Circle()
```

Creates a Circle with both values set to `0.0`.

```java
Circle(double radius, double diameter)
```

Creates a Circle with the given radius and diameter.

### Example

```java
Circle circle = new Circle(5.0, 10.0);
```

---

## Employee

Represents an employee.

### Instance Variables

| Variable | Type     | Description           |
| -------- | -------- | --------------------- |
| `id`     | `int`    | The employee's ID     |
| `salary` | `double` | The employee's salary |

### Constructors

```java
Employee()
```

Creates an Employee with both values set to `0`.

```java
Employee(int id, double salary)
```

Creates an Employee with the given ID and salary.

### Example

```java
Employee employee = new Employee(123, 55000.0);
```

---

## House

Represents a house.

### Instance Variables

| Variable     | Type     | Description            |
| ------------ | -------- | ---------------------- |
| `bedrooms`   | `int`    | The number of bedrooms |
| `squareFeet` | `double` | The size of the house  |

### Constructors

```java
House()
```

Creates a House with both values set to `0`.

```java
House(int bedrooms, double squareFeet)
```

Creates a House with the given number of bedrooms and square footage.

### Example

```java
House house = new House(3, 2000.0);
```

---

## Movie

Represents a movie.

### Instance Variables

| Variable | Type     | Description                     |
| -------- | -------- | ------------------------------- |
| `year`   | `int`    | The year the movie was released |
| `rating` | `double` | The movie's rating              |

### Constructors

```java
Movie()
```

Creates a Movie with both values set to `0`.

```java
Movie(int year, double rating)
```

Creates a Movie with the given year and rating.

### Example

```java
Movie movie = new Movie(2025, 8.2);
```

---

## Book

Represents a book.

### Instance Variables

| Variable | Type     | Description           |
| -------- | -------- | --------------------- |
| `pages`  | `int`    | The number of pages   |
| `price`  | `double` | The price of the book |

### Constructors

```java
Book()
```

Creates a Book with both values set to `0`.

```java
Book(int pages, double price)
```

Creates a Book with the given number of pages and price.

### Example

```java
Book book = new Book(350, 19.99);
```

---

## Athlete

Represents an athlete.

### Instance Variables

| Variable | Type     | Description          |
| -------- | -------- | -------------------- |
| `age`    | `int`    | The athlete's age    |
| `height` | `double` | The athlete's height |

### Constructors

```java
Athlete()
```

Creates an Athlete with both values set to `0`.

```java
Athlete(int age, double height)
```

Creates an Athlete with the given age and height.

### Example

```java
Athlete athlete = new Athlete(18, 72.5);
```

---

## Phone

Represents a phone.

### Instance Variables

| Variable  | Type     | Description            |
| --------- | -------- | ---------------------- |
| `storage` | `int`    | The storage capacity   |
| `price`   | `double` | The price of the phone |

### Constructors

```java
Phone()
```

Creates a Phone with both values set to `0`.

```java
Phone(int storage, double price)
```

Creates a Phone with the given storage and price.

### Example

```java
Phone phone = new Phone(256, 799.99);
```

---

## Temperature

Represents a temperature reading.

### Instance Variables

| Variable  | Type     | Description     |
| --------- | -------- | --------------- |
| `degrees` | `double` | The temperature |
| `day`     | `int`    | The day number  |

### Constructors

```java
Temperature()
```

Creates a Temperature with both values set to `0`.

```java
Temperature(double degrees, int day)
```

Creates a Temperature with the given temperature and day.

### Example

```java
Temperature temperature = new Temperature(72.5, 19);
```

---

## Coordinate

Represents a coordinate.

### Instance Variables

| Variable | Type  | Description      |
| -------- | ----- | ---------------- |
| `x`      | `int` | The x-coordinate |
| `y`      | `int` | The y-coordinate |

### Constructors

```java
Coordinate()
```

Creates a Coordinate with both values set to `0`.

```java
Coordinate(int x, int y)
```

Creates a Coordinate with the given x and y values.

### Example

```java
Coordinate coordinate = new Coordinate(10, 25);
```

---

# Classes with Three Instance Variables

## Game

Represents a game.

### Instance Variables

| Variable | Type     | Description               |
| -------- | -------- | ------------------------- |
| `score`  | `int`    | The player's score        |
| `level`  | `int`    | The current level         |
| `time`   | `double` | The amount of time played |

### Constructors

```java
Game()
```

Creates a Game with all values set to `0`.

```java
Game(int score, int level, double time)
```

Creates a Game with the given score, level, and time.

### Example

```java
Game game = new Game(1500, 3, 42.5);
```

---

## Pizza

Represents a pizza.

### Instance Variables

| Variable   | Type     | Description               |
| ---------- | -------- | ------------------------- |
| `slices`   | `int`    | The number of slices      |
| `diameter` | `double` | The diameter of the pizza |
| `price`    | `double` | The price of the pizza    |

### Constructors

```java
Pizza()
```

Creates a Pizza with all values set to `0`.

```java
Pizza(int slices, double diameter, double price)
```

Creates a Pizza with the given number of slices, diameter, and price.

### Example

```java
Pizza pizza = new Pizza(8, 14.0, 18.99);
```

---

## Flight

Represents a flight.

### Instance Variables

| Variable     | Type     | Description              |
| ------------ | -------- | ------------------------ |
| `passengers` | `int`    | The number of passengers |
| `distance`   | `double` | The distance traveled    |
| `altitude`   | `double` | The altitude             |

### Constructors

```java
Flight()
```

Creates a Flight with all values set to `0`.

```java
Flight(int passengers, double distance, double altitude)
```

Creates a Flight with the given number of passengers, distance, and altitude.

### Example

```java
Flight flight = new Flight(150, 1200.5, 35000.0);
```

---

# Classes for Nesting

These classes are especially useful for practicing an object that contains another object.

## Engine

Represents a car engine.

### Instance Variables

| Variable     | Type  | Description             |
| ------------ | ----- | ----------------------- |
| `horsepower` | `int` | The engine's horsepower |
| `cylinders`  | `int` | The number of cylinders |

### Constructors

```java
Engine()
```

Creates an Engine with both values set to `0`.

```java
Engine(int horsepower, int cylinders)
```

Creates an Engine with the given horsepower and number of cylinders.

### Example

```java
Engine engine = new Engine(250, 4);
```

---

## Address

Represents an address.

### Instance Variables

| Variable      | Type  | Description      |
| ------------- | ----- | ---------------- |
| `houseNumber` | `int` | The house number |
| `zipCode`     | `int` | The ZIP code     |

### Constructors

```java
Address()
```

Creates an Address with both values set to `0`.

```java
Address(int houseNumber, int zipCode)
```

Creates an Address with the given house number and ZIP code.

### Example

```java
Address address = new Address(19, 8648);
```

---

## Processor

Represents a computer processor.

### Instance Variables

| Variable | Type     | Description                   |
| -------- | -------- | ----------------------------- |
| `cores`  | `int`    | The number of processor cores |
| `speed`  | `double` | The processor speed           |

### Constructors

```java
Processor()
```

Creates a Processor with both values set to `0`.

```java
Processor(int cores, double speed)
```

Creates a Processor with the given number of cores and speed.

### Example

```java
Processor processor = new Processor(8, 4.2);
```

---

# Suggested Nesting Examples

Once you are ready to put objects inside other objects, these combinations work well:

### Car → Engine

```java
Engine engine = new Engine(250, 4);

Car car = new Car(2020, 45000);
car.engine = engine;
```

### Person → Address

```java
Address address = new Address(19, 8648);

Person person = new Person();
person.age = 41;
person.address = address;
```

### Computer → Processor

```java
Processor processor = new Processor(8, 4.2);

Computer computer = new Computer();
computer.processor = processor;
```

The important idea is that an **instance variable does not have to be an `int` or `double`**. It can also be another class.

For example:

```java
public Engine engine;
```

means that a `Car` has an instance variable whose type is `Engine`.

This allows objects to be built from other objects.
