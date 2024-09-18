## **Pesquisa Viral | Viral Search** 🌟

#### Explore, analyze, and optimize any business profile on Instagram.

Welcome to the future of Instagram business profile analysis. This platform allows users to filter, sort, and visualize performance and activity metrics for any business account on Instagram. With a clean and intuitive interface, users can easily uncover valuable insights into post engagement, activity trends, and follower growth.

---

#### **Live Demo**  
🚀 **Try it out now:** [Business Profile Analyzer](https://your-app-url.com)

---

### **Key Features**

- **Advanced Profile Analysis**: Sort and filter posts by engagement, date, or any relevant metric.
- **Interactive Performance Graphs**: Visualize profile activity and engagement with clean and easy-to-understand charts.
- **VIP Beta Access**: A select group of users from a partnered course on Kiwify are part of an exclusive testing phase.
- **Email Whitelisting**: Verify if you're part of the VIP testers through a seamless email verification system.
- **OAuth 2 Login**: Use Facebook to log in effortlessly (plus, I gain a little each time you do 😉).

---

### **Upcoming Features**

- **Freemium, Plus, and Enterprise Plans**: Get more out of your Instagram data with tailored subscription plans (coming soon).
- **Payment Integration**: Simple and secure payment processing for upgrades.

---

### **Tech Stack and Architecture**

This platform is built for scalability, security, and performance, with key decisions focused on providing the best user experience while maintaining robust backend performance.

#### **Technologies Used**

- **PHP (MVC Architecture)**: Utilizes the **Model-View-Controller (MVC)** pattern, where the business logic (Models), control logic (Controllers), and presentation layer (Views) are well-separated, ensuring maintainability and organization.
  - The application is currently monolithic, with the frontend and backend integrated, meaning the frontend is not decoupled via APIs, but all functionality is managed within the same codebase and server.
  - The architecture was designed for simplicity and efficiency in the early stages, with plans to evolve towards a more modular structure as the application scales.
  
- **JWT for Secure Authentication**: Token-based authentication to ensure secure session management and reduce unnecessary requests to Facebook.
- **Redis for Caching and Queuing**:
  - **Token storage**: OAuth tokens are stored with a three-day expiration to optimize API requests.
  - **Asynchronous Searches**: Redis queues allow for fast and scalable search operations.
  - **Recent Searches**: Users can access their last searches without any delay, cached for three days.
- **Non-Relational Database**: Chosen for horizontal scalability and flexibility in handling diverse data structures as the platform grows.
- **Webhook Integration**: Used to collect exclusive VIP user data from Kiwify, enabling seamless whitelisting of test users.
- **Facebook OAuth 2.0**: Easily allows users to log in with their Facebook credentials, streamlining the onboarding process while benefiting the platform.

---

### **Business Vision**

This project is designed as a future SaaS product (B2C), focused on delivering value to Instagram business users looking to optimize their profiles. The flexible freemium model ensures accessibility, while premium plans (Plus and Enterprise) will cater to users who need more advanced features and data insights.

With careful attention to security (OAuth 2.0, JWT, and Redis), performance (asynchronous tasks, caching), and scalability (non-relational databases), this platform is ready to grow alongside its users.

---

#### **Screenshots & Videos**

![Dashboard Preview](https://your-screenshot-link.com)
_A simple, clean dashboard offering insightful data at your fingertips._

![Performance Graph](https://your-performance-graph-link.com)
_Graphs that help visualize key metrics in real-time._

---

**Let's connect!**  
Feel free to [contact me](mailto:your-email@example.com) for any questions or collaboration opportunities.
