
![Logo](https://res.cloudinary.com/dkgxkekb6/image/upload/v1711189934/l2iag3qdaupxdosjacaz.png)


# EventHive: Streamlining College Event Ticketing and Verification
Welcome to EventHive, your go-to platform for hassle-free college event ticket booking and verification. Designed to streamline the entire process, EventHive offers a seamless experience for event organizers and attendees alike. Say goodbye to long queues and confusion at the entrance – with EventHive, managing and attending college events has never been easier.



## Demo

https://github.com/VishalRMahajan/EventHive/assets/111660265/84551f58-76bf-4a48-9c38-afd840f2aa3c


## Problem Statement

College events often face challenges with ticket booking and verification processes, leading to long queues, manual errors, and confusion. Organizers struggle to efficiently manage ticket sales and verify attendees, resulting in a poor user experience. Attendees, on the other hand, face inconvenience and delays during event entry. These issues highlight the need for a streamlined ticketing and verification system to enhance the overall event experience for both organizers and attendees.
## How It Works

1. **Registration**: Users register for an account using their @student.sfit.ac.in email.
2. **Login**: Students log in with their @student.sfit.ac.in email, and committee members log in with @sfit.ac.in email.
3. **Dashboard**: Both students and committee members access a common dashboard.
4. **Event Details**: Students can view event details on the dashboard, including event information and ticket availability.
5. **Ticket Purchase**: Students can buy tickets by clicking on the "Buy Ticket" button, which redirects them to the Razorpay payment gateway for online payment.
6. **Payment Confirmation**: After successful payment, a QR code is sent to the student's email for ticket authentication.
7. **QR Code Scan and Ticket Verification**: At the event, the QR code on the ticket is scanned for authentication and verification.
8. **Ticket Management**: Students can view their tickets by clicking on the "Tickets" button on the dashboard.
9. **Committee Functions**: Committee members can add events and view the list of students who have booked tickets.

## Tech Stack

- **Frontend Framework**: [Reflex](https://github.com/reflex-dev) (Python framework for frontend and backend)
- **Backend Framework**: FastAPI (Python framework for building APIs)
- **Database**: [PostgreSQL](https://github.com/postgres/postgres) (for storing data)
- **Payment Gateway Integration**: Razorpay (for online payment processing)
- **Cloud Storage**: Cloudinary (for storing and managing images, including QR codes)
- **Email Service**: SMTP (for sending emails)
- **QR Code Generation**: Python QR Code (for generating QR codes dynamically)
- **Web Server**: Uvicorn (ASGI server for hosting the FastAPI backend)
- **Version Control**: Git (for version control, including submodules)



## Results
The implementation of EventHive has streamlined ticket booking, eliminating long queues and reducing entry wait times. Attendees now enjoy a seamless event entry experience, enhancing overall satisfaction. Organizers benefit from improved ticket management, real-time sales tracking, and efficient attendee verification, enhancing operational efficiency.
## Conclusion
EventHive transforms college event management by leveraging technology to simplify ticketing and verification processes. Its user-friendly interface and efficient features make it a valuable tool for colleges looking to enhance their event experiences.
## Repository Structure

- EventHive (Main Repository)
  - Frontend (Submodule - Frontend_reflex)
  - Backend (Submodule - Backend_Fastapi)
## Future Scope

- **Integration with Campus Systems**: Integrate EventHive with existing campus systems for seamless event management.
- **Enhanced Analytics**: Provide detailed analytics and reporting features for better event planning.
- **Mobile App**: Develop a mobile app for easier ticket booking and event access.
- **Integration with Social Media**: Allow attendees to share event details and invite friends through social media platforms.
- **Interactive Event Features**: Introduce interactive features such as live polls and Q&A sessions to enhance attendee engagement.


## References

- [Reflex Docs](https://reflex.dev/docs/ui/overview/)
- [FastAPI Docs](https://fastapi.tiangolo.com/)
- [Razorpay Docs](https://razorpay.com/docs/)
