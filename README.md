Jetpack Compose Assignment 1
Overview
This Android application demonstrates the use of Jetpack Compose to display a list of academic courses. Each course is presented in a card that shows basic information (title, code, credit hours) and can be expanded to reveal additional details (description, prerequisites). The app follows Material 3 Design principles and incorporates state management, animations, and efficient list rendering.

Features
Composable UI: Built entirely with Jetpack Compose, using @Composable functions.
State Management: Uses rememberSaveable for preserving the expanded state of each course card across configuration changes.
Efficient List: Implements LazyColumn for performant rendering of potentially long course lists.
Animations: Applies animateContentSize for smooth expand/collapse transitions.
Material 3 Design: Utilizes MaterialTheme for consistent styling, with support for light and dark themes.
Preview Support: Includes @Preview annotations to visualize UI in both light and dark modes.
