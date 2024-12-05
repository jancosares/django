# SMS Signup Application

**_Django Application for Sending SMS_**

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

## Images

![Screenshot 2024-12-02 125700](https://github.com/user-attachments/assets/d9fc6a80-c343-490f-ad58-1397a6157a42)

![Screenshot 2024-12-02 124849](https://github.com/user-attachments/assets/01691c75-4b54-46e6-8cae-f0badd964659)

![Screenshot 2024-12-02 125350](https://github.com/user-attachments/assets/d80e23ce-1bfd-4405-bcb2-c65ab3cd807d)

![sms](https://github.com/user-attachments/assets/cee5b4f7-139b-4741-af07-72106c5f5b38)

![Screenshot 2024-12-02 125638](https://github.com/user-attachments/assets/b1181518-dac4-48e3-bcbf-c9737f41596a)



