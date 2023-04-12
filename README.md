

# Typing_Website

This is a web development project built using MERN stack. Every time the user visits the website, a new sentence is displayed which is fetched through an API. Upon clicking the "Start" button, the user can start practicing typing. The time starts and if the letter matches, it will be displayed in green, otherwise, it will be displayed in red. The accuracy and words per minute (WPM) are shown dynamically while typing, along with the percentage of the sentence completed.

## Features

- Displays a new sentence on every visit
- Typing practice with real-time accuracy and WPM calculation
- Profile section to view user details, total accuracy, WPM, and time spent typing
- Contact us page to send inquiries and feedback
- Secure login, registration, and change password pages with JWT authentication
- The JWT token is added as a cookie with a validity of 30 days
- Built using various packages like React Router DOM, Material-UI, Express, Mongoose, Express, Nodemailer, and Formspree

## How to Use

1. Clone the repository to your local machine
2. Run `npm install` in both the client and server directories to install the required packages
3. Start the server: 
   - Navigate to the server directory in your terminal
   - Run `npm start` to start the server on port 3000
4. Start the client: 
   - Navigate to the client directory in your terminal
   - Run `npm start` to start the client on port 3001
5. Open your browser and go to `http://localhost:3001` to see the app

Note: The proxy is set up to redirect requests from the client to the server running on port 3000. If you change the server port, make sure to update the `proxy` field in the `package.json` file in the client directory to the new port number.



## Contribute

If you want to contribute to this project, feel free to submit a pull request. Please make sure to follow the code style and write descriptive commit messages.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
