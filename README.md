# Nodemailer Form with Next.js and Tailwind CSS

This is a simple example of a contact form built using Next.js and Tailwind CSS, with the ability to send emails using the Nodemailer library. This project aims to provide a starting point for integrating a contact form into your Next.js application.

## Prerequisites

Before getting started, ensure that you have the following installed on your machine:

- Node.js (version 12 or higher)
- NPM (Node Package Manager)

## Getting Started

To set up the project locally, follow these steps:

1. Open a terminal Clone `https://github.com/maryamtufail/nodemailer_form_nextjs.git` to your local machine or download the source code as a ZIP file.
2. Run cd `nodemailer_form_nextjs` .
3. Run `npm install` to install the project dependencies.
4. Create a `.env.local` file in the project root and provide the necessary environment variables (see the **Environment Variables** section below for details).
5. Run `npm run dev` to start the development server.
6. Open your browser and visit `http://localhost:3000` to see the form in action.


## Environment Variables

The following environment variables are required to configure the email service:

- `GMAIL_USER`= YOUR_EMAIL
- `GMAIL_PASSWORD`= YOUR_PASSCODE

### What is PASSCODE?
This is not your email passwords. 

- Go to `https://shorturl.at/rKTZ9` or `Access your google account > Security > 2-Step Verification > App Passwords (Scroll down at bottom see this)`
- Open App passwords: `select app > Other > Write nodemailer` 
- Click generate. copy that code it is your PASSCODE.

Make sure to provide appropriate values for these variables in your `.env.local` file.

Feel free to modify the project structure as per your requirements.

## Acknowledgements

This project was inspired by the following resources:

- Next.js: [https://nextjs.org/](https://nextjs.org/)
- Tailwind CSS: [https://tailwindcss.com/](https://tailwindcss.com/)
- Nodemailer: [https://nodemailer.com/](https://nodemailer.com/)


## Conclusion

With this simple setup, you can easily add a contact form to your Next.js application using Tailwind CSS for styling and Nodemailer for sending emails. Customize the form, add validation, and enhance the functionality to meet your specific requirements. 

Happy coding!

