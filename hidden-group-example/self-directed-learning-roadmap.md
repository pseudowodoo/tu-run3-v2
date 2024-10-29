# 🚶 Self-Directed Learning Roadmap

Start here if you want to learn parts of TechUp in your own time, at your own pace.

For those of us who may not have the time to undergo the full month-long TechUp, here are some curated, readily-available resources that the TechUp team recommends that you can get started with immediately.

The objectives of this learning roadmap are to:

***

{% hint style="success" %}
**Understand how the Internet works**

* **Internet Infrastructure**: Learn about the physical and virtual components that make up the internet, including servers, data centers, and undersea cables.
* **IP Addresses and DNS**: Understand how devices are identified on the internet and how domain names are translated into IP addresses through the Domain Name System (DNS).
* **Data Transmission**: Study how data is broken into packets, how these packets travel through different routes to reach their destination, and how protocols like TCP/IP ensure reliable communication.
* **Web Protocols**: Explore protocols such as HTTP/HTTPS, which enable the transfer of web pages from servers to browsers.
* **Network Security**: Learn about encryption, secure sockets layer (SSL), transport layer security (TLS), and other methods used to protect data during transmission.
* **Cybersecurity**: Understand common internet threats like malware, phishing, and DDoS attacks, and learn basic strategies to mitigate these risks.
{% endhint %}

{% hint style="success" %}
**Understand product thinking**. Key concepts:

* **User-Centered Design**: Emphasize the importance of understanding user needs, preferences, and behaviors in product development
* **Product Vision and Strategy**: Understand how to create a compelling product vision and align it with business goals and strategies.
* **Feature Prioritization**: How to decide which features to develop first.
* **Prototyping and Testing**: Understand how to create prototypes and conduct user testing to gather feedback and iterate on product design.
* **Metrics and Analytics**: Understand key performance indicators (KPIs) and metrics to measure product success and inform decision-making.
* **Agile and Lean Methodologies**: Learn about agile development practices and lean startup principles to create flexible, efficient product development processes.
{% endhint %}

{% hint style="success" %}
**Understand web development basics.** Key concepts:



* **HTML and CSS**: Learn the fundamental building blocks of web pages, including how to structure content with HTML and style it with CSS.
* **JavaScript**: Gain basic proficiency in JavaScript to add interactivity to web pages, manipulate the DOM, and handle events.
* **Responsive Design**: Understand how to create web pages that look and function well on a variety of devices and screen sizes.
* **Front-End Frameworks**: Get an introduction to popular front-end frameworks like React and Vue.js that facilitate building dynamic user interfaces.
* **Back-End Development**: Learn the basics of server-side programming with languages like Node.js, Python, or Ruby, and understand how to create APIs.
* **Databases**: Understand how to interact with databases using SQL or NoSQL to store and retrieve data.
* **Version Control**: Learn the basics of version control systems like Git to manage code changes and collaborate with other developers.
* **Deployment**: Get an introduction to deploying web applications to the cloud using services like AWS, Heroku, or Netlify.
{% endhint %}

***

### Week 1 (2 hours): How does the Internet Work?

#### a. How Computers Work

This playlist is an educational series of short videos that explain the fundamental concepts of computer science in an accessible and engaging way for beginners. Key topics include:

* [**What Makes a Computer, a Computer?**](https://www.youtube.com/watch?v=mCq8-xTH7jA\&list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-\&index=2): Explains the basic components and functions of a computer.
* [**Binary & Data**](https://www.youtube.com/watch?v=USCBCmwMCDA\&list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-\&index=3): Introduces binary code and how computers use it to process data.
* [**Circuits & Logic**](https://www.youtube.com/watch?v=ZoqMiFKspAA\&list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-\&index=4): Discusses how electrical circuits and logic gates form the foundation of computer operations.
* [**CPU, Memory, Input & Output**](https://www.youtube.com/watch?v=DKGZlaPlVLY\&list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-\&index=5): Describes the role of the central processing unit, memory, and how computers interact with the outside world through input and output devices.
* [**Hardware and Software**](https://www.youtube.com/watch?v=xnyFYiK2rSY\&list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-\&index=6): Covers how software is used to control hardware and perform tasks.

{% embed url="https://youtu.be/OAx_6-wdslM" %}

#### b. How the Internet Works

This playlist is a series of educational videos that explain the fundamental concepts and mechanics behind the internet. Key topics include:

* [**What is the Internet?**](https://www.youtube.com/watch?v=Dxcc6ycZ73M\&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7): An introduction to the internet, its structure, and how it connects millions of devices worldwide.
* [**IP Addresses and DNS**](https://www.youtube.com/watch?v=5o8CwafCxnU\&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7\&index=3): Explains how IP addresses and the Domain Name System (DNS) help devices find and communicate with each other.
* [**Packets, Routing, and Reliability**](https://www.youtube.com/watch?v=AYdF7b3nMto\&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7\&index=4): Discusses how data is broken into packets, how they are routed across the network, and methods to ensure reliable data transfer.
* [**HTTP and HTML**](https://www.youtube.com/watch?v=kBXQZMmiA4s\&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7\&index=5): Covers how the Hypertext Transfer Protocol (HTTP) and Hypertext Markup Language (HTML) are used to deliver and display web pages.
* [**Encryption and Public Keys**](https://www.youtube.com/watch?v=ZghMPWGXexs\&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7\&index=6): Introduces encryption methods and public key infrastructure to secure data transmission.
* [**Cybersecurity and Crime**](https://www.youtube.com/watch?v=AuYNXgO\_f3Y\&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7\&index=7): Examines potential threats on the internet and strategies to protect against them.

{% embed url="https://youtu.be/Dxcc6ycZ73M" %}

#### c. What happens when you type a URL in the browser and press 'Enter'?

This Medium article (login required) explains the technical processes that occur when you type a URL into a browser and press enter:

1. **DNS Lookup**: The browser checks the URL to find the corresponding IP address using DNS.
2. **TCP Connection**: The browser establishes a TCP connection with the server.
3. **HTTP Request**: The browser sends an HTTP request to the server.
4. **Server Response**: The server processes the request and sends back an HTTP response.
5. **Rendering**: The browser renders the HTML content, along with CSS and JavaScript, to display the web page.

{% embed url="https://medium.com/@maneesa/what-happens-when-you-type-an-url-in-the-browser-and-press-enter-bb0aa2449c1a" %}

#### d. How the Internet Works (a round-up lecture)

Justyn Oh, Software Engineer at Open Government Products, shares a crash-course framework on How the Internet Works, and some takeaways for policy-makers.



{% embed url="https://docs.google.com/presentation/d/12su5WrpCPGDdJFkRA7WuCRqmAMv29bTyg_pXOxgYJqg/edit?usp=drive_link" %}

### Week 2 (4 hours): Selected presentations from TechUp 2.0 and reading materials on Product Thinking

#### a. ProductUp slides

ProductUp is a half-day workshop conducted by Open Government Product's Product Managers on the overall product development process, from problem statements, to identifying target audience, to user journeys, all the way to iterating and funding successful projects. While this workshop is most effective in a hands-on setting, the slides and exercises will give you an overview of the thinking behind the product process.



{% embed url="https://docs.google.com/presentation/d/1WTSqkZnYaTpWxRUzYmycmdu3Mccj8Jel7CezN_0TH84/edit?usp=sharing" %}

#### b. Product Management in Software Development: How it Works

To expand on ProductUp, this video explains what product management means, including product market fit, product vision, strategy, understanding customers, product execution and product KPIs.

{% embed url="https://youtu.be/7j4WGVAsf4Y" %}

#### c. Products 101: What is 'good' product?

Conducted by Director/Products Directorate Chen Kaiwei, this session explains the outline of how to&#x20;

{% embed url="https://drive.google.com/file/d/1cs6Cf5U_ga13tXkUxowMDmNk13FCshL9/view?usp=sharing" %}

#### d. DesignUp

The following presentations by Design Manager Mike Chen & Lead UX Researcher Darren Ng cover:

* What is good design?
* How do you design your prototype?
* How do you test your prototype?



{% embed url="https://docs.google.com/presentation/d/1Rms4sa5s8U0A3jj3hEBfXGI4qsHONtyvCotlN0yqCuc/edit?usp=sharing" %}

{% embed url="https://docs.google.com/presentation/d/1t6GhtbrqaatBF4sEKQwV7tKkTy_vjYQyTrHnjLmkRPw/edit?usp=sharing" %}

{% embed url="https://docs.google.com/presentation/d/1Nf1GJyPBtfK5v4qNKsW4IKRivtSfpK93iEvNfx6g93g/edit?usp=sharing" %}

{% embed url="https://docs.google.com/presentation/d/1Mil5jOGyriJxUnBaBy5L98ppeU5QOfURC6xb-11pVxg/edit?usp=sharing" %}

{% embed url="https://docs.google.com/presentation/d/1vPPGaXvodMeRyI5Wr9tUBQ2k3SKWN1NAGFq_6r2R7MI/edit?usp=sharing" %}

{% embed url="https://docs.google.com/presentation/d/1wnSMhu8wmZlY-3IVojEOSZ8AEOb7cjGUsbDd2xst1QI/edit?usp=sharing" %}

#### e. Agile product ownership in a nutshell

This video provides an overview of the roles and responsibilities of a Product Owner within an Agile development framework. It highlights key concepts such as **prioritizing the product backlog, defining user stories, ensuring clear communication with the development team, and maintaining a focus on delivering value to the customer**. The video emphasizes the importance of collaboration, iterative progress, and adaptability in the product development process.

{% embed url="https://youtu.be/502ILHjX9EE" %}

#### f. Product Metrics: How to Measure Product Success

This video explains which North Star metrics report on the product’s successes and failures. Key topics covered are: What is success for you, What are metrics (KPIs)?, user acquisition metrics, user engagement metrics, and financial metrics.

{% embed url="https://youtu.be/wtDFgx41Rho" %}

***

### Weeks 3-6 (20+ hours): Web Development

#### a. Selected modules of the Complete 2024 Web Development Bootcamp on Udemy

The Complete 2024 Web Development Bootcamp on Udemy is a comprehensive course designed to teach students everything they need to become professional web developers. It covers **front-end and back-end development**, including **HTML, CSS, JavaScript, Node.js, React, PostgreSQL**, and more, including practical exercises to build real-world applications. The course is suitable for beginners, with step-by-step instructions and explanations.

We have selected a few of the more important modules (marked with "❗") that we recommend learners to focus on:

{% content-ref url="../pre-work/mandatory-course-udemy.md" %}
[mandatory-course-udemy.md](../pre-work/mandatory-course-udemy.md)
{% endcontent-ref %}

#### b. Primers to understand Web Development

The TechUp team has also prepared primers to break down key concepts related to **front-end development, Git/GitHub, HTML, CSS, JavaScript, back-end development Databases and APIs.** These are short lectures with some hands-on exercises.

{% content-ref url="../programme-materials.md" %}
[programme-materials.md](../programme-materials.md)
{% endcontent-ref %}

### Weeks 7-10 and beyond (40+ hours): CS50 for Lawyers (highly recommended as a bonus)

CS50 for Lawyers is a highly-rated and well-acclaimed version of Harvard's renowned introductory computer science course tailored specifically for non-technical professionals. It provides a broad overview of computer science and programming, aimed at helping lawyers understand the technology landscape. Key topics include **algorithms, data structures, cryptography, cybersecurity, and the basics of programming languages like Python and SQL**. The course focuses on practical applications in the legal field, enabling lawyers to better navigate tech-related cases, communicate with technical experts, and understand the implications of technology on law.

{% embed url="https://pll.harvard.edu/course/cs50-lawyers" %}

CS50 for Lawyers is designed to be completed in **about 10 weeks**, with an estimated time commitment of **6 to 9 hours per week**. It is particularly beneficial for policy officers who interact with technology but are not directly responsible for tech policy, strategy, or planning.
