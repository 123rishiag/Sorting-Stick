# Sorting Stick

Welcome to **Sorting Stick**, a project created to visually demonstrate and compare various sorting algorithms. Built using C++ and SFML, this interactive tool makes sorting algorithms come alive, helping learners and developers better grasp the efficiency and functionality of different sorting techniques.

## Features

- **Algorithm Visualizer**: Watch sorting algorithms such as Bubble Sort, Insertion Sort, Selection Sort, Merge Sort, Quick Sort, and Radix Sort sort data step-by-step.
- **Sorting Comparison**: Compare the efficiency of each sorting algorithm in real-time.
- **Interactive SFML Graphics**: The visualizer uses smooth and responsive graphics, making it easy to follow each step of the sorting process.
- **Learning-Oriented Design**: Perfect for visual learners who want to understand the inner workings of sorting algorithms.

## Learning Outcomes

- **Sorting Algorithms**: Gained practical understanding of various sorting algorithms, from basic to advanced.
- **SFML Framework**: Gained hands-on experience using SFML to create engaging and interactive visualizations.
- **Object-Oriented Programming**: Designed the project with services, controllers, and models for clean, modular structure.
- **Algorithm Optimization**: Observed and learned the comparative efficiency of sorting algorithms in different scenarios.

## Project Structure

### Services and Their Model, Controllers

- **GraphicService**: Manages game window and rendering operations.
- **EventService**: Handles user input and game events.
- **TimeService**: Manages game timing and countdowns.
- **SoundService**: Manages sound effects and music playback.
- **UIService**: Manages UI components.
  - **UI Controllers**: `SplashScreenUIController`, `MainMenuUIController`, `GameplayUIController`
  - **UI Elements**: `UIView`, `TextView`, `ImageView`, `ButtonView`, `AnimatedImageView`, `RectangleShapeView`
  - **UI Interface**: `IUIController`
- **GameplayService**: Manages core gameplay mechanics.
  - **Controllers**: `GameplayController`, `StickCollectionController`
  - **Models**: `StickCollectionModel`
  - **Views**: `GameplayView`, `StickCollectionView`
  - **Stick**: Structure representing the stick data in the sorting algorithms.

### Additional Core Components
- **Main**: Entry point of the game.
- **GameService**: Core service that initializes and manages the game.
- **ServiceLocator**: Coordinates the initialization, updating, and rendering of all services, ensuring smooth communication between components.
- **Config**: Manages global configurations like file paths for assets, textures, sounds, and fonts.

## How to Use

- **Objective**: Select a sorting algorithm and observe its step-by-step process as it organizes a collection of items.
- **Controls**:
  - Choose a sorting algorithm from the main menu.
  - Watch as the algorithm sorts the data and observe the differences in sorting speeds and steps.

## How to Build and Run

1. Clone the repository:

   ```bash
   git clone https://github.com/123rishiag/Sorting-Stick.git
   ```

2. Build the project using your preferred C++ compiler.

3. Ensure that SFML is installed. Follow the installation instructions on the [SFML website](https://www.sfml-dev.org/).

4. Run the executable to start the sorting visualizer.

## Video Demo

Check out the [Video Demo](https://www.loom.com/share/9603286e2cdf4890bd22a08992c483eb?sid=87df604a-d52c-4710-a02c-f88cab199510) to see Sorting Stick in action!