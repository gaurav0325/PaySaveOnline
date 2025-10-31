# Functional Requirements – PaySaveOnline

## Overview
PaySaveOnline is a browser-based digital payment assistant that detects hidden checkout fees such as FX mark-ups, DCC traps, and card surcharges.

## Key Functional Requirements
1. Detect checkout pages automatically using common patterns (e.g., `/checkout`, `cart`, `payment`).
2. Parse the merchant’s country, currency, and transaction total.
3. Match this against the user’s locally stored card profiles.
4. Identify potential FX, surcharge, or DCC losses.
5. Display an advisory tooltip beside the payment button within one second.
6. Maintain a local “savings dashboard” tracking avoided losses.
7. Ensure all advice is calculated locally; no personal data leaves the user’s device.
