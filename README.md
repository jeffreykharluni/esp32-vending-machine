# esp32-vending-machine
IoT vending machine that dispenses items after Razorpay payment
# ESP32 Smart Vending Machine

This project demonstrates a smart IoT vending machine powered by an ESP32 microcontroller,
AWS IoT Core, and Razorpay payment integration.

When a customer completes a payment, the ESP32 receives a dispense command via AWS IoT.
If the device was offline for more than 2 minutes, it automatically requests a refund
through an AWS Lambda function connected to Razorpay API.

**Technologies used:**
- ESP32 (Arduino framework)
- AWS IoT Core & AWS Lambda
- Razorpay API (for payments & refunds)

