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
- **Integrated External APIs**:
  - Integrated with the **TransportAPI** to retrieve bus route details in Leeds.
    - Parameters included `app_id` and `app_key` for authentication.
  - Utilized the **UK Police API** to fetch crime data in the vicinity of selected bus stops.
    - Parameters: Latitude (`lat`), Longitude (`lng`), and Date (`date`).
- **Some JavaFX Components**:
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
- **Data Entry Tool with Flask:**
  - Created a user-friendly interface using Flask for seamless product data entry.
  - Implemented a data entry tool that leverages Flask, preventing users from proceeding without entering essential product details.
- **Flask Routes and Views:**
  - Developed robust routes and views in Flask to render HTML templates, process form submissions, and manage the overall flow of the application.
  - Ensured a smooth and intuitive navigation experience for users interacting with the product management system.
- **Validation Mechanisms:**
  - Employed comprehensive validation mechanisms, encompassing both frontend (client-side) and backend (server-side) validation to enhance data accuracy.
    - Frontend validation provides immediate feedback to users, enhancing the user experience.
    - Backend validation in Flask guarantees that the submitted data meets the required criteria, maintaining data integrity.
- **Continuous Integration and Deployment:**
  - Implemented continuous Oracle Cloud deployment practices to establish a seamless and reliable deployment pipeline.
  - Automated testing and deployment processes ensure a consistent and efficient workflow, facilitating the maintenance and updates of the product management system.

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

### StringList Implementation Harmony: BaseStringList, ArrayStringList, and LinkedStringList
**Architecture and Functionality:**
- *StringList Interface Design Excellence:*
  - Architected a StringList interface with a well-defined structure, optimizing for efficiency in string manipulation across all implementations.
  - Implemented versatile methods that cater to intricate string operations, promoting a user-friendly and powerful interface.
**Comprehensive Testing:**
  - Executed comprehensive testing suites for each StringList implementation, scrutinizing functionality under various scenarios and edge cases.
  - Validated the robustness and correctness of the implementations, instilling confidence in their reliability and consistent performance.
**Code Highlights:**
- *BaseStringList:*
  - Leveraged a foundational approach, emphasizing simplicity and efficiency in string handling.
- *ArrayStringList:*
  - Employed dynamic arrays for optimized memory utilization and efficient string manipulation.
  - Implemented algorithms to handle resizing and dynamic array management seamlessly.
- *LinkedStringList:*
  - Utilized linked structures to enhance flexibility and accommodate variable-length string operations efficiently.
  - Executed algorithms to navigate and manipulate strings within the linked structure effectively.

### Connect Four Game
- **Object-Oriented Programming (OOP) Principles:**
  - Implemented OOP principles, including polymorphism and inheritance, to create a modular and extensible Connect Four Game.
  - Leveraged polymorphism for a flexible codebase, enabling the development of diverse game components with a unified interface.
  - Utilized inheritance to establish clear relationships between classes, fostering code reuse and maintaining an organized class hierarchy.
- **Core Game Logic Enhancement:**
  - Enhanced the core game logic, ensuring a faithful representation of Connect Four rules and mechanics.
  - Enforced adherence to standard Connect Four rules, allowing players to strategically drop discs into columns and achieve victory by connecting four discs of the same color vertically, horizontally, or diagonally.

### Bringing Colors to Life: A Fun and Interactive Arduino LED Project
- **Creative Arduino Microcontroller Project:**
  - Developed an engaging and creative project centered around Arduino microcontrollers and LED technology.
  - Crafted an interactive experience that captivates users and brings the world of LEDs to life.
- **Accessibility Prioritization:**
  - Prioritized accessibility by designing the project with features tailored to individuals with visual impairments.
  - Ensured inclusivity, allowing a diverse user base to enjoy the project, accommodating varying levels of visual abilities.
- **Logic Gates and Truth Tables Integration:**
  - Integrated logic gates into the project for digital signal processing, providing precise control over LED behavior.
  - Developed truth tables to establish the relationship between input signals and desired output states, facilitating a logically sound project design.
  - Implemented AND, OR, and NOT gates to achieve specific lighting patterns and dynamic color combinations.
- **Karnaugh Maps (K-maps) Optimization:**
  - Applied Karnaugh mapping techniques to simplify and optimize logical expressions within the project.
  - Utilized K-maps as a visual aid to identify patterns and eliminate redundancies in truth tables, streamlining the overall design process.
  - Optimized the logical design of the LED project for enhanced efficiency and resource utilization.
- **Finite State Machines (FSMs) for Dynamic Sequences:**
  - Implemented Finite State Machines to model the behavior of the LED project as it smoothly transitions between different states.
  - Defined states, transitions, and actions to create a structured and modular design, facilitating easy extension and modification.
  - Leveraged FSMs to introduce a dynamic and interactive element, enabling diverse and engaging LED sequences.
