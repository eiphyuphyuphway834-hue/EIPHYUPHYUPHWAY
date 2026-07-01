# Week 5 Documentation

## 1.1 Problem Statement
A cafe needs a program to automatically calculate customer bills
instead of doing it manually by the cashier.

## 1.2 Inputs
- Customer name
- Quantity of Coffee
- Quantity of Tea
- Quantity of Sandwich

## 1.3 Outputs
- A receipt showing customer name, item quantities, and total bill in RM

## 1.4 Typical Process Flow
1. Cashier enters customer name
2. Cashier enters quantity for each item
3. Program calculates the total price
4. Program prints the receipt

## 1.5 Constraints
- Quantities must be whole numbers (no half items)
- Prices are fixed (Coffee: RM8.50, Tea: RM6.00, Sandwich: RM12.00)
- Total must be displayed with 2 decimal places

## 2. Problem Decomposition
- Task 1: Get input from user (name and quantities)
- Task 2: Calculate total based on quantities and fixed prices
- Task 3: Print a formatted receipt

## 3. Pseudocode
```
START
  INPUT customer_name, coffee_qty, tea_qty, sandwich_qty
  total = (coffee_qty x 8.50) + (tea_qty x 6.00) + (sandwich_qty x 12.00)
  PRINT receipt with customer name, quantities, and total
END
```