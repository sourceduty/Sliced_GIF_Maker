![Sliced GIF Example](https://github.com/sourceduty/Sliced_GIF_Maker/assets/123030236/abd70052-16e8-4db1-a9de-98f2a113ba55)

> Create a unique GIF using uploaded image files.

#

This Python GUI program, developed for image processing and GIF creation, provides an intuitive interface for users to transform their images into dynamic animations. By leveraging the tkinter library for the graphical user interface and the PIL (Pillow) library for image manipulation, the application offers robust functionality wrapped in a user-friendly design. The main workflow involves loading an image from the user’s file system, processing it into equal square pieces, and then incrementally assembling these pieces into a series of frames that compile into a GIF. The final touch ensures the GIF ends with the complete image displayed for two seconds, creating a seamless and polished animation effect.

![Sliced GIF Maker](https://github.com/sourceduty/Sliced_GIF_Maker/assets/123030236/718ba0b2-4d33-4b82-bf4d-96a81cd3fd05)

The program begins with a straightforward "Load Image" button that allows users to select their desired image. Once an image is loaded, the "Create GIF" button becomes active. This button initiates the process of dividing the image into a specified number of equal parts. Each of these parts is then sequentially added back to a new image frame, simulating the assembly of the image piece by piece. This sequence of frames is saved as a GIF, ensuring the resulting animation is both captivating and of high quality. Throughout this process, a text box within the GUI provides real-time updates on the progress, enhancing user engagement and transparency.

A key feature of this program is its adaptability. Users can adjust the number of pieces the image is divided into, offering flexibility in the complexity and length of the resulting GIF. Moreover, the program's design ensures that the final GIF maintains the original dimensions of the loaded image, preserving its quality and resolution. The last frame's extended display time enhances the viewer's experience by providing a moment of rest and recognition of the complete image. This combination of technical precision and thoughtful user experience design makes the program a powerful tool for both casual users and those needing a reliable image processing solution.

***
Copyright (C) 2024, Sourceduty - All Rights Reserved.
