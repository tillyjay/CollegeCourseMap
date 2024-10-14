# College Course Map 

## Ionic College Course Map App
This project is a college course map built with TypeScript and the Ionic framework. It provides an intuitive and interactive mobile and web interface for students and faculty to navigate through academic years, semesters, courses, diplomas, and instructors. The app is designed to help users easily explore the academic offerings at the college, with detailed information and connections between different academic entities.

## Features:
- Academic Year Overview: Users can browse through different academic years and view associated semesters.
- Course and Diploma Details: Students can explore available courses and diplomas, and view detailed information on specific -subjects.
- Instructor Profiles: The app includes profiles for instructors, making it easy to find information about faculty members.
- Real-Time Data Fetching: Data for academic years, semesters, courses, and instructors is fetched from an API, ensuring real-time accuracy.

## Technologies Used
- Ionic Framework
- TypeScript
- React
- Axios

## Lessons Learned
- TypeScript's static type checking helped catch potential errors early, ensuring data consistency across components and reducing runtime issues by defining clear interfaces and types.
- Managing component state with React's useState and side effects with useEffect, essential for fetching and displaying dynamic data from APIs.
- Handling asynchronous data properly (e.g., axios for API calls) especially when working with real-time data.
- Using Ionic’s built-in UI components like IonRefresher and IonList allowing for a more mobile-native user experience.
- Ionic’s IonRouterOutlet and routerLink making navigation between pages smooth, but understanding the hierarchy and how to pass parameters for dynamic content loading.
- Testing on both mobile and web platforms helped identify potential issues with responsiveness and performance across devices.

## Future Improvements
- Lazy Loading & Performance Optimization: Implement lazy loading for data and components to improve initial load times, especially for larger datasets like courses or academic years.
- Accessibility (WCAG) Improvements: Ensure the app meets WCAG standards by adding color contrast, adding proper ARIA attributes, and enhancing keyboard navigation and screen reader support.
- Implement user authentication (e.g., OAuth) and role-based access control for restricting access to certain features or pages based on user roles (e.g., students, faculty, admins).

## Icons
![image](https://github.com/user-attachments/assets/8603d551-fcac-4d85-9889-ad2b1ae2a215)

