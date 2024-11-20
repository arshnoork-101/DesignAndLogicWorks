# Paint Estimator App

This repository provides a paint estimation system that calculates the amount of paint required for a room, including the number of cans for both base and finishing coats, and generates a cost breakdown.

## Files

- **`areacalculation.txt`**: Calculates the total area to be painted by considering wall and ceiling dimensions, including objects (windows/doors) that shouldn't be painted.
- **`cancalculation.txt`**: Determines the number of cans required for both base and finishing coats, based on the calculated area.
- **`main.txt`**: Coordinates area and can calculations, then computes the total cost (including taxes) and displays a detailed receipt.

## Process Flow

1. **Area Calculation**:
   - Collect room and wall dimensions.
   - Subtract areas for objects like windows/doors.
   - Calculate the ceiling area as rectangles.

2. **Can Calculation**:
   - Based on the area, the required number of base and finishing cans are calculated. Users can input the number of coats, with the system suggesting a default.

3. **Cost Calculation**:
   - Calculate total cost based on the number of cans, including taxes, and display a receipt with detailed breakdowns.

## Features

- **Area Estimation**: Calculates the area of walls and ceiling.
- **Paint Can Estimation**: Determines the number of cans required based on area coverage.
- **Cost Breakdown**: Provides a receipt with total costs, including taxes.

## Usage

1. Enter room dimensions and any objects on the walls that don’t need painting.
2. Calculate the ceiling area by dividing it into rectangles.
3. The system estimates the number of paint cans required.
4. A detailed receipt is generated, showing the total cost and tax.

---

This tool simplifies the paint estimation process by calculating the area, determining the number of cans, and providing a cost breakdown for painting a room.

---

You can check out the files available and the detailed presentation made to know the process in detail.

