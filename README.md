<section id="self-assessment">
  <h1>Professional Self-Assessment</h1>

  <p>My name is <strong>Fernanda Coghlan</strong>, and this ePortfolio represents the culmination of my academic journey in the Bachelor of Science in Computer Science program at Southern New Hampshire University. Throughout the program, I have grown from a learner with a strong background in engineering into a capable and versatile software developer. The ePortfolio presented here demonstrates my technical proficiency, problem-solving abilities, and professional readiness through carefully selected and enhanced software artifacts.</p>

  <p>This capstone project provided me with the opportunity to revisit and improve a mobile application originally developed during CS 360: Mobile Architecture and Programming. The <strong>FLC Weight Tracker App</strong> was chosen as my central artifact and enhanced across three major categories: <em>software design and engineering</em>, <em>algorithms and data structures</em>, and <em>databases</em>. This approach allowed me to focus on one real-world, functional application while applying a wide range of technical skills and architectural patterns to bring it to production quality.</p>

  <h2>Strengths Gained Through the Program</h2>
  <ul>
    <li><strong>Software Engineering & Design:</strong> Applied the Model-View-ViewModel (MVVM) architecture and repository patterns to improve modularity, scalability, and separation of concerns within the app.</li>
    <li><strong>Algorithms & Data Structures:</strong> Designed a weekly trend detection algorithm using <code>TreeMap</code> and <code>LocalDate</code> to provide insight into health patterns.</li>
    <li><strong>Databases:</strong> Integrated the Room persistence library and SharedPreferences to manage both structured and lightweight user data across sessions.</li>
    <li><strong>Security Mindset:</strong> Ensured safe storage of user settings and implemented best practices to protect sensitive data.</li>
  </ul>

  <h2>Collaboration, Communication, and Growth</h2>
  <p>Although this final project was completed independently, I consistently demonstrated collaboration and communication throughout the program in peer reviews, group discussions, and code walkthroughs. I developed fluency in explaining design decisions and documenting enhancements with clarity—skills reflected in the narratives and code review video within this ePortfolio. These are critical when collaborating in team environments or communicating technical solutions to non-technical stakeholders.</p>

  <h2>Career Aspirations</h2>
  <p>My immediate career goal is to transition into a remote software development role that allows me to build meaningful, user-centered applications. I am particularly interested in mobile development and backend data handling. Long-term, I intend to specialize further in full-stack engineering and eventually contribute to software architecture decisions at an organizational level. This ePortfolio helps position me for those opportunities by clearly presenting my applied skills and the tangible outcomes of my work.</p>

  <h2>Portfolio Overview</h2>
  <p>This ePortfolio contains:</p>
  <ul>
    <li>
      A <strong>code review video</strong> describing the original artifact and enhancement plans: 
      <a href="https://www.youtube.com/watch?v=qd9zIlDoPJo" target="_blank">CS 499 Capstone Code Review: FLC Weight Tracker Enhancement Overview</a>
      <p></p>
    </li>
    <li>Three enhanced versions of the <strong>FLC Weight Tracker App</strong>, demonstrating growth across:
      <p></p>
      <ul>
        <li><strong>Software Design and Engineering:</strong> <a href="https://drive.google.com/file/d/1zaSNtRdl-s43xBWz4__1I7r5ToI5jUja/view?usp=sharing" target="_blank">Download</a></li>
        <li><strong>Algorithms and Data Structures:</strong> <a href="https://drive.google.com/file/d/1hH4I4JiBqclSYB4Zc9Hd5lh8V8_KH9mv/view?usp=sharing" target="_blank">Download</a></li>
        <li><strong>Databases:</strong> <a href="https://drive.google.com/file/d/1LTYa49SaSjqb7jfMdzDdADcY5GrTYcgn/view?usp=sharing" target="_blank">Download</a></li>
        <li><strong>Final Version (fully enhanced):</strong> <a href="https://drive.google.com/file/d/13EhIfWzuy95sW_yZjMIotzky3qffnDPA/view?usp=sharing" target="_blank">Download</a></li>
        <p></p>
      </ul>
    </li>
    <li>Detailed <strong>narratives</strong> for each enhancement:</li>
  </ul>

  <div style="margin-top: 20px; line-height: 1.6;">

  <p><strong>Software Design and Engineering:</strong> 
    This enhancement focused on restructuring the original <em>FLC Weight Tracker App</em> using modern architectural patterns to ensure modularity, maintainability, and testability. I adopted the Model-View-ViewModel (MVVM) design pattern and introduced a repository layer to separate concerns between UI logic and data access. This refactor improved scalability and facilitated better lifecycle management using Android Architecture Components. I also implemented <code>LiveData</code> and <code>ViewModel</code> to ensure reactive and lifecycle-aware data binding across screens. As a result, the application now handles configuration changes gracefully and maintains a clean separation of logic. Through this enhancement, I demonstrated skills in architecture design, refactoring legacy code, and integrating Android Jetpack components. It aligns with Course Outcome #4 by using innovative software engineering techniques to implement value-driven solutions tailored to mobile environments.
  </p>

  <p><strong>Algorithms and Data Structures:</strong> 
    In this enhancement, I implemented a custom weekly trend detection algorithm to calculate average weight trends over time. Using <code>TreeMap</code> and <code>java.time.LocalDate</code>, I designed a strategy to sort weight entries by date and group them into ISO calendar weeks. I then calculated the average weight per week and exposed the result to the UI using <code>LiveData</code>. This enhancement transformed the user experience by providing meaningful feedback about progress toward health goals. It also required applying foundational knowledge of data structures (maps, lists), sorting algorithms, and temporal logic. This work reflects my ability to design and implement algorithmic solutions, satisfying Course Outcome #3 related to solving computing problems using algorithmic principles while considering trade-offs in performance and complexity.
  </p>

  <p><strong>Databases:</strong> 
    To address the lack of persistence in the original application, I integrated the Room persistence library to manage structured data storage for weight entries. I created an <code>Entity</code> class, <code>DAO</code> interface, and a <code>RoomDatabase</code> instance, establishing a complete local SQLite-backed solution. I also used <code>LiveData</code> to ensure that changes to the database were automatically reflected in the UI. Additionally, I incorporated <code>SharedPreferences</code> to store lightweight user-specific data such as name, email, password, weight goals, and notification preferences. This dual-layered data persistence ensures that both complex and simple data types are retained across sessions. With these enhancements, the app is now robust, user-friendly, and aligned with best practices in mobile database architecture. This work directly supports Course Outcome #4 and also touches on Outcome #5 by ensuring user data is handled securely and appropriately scoped between Room and preferences.
  </p>

</div>


  <ul>
    <li><strong>Screenshots and walkthroughs</strong> showing before-and-after views of the code and UI.</li>
  </ul>

  <p>Each enhancement aligns with specific <em>course outcomes</em> and showcases the depth of my technical knowledge, critical thinking, and ability to deliver reliable, user-friendly software. Together, these artifacts tell the story of my development as a computer science professional ready to enter the field with confidence and creativity.</p>
</section>
