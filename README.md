# swift-studies

## doing your first hello world

```swift
print("Hello World")
```

## Variables & constants

### declare a variable

- to declare a variable in swift use:  ```var```
  + variables is useful when you need to manipulate a value

#### example:

```swift
var amount = 1
amount += 1

print(amount) //output 2
```

### declare a constant

- to declare a constant in swift use:  ```let```
  + constants is useful when you don't want a value can be mutable

#### example:

```swift
let pi: Double = 3.14
```

---

## Basic types

- Int: integers
- Double: floating-point numbers
- String: a sequence of characters
- Bool: true/false

#### examples:

```swift
var age: Int = 27

var price: Double = 1.99

var message: String = "this is good"

var lateToWork: Bool = true
```

--- 

## Arithmetic Operators

- ```+``` addition
- ```-``` subtraction
- ```*``` multiplication
- ```/``` division
- ```%``` remainder

#### you can use with compound assignment operators too:

```swift
var age: Int = 30

age += 1 //31
age -= 1 //30
age *= 2 //60
age /= 2 //30
age %= 2 //0
```

---

## String Interpolation

- string interpolation is very easy in swift:

```swift
var price: Double = 299.99

print("this xbox one series s costs \(price) dollars")

//output: this xbox one series s costs 299.99 dollars
```



## Else If statement

```swift
var fruit: String = "banana"

if fruit == "banana" {
  print("🍌")
} else if fruit == "grape" {
  print("🍇")
} else if abbreviation == "apple" {
  print("🍎")
} else {
  print("fruit emoji not found")
}
```



## Ternary

```swift
var fruit: String = "apple"


fruit === "apple" ? print("🍎") : print("Ops, it not an apple")
```



## Switch

```swift
var fruit: String = "banana"

switch fruit{
    case "banana":
      print("🍌")
    case "grape":
      print("🍇")
    case "apple":
      print("🍎")
    default:
      print("fruit emoji not found")
}
```

## Switch Interval

```swift
var num: Int = 2
 
switch num {
  case 1...10:
    print(num*10) 
  case 11...20:
    print(num*20)
  case 21...30: 
    print(num*30)
  default: 
    print(num)
} 
```

## Switch Compose

```swift
var animals: String = "Dog"


switch animal {
    case "Dog", "Cat", "Rabbit":
        print("land")
    case "Fish", "Shark": 
        print("aquatic")
    default:
        print("ops")
}
```