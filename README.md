

1. Hospital Outpatient Appointment Scheduling
Domain: Healthcare Operations

Problem: Outpatient departments in hospitals often use static, manually-managed appointment slots, leading to long patient wait times, doctor idle time, and overbooking during peak hours — while other slots go unused.

Objective: Build a scheduling system that:

Dynamically allocates appointment slots based on doctor availability, expected consultation time (varies by case type), and patient priority (emergency vs. routine).
Predicts no-show probability using historical data and overbooks intelligently to offset it.
Re-optimizes the schedule in real time when cancellations or delays occur.
Efficiency core: This is a dynamic scheduling/bin-packing problem — minimizing total patient wait time and doctor idle time simultaneously.
