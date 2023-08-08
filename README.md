# Virtual_Trial_Room
Virtual_Trial_Room_ECartom_ECart
A real-time virtual dressing room system that enables users to try on clothes virtually. The system consists of multiple tasks, including face detection from a video stream, model alignment, approximation of torso and lower body positions based on face detection, and dress-up using image processing techniques.

#Motivation
MICROSOFT, among its various innovative products, introduced the Kinect, showcasing its potential applications. One of the applications presented was the Virtual Dressing Room, which addressed a similar problem statement. However, the existing model was limited to showrooms that could afford and possess the Kinect setup. To overcome these technical and hardware barriers, we developed a product that allows any user with a basic RGB camera on their device to experience a virtual dressing room. This extends the application to online shopping users and smaller businesses that may not have opted for the costly Kinect.

Day-to-Day Implementation and Touchless Shopping
In the wake of the COVID-19 pandemic, touchless shopping experiences have gained popularity across various industries, including the clothing industry. The virtual trial room model described here aligns with this trend and offers a convenient and safe solution for trying on clothes without physical contact.

By leveraging a basic RGB camera available on users' devices, this virtual trial room system eliminates the need for expensive hardware like the Kinect, making it accessible to a wider range of users, including online shoppers and smaller businesses.

The key benefits and day-to-day implementation of this model in the clothing industry include:

Contactless Try-On Experience: Customers can virtually try on clothes without physically wearing them, reducing the risk of contamination and providing a hygienic shopping experience.
Enhanced Convenience: Users can try on different combinations of shirts and pants from the comfort of their homes, saving time and effort compared to traditional trial rooms.
Improved Decision-Making: The system allows customers to visualize how different clothing items will look on them, facilitating better decision-making and reducing the chances of purchasing unsuitable items.
Increased Customer Engagement: Virtual trial rooms provide an interactive and engaging shopping experience, attracting and retaining customers through innovative technology.
Business Expansion Opportunities: Smaller businesses that may not have the resources to set up physical trial rooms or afford expensive equipment like the Kinect can now offer virtual trial room experiences, expanding their reach and attracting a broader customer base.
#Use Instructions
To use the virtual trial room model, follow these instructions:

Install the required dependencies by running the following commands:

pip3 install opencv-python pip3 install flask

Run the flasktry.py file.

Access the application by navigating to localhost in your web browser.

On the main page, you will find a navbar with options to explore various shirts and pants.

Select the desired shirt and pant combinations, and click on "Predict" to see the result.

Prerequisites
To use the virtual trial room model, you need the following:

Webcam or an RGB camera on your device.
Technologies Used
The virtual trial room model utilizes the following technologies:

OpenCV: OpenCV is used for face detection from the video stream, model alignment, and image processing tasks.
Flask: Flask is used to create a web application for users to access and interact with the virtual trial room system.
Please note that this README.md file provides an overview of the virtual trial room basic model. For more detailed information and implementation, refer to the source code and relevant documentation.
