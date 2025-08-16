# Lab 1: Task Squirrels
#### Z Number: Z23724811 
Name: Aryan Lakhani

## Description
Task Squirrels is a simple and interactive app designed to help parents encourage their children to complete chores. The app provides a list of tasks for users to complete. Users are required to attach photos to show that they have completed the task. After attaching the photo to a task, the app retrieves the location metadata from the photo and displays where the photo was taken on a map. This makes it easy for parents to verify that tasks have been completed as requested.
<br>



## Key Features

- **Attach Photos**: Users can attach photos to tasks to show proof of completion
- **Location Display**: The app retrieves and displays the location metadata from the attached photo, zooming in on the map to show where the photo was taken
- **Custom Map Annotations**: Instead of using a standard map pin, the app displays the attached photo as a custom annotation on the map
- **View Photo in Full Screen**: Users can tap the "View Photo" button to see the attached photo in detail


<br>


## GIF of the app running accordingly

![Simulator Screen Recording - iPhone 15 Pro - 2024-09-03 at 15 44 56](https://github.com/user-attachments/assets/a3d9886e-458c-412b-b570-1b694f02c9b4)

<br>


## GIF of creating a new task 

![Simulator Screen Recording - iPhone 15 Pro - 2024-09-03 at 16 03 35](https://github.com/user-attachments/assets/48fbbf6d-cd57-4355-8afb-597e99307571)

<br>


## Code Overview

The `TaskDetailViewController.swift` file handles the following:

- **Photo Library Access**: Requests permission to access the user’s photo library to select and attach photos to tasks.
- **Image Picker Presentation**: Displays an image picker to allow the user to choose a photo from their library.
- **Location Metadata Retrieval**: Extracts location metadata from the selected photo to determine where the task was completed.
- **Map View Display**: Displays the location where the attached photo was taken on a map, zooming in on the relevant area.
- **Custom Annotation**: Adds a custom annotation to the map, replacing the standard pin with the attached photo.
- **Photo Viewing**: Allows users to view the attached photo in full screen by tapping the "View Photo" button.








## Technologies Used

- **Swift**: The programming language used to develop the app
- **Xcode**: The integrated development environment (IDE) used for the app's development
- **PhotosUI**: Used for accessing and managing the user’s photo library
- **MapKit**: Used to integrate the map and display location data with custom annotations


