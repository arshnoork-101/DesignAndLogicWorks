# Car Wash System Flowchart

This repository contains a flowchart outlining the logic for a car wash system, covering membership validation, wash selection, payment processing, and car wash activation.

---

## System Features

1. **Membership System**:
   - Unique `MemberNum` scanned via barcode.
   - Members get up to **3 washes/day**, with extra washes charged at **double price**.
   - Pre-selected wash types available for members.

2. **Wash Options**:
   - **Basic Wash**: $5.75  
   - **Clean Wash**: $8.60  
   - **Super Clean Wash**: $11.55  
   - Non-members manually select their wash type.

3. **Payment and Validation**:
   - Calculates payment based on wash type and membership.
   - Validates payment before activating the wash.

4. **Error Handling**:
   - Handles invalid inputs, failed payments, and barcode detection issues.

---

## Process Overview

1. **Scan or Select**: Users scan their barcode or manually choose a wash type.  
2. **Membership Check**: Validates `MemberNum` and pre-selected wash.  
3. **Daily Limit**: Checks usage; charges extra for exceeding 3 washes/day.  
4. **Payment**: Calculates and validates payment.  
5. **Activation**: Activates wash upon successful payment.

You can check out the jpg file to get through the flowchart concisely.
