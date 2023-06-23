# MOBILE_APPLICATION_FOR_TRANSFERRING_IMAGES_TO_A_RASPBERRY_PI_CARD

Functionalities:

Requesting and handling runtime permissions: The app requests the user's permission to read external storage in order to access and upload images.

Image selection: The app allows the user to select an image from their device's storage using the system's file picker.

Image upload: The selected image is uploaded to a server using a multipart upload request. The app sends the image file, along with additional parameters (name and email), to the server.

Server-side image handling: The server-side PHP script receives the uploaded image and saves it on the server. It creates a directory if necessary and saves the image with a unique filename. It also inserts the image path into a database (optional functionality).

Technologies:

Android: The app is developed using the Android platform, specifically using the Java programming language.

PHP: The server-side code is written in PHP, which is a server-side scripting language commonly used for web development.

Apache Server: The PHP script is hosted on an Apache server, which provides the environment for executing the PHP code and serving the HTTP requests.

Overall, the project combines Android app development, image handling, file upload, and server-side scripting with PHP to provide a functionality that allows users to select and upload images from their Android devices to a server.
