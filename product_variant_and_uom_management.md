# Feature: Product Variant & Unit of Measure Management

## Short Description
Lets the system group related SKUs under one parent product (e.g., same
shirt in different sizes/colors) and handle items bought, stored, and
sold in different units (e.g., box, dozen, piece).

## Purpose
To avoid duplicate product records and prevent counting errors when the
same item is measured in different units.

## Main Functions/Activities
- Create a parent product with multiple child variants (size, color)
- Assign each variant its own SKU, price, and stock count
- Define base unit of measure (e.g., piece)
- Define conversions (1 box = 12 pieces)
- Convert units automatically when receiving or selling stock
- Display total stock across all variants of a product
