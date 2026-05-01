# 🍵 Cafe Billing System

A comprehensive desktop billing application built with Python Tkinter for small cafes and restaurants. This system allows cashiers to quickly generate bills, apply discounts, and maintain customer records.

## 🎯 Overview

This Cafe Billing System is designed to streamline the counter sales process in small food establishments. It replaces manual calculations with an automated system that handles item selection, quantity management, discount application, and professional receipt generation.

**Course:** Artificial Intelligence / Python Programming Lab  
**Topic:** Tkinter GUI Widgets - Label, Entry, Button, Frame, Text  
**Lab:** 10 - Working with Widgets through a Real-Time Billing System

## ✨ Features

### Core Functionality
- ✅ **Customer Information Management**
  - Name and contact number collection
  - Input validation with real-time error checking
  
- ✅ **Item Management**
  - Predefined menu items (Tea, Coffee, Sandwich, Burger, Fries, Juice)
  - Auto-fill price on item selection
  - Quantity management
  
- ✅ **Discount System**
  - Percentage-based discounts
  - Fixed amount discounts
  - Discount validation (no negative values, percentage ≤ 100%)
  
- ✅ **Billing Calculations**
  - Subtotal calculation
  - Discount application
  - GST calculation (5%)
  - Final total computation
  
- ✅ **Receipt Generation**
  - Professional formatted receipt
  - Store information header
  - Itemized billing
  - Thank you message
  
- ✅ **User Interface**
  - Clean, intuitive layout
  - Color-coded sections
  - Responsive buttons
  - Scrollable receipt area

### Validation Rules
| Field | Validation Rule |
|-------|----------------|
| Customer Name | Alphabets only, 2-50 characters |
| Contact Number | Numeric only, 8-15 digits |
| Price | Positive number, max 2 decimals |
| Quantity | Positive integer, max 1000 |
| Discount | Non-negative, ≤ 100% for percentage |

## 🛠️ Technologies Used

- **Python 3.8+** - Core programming language
- **Tkinter** - GUI framework (built-in)
- **Regex (re)** - Input validation
- **Datetime** - Timestamp generation

## 💻 Installation

### Prerequisites
- Python 3.8 or higher installed on your system
- pip package manager

### Step-by-Step Installation

1. **Clone the repository**
```bash
git clone https://github.com/AtqaAsma016/cafe-counter-billing-system-AIlab9.git
cd tkinter-cafe-billing-system
