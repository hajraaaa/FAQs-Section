# FAQ Section

This iOS application demonstrates how to implement a Frequently Asked Questions (FAQ) section using Swift and UIKit. The app utilizes the MVVM (Model-View-ViewModel) design pattern to manage the FAQ data and presentation.

## Features

- **FAQ List**: Displays a list of FAQs with expandable answers.
- **Expandable Cells**: Clicking on a question expands or collapses the answer.
- **MVVM Design Pattern**: Separates the model, view, and view model for better code organization.
- **Encapsulation**: Manages FAQ data and logic within the view model, abstracting it from the view controller.

## Components

- **FAQViewController**: The main view controller responsible for displaying the list of FAQs.
- **FAQViewModel**: Manages the FAQ data and handles the logic for expanding/collapsing answers.
- **FAQ**: A model representing an individual FAQ item.
- **FAQTableViewCell**: A custom table view cell used to display each FAQ.

## Installation and Setup

### Prerequisites

- Xcode 12 or later
- iOS 13.0 or later

### Steps to Run the App

**Clone the Repository**

git clone https://github.com/yourusername/faq-section-app.git

Replace yourusername with your GitHub username.

Open the Project in Xcode

Navigate to the project folder and open the .xcodeproj file. Xcode will launch the project.

**Build the Project**

Select your target device or simulator. Press Cmd + B to build the project.

**Run the Project**

Press Cmd + R to run the app on the selected device or simulator.

### How It Works
The app displays a list of FAQs using a UITableView. Each row represents a question, and the answer is shown when the row is expanded.
