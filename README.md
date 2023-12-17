# Hurein B. Kaiser

Atlanta, GA | (706) 572-6520 | Hurein.Kaiser@uga.edu | [LinkedIn](http://www.linkedin.com/in/hurein-kaiser) 

## About Me

I am Hurein B. Kaiser, a Computer Systems Engineering student at the University of Georgia with certificates (in-progess) in Informatics and Financial Technology (FinTech). 

## Education

- **B.S. Computer Systems Engineering**
  - College of Engineering, University of Georgia, Athens, GA
- **Certificate in Informatics**
  - College of Engineering, University of Georgia, Athens, GA

## Skills & Languages

- **Programming Languages & Software Skills:**
  - Python • Java • C/C++ • MATLAB • Cloud Computing • Web Development (HTML/CSS) • Data Management (SQL) • Data Modeling • JavaFX • Flask • WordPress • Drupal • Arduino

- **Electrical Engineering & Electronics Skills:**
  - Digital Electronics • Power Electronics • Circuit Design • Control Systems • Embedded Systems • CAD Tools • Fault Diagnosis & Troubleshooting • Lab Equipment Operation

## Projects
### Secure Transit: A JavaFX Application for Transport Security Updates in Leeds

- Integrated External APIs:
  - Integrated with the **TransportAPI** to retrieve bus route details in Leeds.
    - Parameters included `app_id` and `app_key` for authentication.
  - Utilized the **UK Police API** to fetch crime data in the vicinity of selected bus stops.
    - Parameters: Latitude (`lat`), Longitude (`lng`), and Date (`date`).

- Some JavaFX Components:
  - **Tabs:** Utilized a `TabPane` to organize and display incident information.
    - Implemented a set of `Tab` objects for each displayed incident, preventing unnecessary closability.
  - **Dropdown Menus:**
    - Created dropdown menus for selecting towns and bus stops using `ComboBox`.
  - **Buttons:**
    - Implemented various buttons for fetching crime data (`getResult`), navigating through incidents (`nextButton` and `backButton`), and managing entries (`startButton` and `endButton`).
    - Disabled or enabled buttons based on specific conditions, ensuring a controlled user experience.
    - Included options to start over (`startButton`) or jump to the end (`endButton`) for easier navigation.
- **Threaded Background Tasks:**
  - Implemented background tasks using threads to prevent UI freezing during long-running operations.
  - Created a daemon thread (`threadSmasher`) to execute tasks asynchronously, ensuring a responsive user interface.

- **Error Handling and User Feedback:**
  - Provided error handling mechanisms to deal with exceptions during API requests.
  - Displayed informative alerts to users in case of invalid input or API request failures.

- **Progress Bar:**
  - Incorporated a progress bar (`progressBar`) to visually indicate the status of background tasks, improving user feedback.
  
### Product Management System: Informatics Project

- Data Entry Tool with Flask:
  - Created a user-friendly interface for seamless product data entry.
  - Implemented a data entry tool with Flask, preventing users from proceeding without entering essential product details.

- Flask Routes and Views:
  - Developed routes and views in Flask to render HTML templates, process form submissions, and manage the overall flow of the application.
  - Ensured a smooth and intuitive navigation experience for users interacting with the product management system.

- Validation Mechanisms:
  - Employed both frontend (client-side) and backend (server-side) validation to enhance data accuracy.
  - Frontend validation provides immediate feedback to users, enhancing the user experience.
  - Backend validation in Flask guarantees that the submitted data meets the required criteria, maintaining data integrity.

- Continuous Integration and Deployment:
  - Utilized continuous Oracle Cloud deployment practices for a seamless and reliable deployment pipeline.
  - Automated testing and deployment processes ensure a consistent and efficient workflow for maintaining and updating the product management system.

Certainly! Here's an expanded version with more specific details about the **JavaFX iTunes Gallery App**:

### JavaFX iTunes Gallery App
- **Media Type Support:**
  - Designed to support diverse media types, ensuring flexibility for users to explore various content.
  - Incorporated a dynamic interface that adapts to different media categories seamlessly.
- **Exception Handling:**
  - Implemented robust exception handling mechanisms to gracefully manage errors during API requests or unexpected issues.
  - Provided informative error messages to guide users in case of network problems or other errors.
- **Image Shuffling Functionality:**
  - Included image shuffling functionality to enhance user engagement and provide a dynamic browsing experience.
  - Users can shuffle through images randomly, adding an element of surprise and entertainment.
- **iTunes Search API Integration:**
  - Leveraged the iTunes Search API for retrieving media content based on user queries.
  - Implemented networking capabilities to handle API requests, ensuring seamless communication between the app and the iTunes API.
- **Custom Gallery Component:**
  - Developed a custom gallery component to display retrieved media content in an organized and visually appealing manner.
  - Incorporated features such as image thumbnails, titles, and additional details to enrich the user browsing experience.
- **Dynamic Image Updates:**
  - Enabled real-time updates of the image gallery based on user interactions, providing instant feedback.
  - Utilized asynchronous tasks or threads to prevent the user interface from freezing during image updates.

### Connect Four Game

- Object-Oriented Programming (OOP) Principles:
  - Applied OOP principles, leveraging features such as polymorphism and inheritance to design and structure the Connect Four Game.
  - Utilized polymorphism to create a flexible and extensible codebase, allowing for the development of different game components with a common interface.
  - Implemented inheritance to establish relationships between classes, promoting code reuse and maintaining a clear and organized class hierarchy.

- Core Game Logic Implementation:
  - Implemented the core game logic, including the rules and mechanics of Connect Four, to accurately simulate the classic game.
  - Ensured that the game adhered to standard Connect Four rules, allowing players to drop discs into columns and win by connecting four discs of the same color vertically, horizontally, or diagonally.

### Bringing Colors to Life: A Fun and Interactive Arduino LED Project
- Developed a creative and interactive project centered around Arduino microcontrollers and LED technology.
- Prioritized accessibility by designing the project to accommodate individuals with visual impairments.
- Ensured that the project was inclusive and could be enjoyed by a diverse range of users, including those with varying levels of visual abilities.
 - Logic Gates and Truth Tables:
    - Incorporated logic gates into the project to perform digital signal processing and control the behavior of the LEDs.
    - Created truth tables to define the relationship between input signals and desired output states, facilitating the logical design of the project.
    - Implemented logical operations such as AND, OR, and NOT gates to achieve specific lighting patterns or color combinations.
 - Karnaugh Maps (K-maps):
    - Applied Karnaugh mapping techniques to simplify and optimize logical expressions.
    - Used K-maps as a visual aid to identify patterns and redundancies in the truth tables, streamlining the design process.
    - Optimized the logical design of the LED project to enhance efficiency and resource utilization.

  - Finite State Machines (FSMs):
    - Implemented Finite State Machines to model the behavior of the LED project as it transitions between different states.
    - Defined states, transitions, and actions to create a structured and modular design that can be easily extended or modified.
    - Utilized FSMs to add a dynamic and interactive element to the project, allowing for diverse and engaging LED sequences.
