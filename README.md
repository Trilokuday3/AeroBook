
# AeroBook

This project primarily focuses on the flight ticket booking process. This system allows users to search for available flights, book tickets, cancle bookings, and provide feedback. It automates key process such as generating and sending booking confirmation emails, ticket cancellations, and notes after receiving feedback.


## Requirements 
- numpy
- pandas
- reportlab

## Implementation
Booking a Ticket: Users can book a ticket by providing source and destination details, along with the desired flight date. It checks for available flights and confirms the booking, creating a ticket ID and sending a confirmation email with a PDF attachment.

Viewing Available Flights: Users can search for available flights by specifying the source and destination. The system displays a list of flights that match the criteria and shows details like flight ID, price, and available seats.

Sending Confirmation and Thank-You Emails: Once a booking is confirmed, a confirmation email with booking details is sent to the passenger. A thank-you email is also sent after booking or feedback submission.

Ticket Cancellation: Users can cancel a ticket using its ticket ID. A cancellation email is sent, and the system updates the booking history file accordingly.

Feedback System: Passengers can send feedback via email, and the system sends a thank-you email in response.

PDF Ticket Generation: A PDF file is generated for each booking, containing the ticket details and a watermark. This file is attached to the confirmation email.
## Features

- Sending Emails via SMTP
- Creating Multi-part Email Messages
- File Attachments
- Support for Different Email Provider
- Email Body Customization


## Screenshots

![Conformation Mail Image](https://github.com/Trilokuday3/AeroBoook/blob/main/AeroBook/Confirm_Image.jpg)

This is an auto-generated email sent after the user booked a ticket through AeroBook.



![Demo Ticket](https://github.com/Trilokuday3/AeroBoook/blob/main/AeroBook/img.jpg)

This is an auto-generated image of a ticket created after booking



![Cancellation Mail Image](https://github.com/Trilokuday3/AeroBoook/blob/main/AeroBook/Cancellation_Image.jpg)
 
This is an image of an auto-generated email sent after ticket cancellation



![Thankyou Mail Image](https://github.com/Trilokuday3/AeroBoook/blob/main/AeroBook/Feed_Back_Img.jpg)

This is an image of an auto-generated email sent after the user provided feedback
## Authors

- [@Trilokuday3](https://github.com/Trilokuday3)




