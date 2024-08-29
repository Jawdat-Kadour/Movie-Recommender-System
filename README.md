Welcome to the **Movie Recommender System** project! This project is a Python-based application that utilizes an expert system to recommend movies to users based on their preferences. The application provides an interactive GUI for users to input their movie preferences, such as genre, rating, language, release year range, and runtime. The system then analyzes the preferences and recommends movies with a high certainty factor.

## Description

### Project Overview

This project implements a movie recommendation system using a combination of rule-based expert systems and graphical user interfaces (GUIs). The application is developed using several key Python libraries, including:

- **Tkinter**: For creating a user-friendly GUI.
- **Experta**: A Python library for building rule-based expert systems.
- **PIL (Pillow)**: For handling and displaying movie poster images within the GUI.
- **PyQt5**: For an alternative GUI implementation with a modern look and feel.

### Key Features

1. **User Preference Input**:
   - Users can input their preferred genre, rating, language, release year range, and runtime.
   - The GUI collects these preferences and feeds them into the expert system.

2. **Rule-Based Expert System**:
   - The system uses `Experta` to implement a knowledge engine that processes user preferences and compares them against a database of movies.
   - Rules are defined to match user preferences with movie attributes, ensuring that only the most relevant recommendations are provided.

3. **Certainty Factor Calculation**:
   - The system calculates a certainty factor for each recommended movie based on how closely it matches the user's preferences.
   - The certainty factor is used to rank the recommendations, with the highest-ranking movies displayed to the user.

4. **Movie Recommendations Display**:
   - Recommended movies are displayed in a scrollable GUI window, complete with movie posters and additional information such as title and certainty factor.
   - Users can visually explore the recommended movies, enhancing the overall user experience.

5. **Multiple GUI Implementations**:
   - The project provides two GUI implementations: one using Tkinter for simplicity and another using PyQt5 for a more modern interface.

### Techniques and Concepts

- **Rule-Based Expert Systems**: The project leverages expert system techniques to build a robust recommendation engine. By defining rules that consider user preferences, the system can provide personalized recommendations with a calculated certainty factor.
  
- **GUI Development**: The project demonstrates proficiency in developing interactive and user-friendly GUIs using Tkinter and PyQt5. These interfaces allow users to input preferences and view recommendations in a visually appealing manner.

- **Image Processing**: With the help of the Pillow library, the system processes and displays movie posters, enhancing the visual appeal of the recommendations.

### Future Enhancements

- **Expand Movie Database**: The system currently uses a small database of movies. Future enhancements could include expanding this database to provide a wider range of recommendations.
- **Integration with Online APIs**: Integrating the system with online movie databases such as IMDb or TMDb could provide real-time recommendations and more dynamic content.
- **Improved Recommendation Algorithms**: Exploring other recommendation algorithms, such as collaborative filtering or content-based filtering, could complement the rule-based approach and offer more diverse recommendations.

---

Feel free to customize this further based on your specific implementation and goals!