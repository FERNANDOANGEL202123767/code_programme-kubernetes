# Microservices-project---Course-Management-system

<p>ACADEMY IQ is an advanced online educational platform designed to provide a seamless learning experience for both instructors and learners. It leverages modern technologies to offer a robust and user-friendly interface for accessing and managing educational content.</p>
<h2>Key Features</h2>
<h3>Web/Mobile Interface</h3>
<ul>
  <li>User-friendly Interface: ACADEMY IQ offers a responsive and intuitive interface optimized for both web and mobile devices, ensuring a consistent experience across various screen sizes.</li>
<li>Responsive Design: The platform uses responsive web design principles to adapt to different devices and screen resolutions seamlessly.</li>
</ul>
<h3>Course Management</h3>
<ul>
  <li>Instructor Tools: Instructors have full control over course content. They can add, update, and delete course materials such as lecture notes, videos, and quizzes.</li>
<li>Admin Approval: Admins review and approve course content before it goes live, ensuring quality and consistency across courses.</li>
  <li>Notification System: A notification system sends SMS and email alerts to learners upon successful enrollment, ensuring they stay informed.</li>
</ul>
<h3>Multiple Course Enrollment:</h3>
<ul>
  <li>Flexible Enrollment: Learners can enroll in multiple courses simultaneously without scheduling conflicts, offering flexibility in learning paths.</li>
</ul>
<h2>Technology Stack</h2>
<h3>Backend</h3>
<ul>
  <li>Node.js: Server-side environment for scalable and efficient backend development.</li>
  <li>Express.js: Fast and minimalist web framework for Node.js.</li>
  <li>MongoDB: NoSQL database for storing course content, user data, and transaction records.</li>
  <li>JWT (JSON Web Tokens): Secure authentication mechanism for API endpoints.</li>
  <li>RESTful APIs: Follows REST architectural principles for seamless communication between frontend and backend services.</li>
</ul>

<h3>Microservices</h3>
<ul>
  <li>Docker: Containerization technology for packaging applications and dependencies into standardized units.</li>
  <li>Kubernetes: Orchestration tool for managing and scaling containerized applications across a cluster of nodes.</li>
</ul>
<h3>Frontend</h3>
<ul>
   <li>NEXT.js: React framework for building server-side rendered and statically generated applications.</li>
<li>TypeScript: Typed superset of JavaScript for improved code quality and developer productivity.</li>
<li>EJS: Embedded JavaScript templates for server-side rendering.</li>
<li>Socket.io: Real-time bidirectional event-based communication between clients and server.</li>
<li>RTK Query: Powerful data fetching and caching tool for efficient API communication.</li>
<li>Cloudinary: Cloud-based image and video management for storing and optimizing multimedia content.</li>
</ul>

<h3>Additional Technologies</h3>
<ul>
  <li>Redis: In-memory data structure store used for caching to improve application performance.</li>
  <li>Tailwind CSS: Utility-first CSS framework for designing custom and responsive user interfaces.</li>
</ul>

<h2>Deployment Instructions</h2>
Follow these steps to deploy the project locally:
<ol>
  <li>Download Docker Desktop: Download and install Docker Desktop from Docker's official website.</li>

<li>Clone the Repository: Clone this repository to your local machine using the following command:<br></li>

git clone https://github.com/ChamodiLiyanage/Microservices-project---Course-Management-system.git<br>
<li>Open with Visual Studio Code: Open the cloned repository using Visual Studio Code or any other code editor of your choice.<br></li>

<li>Navigate to Backend Directory: Using your terminal, navigate to the 'backend' directory inside the cloned repository:<br></li>

cd DS_Project_Y3S1/backend<br>
<li>Start Docker Containers: Run the following command to build the Docker images and start the containers:<br></li>

docker-compose up<br>
<li>Start Frontend Development Server: Open a new terminal window/tab and navigate to the root directory of the project. Then, run the following command to start the development server for the frontend:<br></li>

npm run dev<br>
<li>Access the Application: Once the development server starts successfully, open your web browser and visit the following URL:<br></li>

http://localhost:3000<br>
<li>You should now be able to access and use the application locally.</li>
</ol>


