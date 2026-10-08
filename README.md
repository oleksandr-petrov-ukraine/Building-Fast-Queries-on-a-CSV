# Building Fast Queries on a CSV

A Python project focused on working with CSV data and improving the performance of data lookup operations.

The project uses a laptop inventory dataset stored in a CSV file and demonstrates how different data structures and search algorithms can be used to make queries more efficient.

## Project Overview

The project starts with reading and processing the `laptops.csv` dataset and gradually builds an `Inventory` class with optimized lookup methods.

The main goal is to compare different approaches and understand how data structures affect time complexity and execution speed.

## What I Practiced

- Reading and processing CSV files with Python's `csv` module
- Working with classes and methods
- Searching for records using a linear search
- Building a dictionary index for faster ID lookups
- Using sets to optimize price-based searches
- Sorting data by price
- Implementing binary search
- Comparing the execution time of different approaches
- Analyzing time complexity and performance

## Main Features

### Laptop ID Lookup

The project implements two approaches for finding a laptop by its ID:

- Linear search through the list of rows
- Dictionary-based lookup using a precomputed ID index

The dictionary-based approach provides significantly faster lookups.

### Two Laptop Promotion

The project checks whether two laptops can be purchased for a given budget.

The initial solution uses nested loops, while the optimized solution uses a set of laptop prices to improve performance.

### Laptops Within a Budget

Laptop records are sorted by price and binary search is used to efficiently find the first laptop exceeding a specified budget.

The method returns up to five matching laptops to keep the displayed output manageable.

## Dataset

The project uses `laptops.csv`, containing information about 1,303 laptops, including:

- ID
- Company
- Product
- Type
- Screen size
- CPU
- RAM
- Storage
- GPU
- Operating system
- Weight
- Price

## Technologies

- Python
- CSV
- Lists
- Dictionaries
- Sets
- Classes
- Linear search
- Binary search
- Time complexity analysis

## Project Goal

This project is part of my Python learning journey toward becoming a Junior Python Data Engineer.

It focuses on understanding how to work with structured data and how choosing the right data structure or algorithm can significantly improve query performance.