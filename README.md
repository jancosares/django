# Django Application for Sending SMS

# SMS Signup Application

This project is a Django-based backend application that implements a user signup feature with SMS notifications. 
Users can sign up with their email, password, and phone number, and receive a confirmation SMS upon successful registration.

## Features

1. *User Signup*: Register users with their email, password, and phone number.
2. *SMS Notification*: Sends a confirmation SMS to users using the Vonage SMS API.
3. *Admin Management*: Manage user information through the Django admin interface.

## Project Structure

- *sms_service*: Contains the main app with views, models, and utility functions for SMS integration.
- *backend*: The core Django project settings, URLs, and configurations.

## How It Works

1. *User Signup*:
   - Endpoint: /api/signup/
   - Method: POST
   - Required Fields: email, password, phone_number
   - On successful signup, an SMS is sent to the provided phone number.

2. *SMS Integration*:
   - Utilizes the Vonage SMS API to send SMS.
   - Configuration is loaded from a .env file.

3. *Admin Panel*:
   - View and manage user information (UserInfo) through the Django admin interface.
