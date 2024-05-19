Toast Notification



This repository provides a simple implementation of toast notifications using HTML, CSS, and JavaScript. Toast notifications are brief, auto-expiring messages that pop up on the user interface to give feedback or display information.

Features


Easy to integrate and use
Customizable appearance
Auto-dismiss after a set duration
Support for multiple toast notifications
Table of Contents
Installation
Usage
Customization
Examples
Contributing
License
Installation
Clone the repository or download the source files.

bash
Copy code
git clone https://github.com/your-username/toast-notification.git
cd toast-notification
Include the CSS and JavaScript files in your HTML file.

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="toast.css">
    <title>Toast Notification</title>
</head>
<body>
    <script src="toast.js"></script>
</body>
</html>
Usage
To display a toast notification, call the showToast function with the desired message and options.

html
Copy code
<button onclick="showToast('This is a toast notification!')">Show Toast</button>
javascript
Copy code
// Example usage
showToast('This is a toast notification!');
Customization
You can customize the appearance and behavior of the toast notifications by modifying the options passed to the showToast function.

Options
message (String): The message to be displayed in the toast notification.
duration (Number): The duration in milliseconds before the toast disappears. Default is 3000 ms.
type (String): The type of toast notification (e.g., 'success', 'error', 'info'). Custom styles can be applied based on the type.
Example
javascript
Copy code
showToast('Success! Your action was completed.', {
    duration: 5000,
    type: 'success'
});
CSS Customization
Modify the toast.css file to customize the look and feel of the toast notifications. You can change colors, fonts, positioning, and animations.

css
Copy code
/* Example CSS for success type toast */
.toast.success {
    background-color: #4caf50;
    color: white;
}

/* Example CSS for error type toast */
.toast.error {
    background-color: #f44336;
    color: white;
}

/* Example CSS for info type toast */
.toast.info {
    background-color: #2196f3;
    color: white;
}
Examples
Here are a few examples of how to use the toast notification system.

Basic Toast
javascript
Copy code
showToast('This is a basic toast notification.');
Success Toast
javascript
Copy code
showToast('Operation was successful!', { type: 'success' });
Error Toast
javascript
Copy code
showToast('An error occurred!', { type: 'error' });
Custom Duration Toast
javascript
Copy code
showToast('This will last longer.', { duration: 10000 });
Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Enjoy your toast notifications! If you have any questions or feedback, feel free to contact us.








