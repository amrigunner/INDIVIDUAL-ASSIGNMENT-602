# INDIVIDUAL-ASSIGNMENT-602

NAME: MOHAMMAD ZUL AMRI BIN ZAMRI

STUDENT ID: 2024274416

GROUP: CDCS2703A

LECTURER’S NAME: MUHAMMAD ATIF BIN RAMLAN



Project Background

The purpose of this project is to develop a real-time chat application using Angular 20 as the frontend framework and Supabase as the backend service. The application is designed to allow users to authenticate using Google OAuth, join chat rooms, and exchange messages in real time. Supabase provides essential backend features such as authentication, database management, and real-time capabilities through its Realtime API, while Angular 20 offers a modern and efficient way to build responsive and dynamic user interfaces.
This project demonstrates key concepts in modern web development, including secure authentication flows, route protection using Angular guards, and real-time data synchronization. It also emphasizes best practices for managing environment variables, implementing Row Level Security (RLS) policies for data protection, and ensuring scalability. By completing this project, the goal is to gain hands-on experience with integrating a frontend framework and a backend-as-a-service platform to build a functional, secure, and user-friendly application.






DISCUSSION

Working on the real-time chat application using Angular 20 and Supabase was an exciting and challenging experience that taught me a lot about modern web development. The main goal was to create a functional chat app that supports Google login, secure routing, and real-time messaging. At first, I thought it would be straightforward, but as I progressed, I realized how much planning and attention to detail was required to make everything work smoothly.
The first step was setting up Angular 20. This version introduced new improvements that make development easier and faster. I focused on using Angular’s routing system to manage navigation and implemented route guards with CanActivate to ensure only authenticated users could access chat rooms. This was a simple but important feature because it added a layer of security to the app and prevented unauthorized access.
Configuring Supabase was another big part of the project. I created tables for users and messages, enabled Google OAuth authentication, and applied Row Level Security (RLS) policies to protect data access. Setting up OAuth was tricky because the redirect URIs had to match exactly between Supabase and Angular. I spent time troubleshooting this issue, and it taught me how important it is to pay attention to small details. Managing environment variables securely was another challenge. I had to make sure sensitive keys were not exposed in the code or committed to GitHub.
The real-time feature was the most interesting part of the project. Supabase’s Realtime API allowed me to implement live messaging and presence indicators. I learned how to use channels to broadcast messages and synchronize updates across users. Handling reconnection logic and cleaning up subscriptions when components were destroyed was essential to avoid memory leaks. These steps made me appreciate how much effort goes into creating a smooth and reliable user experience.
Security was always a priority. Misconfigured RLS policies could block legitimate access or expose sensitive data, so I tested everything carefully. I also learned that security is not just about backend rules, but it also includes managing tokens, protecting routes, and avoiding hardcoded secrets in the frontend. These lessons reinforced why security should never be an afterthought in any application.
Beyond the technical side, this project taught me the importance of documentation and version control. Writing a clear README and making meaningful commits wasn’t just for marks, it made the project easier to manage and share. It also helped me stay organized and track my progress.
Looking ahead, I would like to add more features such as file uploads using Supabase Storage, typing indicators, message reactions, and pagination for chat history. Deploying the app on platforms like Vercel or Netlify would make it accessible to others, and adding unit and end-to-end tests would improve reliability and scalability.
Overall, this lab activity was a great learning experience. It strengthened my ability to combine cutting-edge tools, solve real problems, and think like a developer who cares about functionality, security, and user experience. I now feel more confident in building modern web applications and look forward to applying these skills in future projects.
