# 🚀 Quantity Measurement Application  
## 📏 Test-Driven Development (TDD) | OOP | Clean Code | DRY Principle  

---

## 🧠 Project Overview

The **Quantity Measurement Application** is designed to validate equality, conversion, and arithmetic operations between different measurement units such as Feet, Inches, Yards, etc.

This project was implemented incrementally using:

- ✅ Test-Driven Development (TDD)
- ✅ Feature Branch Workflow
- ✅ Clean Code Practices
- ✅ DRY (Don't Repeat Yourself) Principle
- ✅ Proper Unit Conversion Strategy

---

# 🌳 Git Workflow

```
main
 └── dev
      ├── feature/UC1-FeetEquality
      ├── feature/UC2-InchEquality
      ├── feature/UC3-GenericLength
      ├── feature/UC4-YardEquality
      ├── feature/UC5-UnitConversion
      ├── feature/UC6-UnitAddition
      ├── feature/UC7-TargetUnitAddition
      ├── feature/UC8-StandaloneUnit
      ├── feature/UC9-WeightEquality
      ├── feature/UC10-GenericQuantity
      ├── feature/UC11-VolumeMeasurement
      ├── feature/UC12-SubtractionAndDivision
      ├── feature/UC13-CentralizedArithmeticLogic
      └── feature/UC14-TemperatureMeasurementwithSelectiveArithmetic
```

---

## 📅 17 Feb 2026  
### 🔹 UC1 – Feet Measurement Equality 
**Branch:** `feature/UC1-FeetEquality`

### 🎯 Objective
- Validate equality of two Feet measurements  
- Implement proper `equals()` method  
- Follow TDD approach  

### ✅ Implementation
- Created Feet class  
- Implemented equality logic  
- Handled null and type safety  
- Wrote JUnit 5 test cases  
- [feature/UC1-FeetEquality](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC1-FeetEquality)

---

## 📅 18 Feb 2026  
### 🔹 UC2 – Feet and Inches Measurement Equality  
**Branch:** `feature/UC2-InchEquality`

### 🎯 Objective
- Compare Feet and Inches  
- Ensure 12 inches = 1 foot  

### ✅ Implementation
- Introduced conversion logic  
- Implemented base unit comparison  
- Improved equality handling  
- [feature/UC2-InchEquality](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC2-InchEquality)

---

## 📅 19 Feb 2026  
### 🔹 UC3 – Generic Quantity Class (DRY Principle)  
**Branch:** `feature/UC3-GenericLength`

### 🎯 Objective
- Remove duplication  
- Introduce reusable `Quantity` class  
- Apply DRY principle  

### ✅ Implementation
- Centralized conversion logic  
- Removed unit-specific duplication  
- Improved abstraction  
- [feature/UC3-GenericLength](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC3-GenericLength)

---

## 📅 20 Feb 2026  
### 🔹 UC4 – Extended Unit Support  
**Branch:** `feature/UC4-YardEquality`

### 🎯 Objective
- Support additional units (Yard, etc.)  
- Make system scalable  

### ✅ Implementation
- Introduced Unit Enum  
- Base unit conversion mapping  
- Easily extensible structure  
- [feature/UC4-YardEquality](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC4-YardEquality)

---

## 📅 20 Feb 2026  
### 🔹 UC5 – Unit-to-Unit Conversion  
**Branch:** `feature/UC5-UnitConversion`

### 🎯 Objective
- Convert one unit into another  

### ✅ Implementation
- Implemented `convertTo()` method  
- Centralized conversion logic  
- Ensured precision-safe calculations  
- [feature/UC5-UnitConversoion](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC5-UnitConversion)

---

## 📅 20 Feb 2026  
### 🔹 UC6 – Addition of Two Length Units  
**Branch:** `feature/UC6-UnitAddition`

### 🎯 Objective
- Add two quantities correctly  

### ✅ Implementation
- Converted to base unit before addition  
- Accurate arithmetic operations  
- Clean and reusable method structure  
- [feature/UC6-UnitAddition](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC6-UnitAddition)

---

## 📅 20 Feb 2026  
### 🔹 UC7 – Addition with Target Unit Specification  
**Branch:** `feature/UC7-TargetUnitAddition`

### 🎯 Objective
- Add two quantities  
- Return result in specified target unit  

### ✅ Implementation
- Implemented `add(quantity, targetUnit)`  
- Converted result before returning  
- Maintained precision and scalability  
- [feature/UC7-TargetUnitAddition](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC7-TargetUnitAddition)

---

## 📅 21 Feb 2026  
### 🔹 UC8 – Refactoring Unit Enum to Standalone  
**Branch:** `feature/UC8-StandaloneUnit`

### 🎯 Objective
- Separate Unit enum from Quantity class  
- Improve modularity  
- Enable multi-category support  

### ✅ Implementation
- Moved Unit enum to standalone file  
- Improved separation of concerns  
- Increased flexibility for new categories  
- [feature/UC8-StandaloneUnit](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC8-StandaloneUnit)

---

## 📅 21 Feb 2026  
### 🔹 UC9 – Weight Measurement  
**Branch:** `feature/UC9-WeightEquality`

### 🎯 Objective
- Extend application to support Weight category  
- Maintain clean architecture  

### ✅ Implementation
- Introduced Weight units (Gram, Kilogram, etc.)  
- Implemented base unit conversion  
- Ensured category-safe equality  
- Prevented cross-category comparison (Length ≠ Weight)  
- [feature/UC9-WeightEquality](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC9-WeigthEquality)

---

## 📅 21 Feb 2026  
### 🔹 UC10 – Generic Quantity Class with Unit Interface for Multi-Category Support  
**Branch:**  `feature/UC10-GenericQuantity`

### 🎯 Objective
- Create a fully generic Quantity system  
- Support multiple measurement categories  
- Apply interface-based design  

### ✅ Implementation
- Introduced `Unit` interface  
- Implemented category-specific enums (LengthUnit, WeightUnit)  
- Created Generic `Quantity<T extends Unit>` class  
- Ensured:
  - Type-safe unit handling  
  - Category-safe operations  
  - Scalable architecture  
- [feature/UC10-GenericQuantity](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC10-GenricQuality)

📅 22 Feb 2026
🔹 UC11 – Volume Measurement

Branch: feature/UC11-VolumeMeasurement

🎯 Objective

Extend system to support Volume category

Maintain generic & scalable architecture

✅ Implementation

Introduced Volume units (Litre, Millilitre, etc.)

Implemented VolumeUnit enum implementing Unit interface

Enabled:

Category-safe equality

Cross-unit comparison within Volume

Ensured:

Volume ≠ Length

Volume ≠ Weight

Maintained DRY & Clean Architecture

[feature/UC11-VolumeMeasurement](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC11-VolumeMeasurement)

📅 23 Feb 2026
🔹 UC12 – Subtraction & Division

Branch: feature/UC12-SubtractionAndDivision

🎯 Objective

Introduce arithmetic operations beyond addition

✅ Implementation

Implemented:

subtract(quantity)

divide(quantity)

Used base unit conversion before operation

Ensured:

Type safety

Category safety

Precision-safe calculations

Prevented invalid operations across categories

Reused conversion logic (DRY)

feature/UC12-SubtractionAndDivision

📅 24 Feb 2026
🔹 UC13 – Centralized Arithmetic Logic

Branch: [feature/UC13-CentralizedArithmeticLogic](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC13-CentralizedArthematicLogic)

🎯 Objective

Remove duplication in arithmetic logic

Follow Single Responsibility Principle

✅ Implementation

Introduced centralized arithmetic handler

Used functional approach (like DoubleBinaryOperator)

Unified:

Addition

Subtraction

Division

Enabled reusable arithmetic engine

Improved maintainability & extensibility

Fully aligned with Clean Code & DRY

feature/UC13-CentralizedArithmeticLogic

📅 25 Feb 2026
🔹 UC14 – Temperature Measurement with Selective Arithmetic

Branch: feature/UC14-TemperatureMeasurementwithSelectiveArithmetic

🎯 Objective

Introduce Temperature category

Handle non-linear conversions (e.g., Celsius ↔ Fahrenheit)

✅ Implementation

Added TemperatureUnit enum

Implemented offset-based conversion logic

Restricted invalid arithmetic:

❌ Addition not allowed

❌ Subtraction not allowed (in some cases)

Allowed:

Equality comparison

Conversion

Introduced Selective Arithmetic Rule Engine

Ensured domain correctness (Temperature ≠ Length logic)

[feature/UC14-TemperatureMeasurementwithSelectiveArithmetic](https://github.com/Xxdhruvshriwastav/QuantityMeasurementApp/tree/feature/UC14-TempratureMesurement)


