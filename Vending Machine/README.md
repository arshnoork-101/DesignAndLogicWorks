# Vending Machine System

This directory contains the pseudo code for a **Vending Machine System**, covering the flow from item selection to payment and cancellation.

## Overview

The system operates through four key states:

1. **Idle State**: Awaits user interaction, guiding them to select items.
2. **Active State**: Manages item selection, quantity input, and validates stock.
3. **Payment State**: Processes payments via multiple options.
4. **Cancel State**: Handles order cancellations and resets the system.

The `main.txt` file outlines the main workflow, initializing the system, calling relevant modules (`Idle`, `Active`), and transitioning to the **Payment State** when the user proceeds to checkout. If no payment is made, the system remains in the **Active State**.

## Key Features

- **Order Management**: Select items and specify quantities, with real-time stock checks.
- **Payment Processing**: Supports multiple payment methods (Credit Card, Bank Card, NFC, Vending App).
- **Inventory Control**: Automatically updates stock and alerts operators for low stock.

## How It Works

1. Initialization defines the states and sets up the inventory/session.
2. The system starts in the **Idle** state, transitioning to **Active** for item selection.
3. Upon pressing the pay button, the system moves to the **Payment** state.
4. If no payment is made, the system stays in **Active** until the process is completed or cancelled.

