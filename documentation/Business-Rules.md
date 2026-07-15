
# 📘 Business Rules

## Overview

This document outlines the business logic used in the Hospitality Sales & Reservation Analytics dashboard.

---

## Revenue

- Revenue includes only confirmed reservations.
- Cancelled and No-Show bookings are excluded.
- Revenue is aggregated at the property and booking date level.

---

## Occupancy

- Occupancy is calculated using occupied rooms divided by available rooms.
- Daily occupancy is aggregated to monthly values for trend reporting.

---

## Booking Analysis

- Booking trends are based on reservation creation date.
- Booking channels are grouped into Direct, OTA, Corporate, and Other.

---

## Target Achievement

- Monthly targets are compared against actual revenue.
- Achievement percentage is calculated as:

Achievement % = Actual Revenue / Target Revenue × 100

---

## Lead Management

- Only active leads are included.
- Closed or duplicate leads are excluded.

---

## OTA Performance

- OTA contribution is calculated based on revenue generated from online travel agencies.
- Channel-wise performance is displayed for comparison.

---

## Data Refresh

- Data is automatically refreshed using Google Apps Script.
- Dashboard reflects the latest available data from the source system.
