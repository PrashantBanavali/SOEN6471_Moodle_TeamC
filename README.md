# SOEN 6471-Advance Software Architecture - Summer 2023 (Team C)


## TEAM MEMBERS
|Name|
|:---------:|
|Prashant Banavali|
|Shubham Jagdishbhai Bhanderi|
|Rutvij	Bhatt|
|Poornaa Himadri Bhattacharya|
|Khushboo Saraf|

## Moodle Software Architecture
1.	Introduction
1.1. Purpose
Moodle is a widely used open-source learning management system (LMS) that provides educators and institutions with a robust platform for creating and delivering online courses. [1] It was initially developed by Martin Dougiamas in 2002 with a strong focus on collaboration, interactivity, and accessibility in online education. 
The primary purpose of Moodle is to facilitate the creation and management of online learning environments. It enables educators to organize and deliver course materials, engage students through various interactive activities, facilitate communication and collaboration, and assess student performance. Moodle supports a wide range of educational formats, including traditional classroom-based courses, blended learning, and fully online courses.

1.2. Characteristics
One of the defining characteristics of Moodle is its open-source nature. Being open-source means that the software's source code is freely available to the public, allowing users to modify, customize, and extend the platform to suit their specific needs. This flexibility has contributed to the widespread adoption of Moodle by educational institutions, corporations, and individual educators worldwide. Moreover, the open-source community around Moodle actively contributes to its development, continually improving its functionality, reliability, and security.

1.3. Development and Improvision
In terms of software activities, the development of Moodle involves a collaborative effort by a global community of developers, educators, and users. The development process follows a transparent and iterative approach, where updates and improvements are regularly released. The community engages in activities such as bug tracking, feature requests, and peer-reviewed code contributions.
‘Moodle's feature set includes tools for content management, discussion forums, assignment submission, quizzes, grade tracking, and more. It supports multimedia content, allowing educators to incorporate videos, audio files, interactive simulations, and other engaging resources into their courses. Furthermore, Moodle promotes active learning through its interactive features, such as real-time chat, wikis, and collaborative workspaces’. [2]

1.4. Accessibility and Features:
The platform also places a strong emphasis on accessibility and inclusivity. It adheres to international accessibility standards, ensuring that learners with disabilities can access and engage with the learning materials effectively. Moodle supports multiple languages, making it suitable for diverse global audiences. [3]
In addition to its core functionality, Moodle supports a wide range of plugins and integrations, allowing users to extend its capabilities. ‘These plugins enable integration with external tools, such as video conferencing systems, learning analytics tools, plagiarism detection services, and more, enhancing the learning experience and providing educators with a comprehensive set of tools.’ [4]

1.5. Summary
In conclusion, Moodle is a powerful open-source learning management system designed to facilitate online education and foster collaboration. Its defining characteristics include its open-source nature, its active community of developers, and its commitment to accessibility and inclusivity. With its extensive feature set, flexibility, and support for customization, Moodle has become a popular choice for institutions and educators seeking a reliable and adaptable platform for online learning.

2.	Context of Use
There are several aspects that can be considered while modeling the context of Moodle. Some of these are:

2.1. Course Context
1. Design Course Structure: Facility to create courses, organize courses, promote content delivery including topics, modules, lessons, help in activity design to create quizzes, and upload assignments.
2. Course Content: Provide the ability to analyze the learning materials available, such as text, images, videos, and maintain communication throughout the course with various interactive elements.
3. Course Progress: Track individual student progress, including completed activities, grades, and overall performance.

2.2.	User Context
Roles and Permissions: Recognize different user roles within Moodle, such as students, instructors, administrators, each with their respective permissions and access levels. The different users with their respective roles on Moodle are:

1. Administrators:  Moodle provides administrative tools to manage the system.
- Administrators can create and manage user accounts, roles, and permissions.
- Administrators can configure system settings, set up authentication methods, and customize the appearance.
- Administrators can generate reports on course enrollment, user activity, and system usage.
- Administrators can perform regular backups, update the software, and manage plugins and extensions.

2. Instructors: Moodle provides a platform to create and manage courses, upload content, interact with students, and evaluate their progress.
-	Instructors can set up courses, organize them into categories, and define course objectives.
-	Instructors can upload resources such as files, documents, videos, and embed multimedia content.
-	Instructors can design various activities, including quizzes, assignments, forums, and surveys, to engage students.
-	Instructors can create grading scales, track student performance, and provide feedback and grades.
-	Instructors can facilitate communication by integrating discussion forums, messaging, and announcements.
-	Track individual student progress, including completed activities, grades, and overall performance.
-	Moodle allows instructors to customize learning paths and provide individualized learning experiences.
 
3. Students: Moodle allows the recipient of the learning process access course materials, participate in activities, submit assignments, and communicate with instructors and peers.

- Students can access course content, including lectures, readings, and multimedia resources.
- Students can participate in online discussions, group activities, and peer assessments.
- Students can view their grades, track their progress, and receive notifications for upcoming deadlines.
- Students can submit assignments electronically and receive feedback from instructors.

2.3. Social Context
1.	Collaboration Tools: Explore various collaborative elements, such as discussion forums, wikis, and group activities, that foster active engagement and facilitate the exchange of information and expertise among users.
2.	Peer Assessment: Gain insight into the peer review and grading mechanisms incorporated in Moodle, which enable peer-based learning and assessment.
3.	Communication Channels: Utilize messaging systems, chatrooms, and announcement features to cultivate effective communication channels between instructors and students.
4.	Data Tracking: Gather and examine user data, which encompasses log files, clickstreams, and engagement metrics, to extract valuable insights regarding user behavior, learning trends, and performance.
5.	Reporting and Analytics: Administrators can generate reports on course enrollment, user activity, and system usage.

2.4. Integration Context
1.	External Tools: Explore the integration of external applications, plugins, and services, such as video conferencing, content repositories, plagiarism detection, and learning analytics dashboards, to enhance the functionality and user experience of Moodle.
2.	Standards and APIs: Understand interoperability standards, like SCORM and LTI, to integrate external content and tools seamlessly.

By considering these diverse facets of context, educators and administrators can make well-informed choices, devise impactful instructional approaches, and deliver tailored support within the Moodle platform.
Furthermore, harnessing the power of learning analytics and integration capabilities can elevate the overall learning journey and foster student achievement.

3. Stakeholder Model - Using Mind Map

3.1. Mapping Out the Elements: A Mind Map for developing an effective Stakeholder Model of Moodle
A stakeholder model or stakeholder analysis in the context of Moodle refers to identifying and understanding the individuals, groups, or entities that have an interest or influence in the Moodle learning management system.
Mapping the stakeholders helps in recognizing their needs, expectations, and potential impact on Moodle's success. 
The stakeholder model is essential for Moodle because it helps in understanding and addressing the needs and expectations of different user groups. 
By identifying stakeholders, Moodle can ensure that its design, development, and implementation align with the requirements of these individuals or groups. 

3.2. Key Stakeholders of Moodle Ecosystem
1. Primary Stakeholders:
-	Students: The main users of Moodle rely on the platform for accessing course materials, submitting assignments, participating in discussions, and tracking their progress.
-	Teachers/Instructors: They use Moodle to create and manage course content, deliver online lectures, assess student performance, and facilitate learning activities.
-	Administrators: Responsible for the overall management, configuration, and maintenance of the Moodle system, including user accounts, permissions, plugins, and system updates.
-	Developers: Individuals or teams involved in the development and improvement of Moodle's core software, plugins, themes, and integrations.

2. Secondary Stakeholders:
- IT Department: Manages the technical infrastructure supporting Moodle, such as servers, databases, network, and security.
- Educational Organizations: Schools, colleges, universities, or any organizations that use Moodle as their learning management system.
- Parents/Guardians: Have an interest in monitoring their children's progress, accessing course materials, and staying informed about their educational activities through Moodle.
- Support Staff: Includes help desk personnel, technical support teams, and training staff who aid and train Moodle users.
- Content Providers: Publishers or content creators who develop and provide educational resources like textbooks, e-books, multimedia content, etc., which can be integrated into Moodle courses.
- Third-party Service Providers: Companies or individuals offering Moodle-related services like hosting, customization, integration, and consulting.

3. Tertiary Stakeholders:
-	Regulatory Bodies: Government agencies or educational authorities that may impose policies, guidelines, or standards related to e-learning platforms like Moodle.
-	Software Vendors: Suppliers of operating systems, web servers, databases, and other software components that are required to run Moodle.
-	Open-source Community: Individuals or organizations contributing to the open-source Moodle project by providing bug fixes, feature enhancements, documentation, translations, etc.
-	Research Communities: Academic researchers or institutions conducting studies and research related to e-learning, online education, and Moodle itself.

The stakeholder model helps Moodle by providing a comprehensive view of the different user groups and their specific needs. 
It enables Moodle developers and administrators to prioritize feature development, allocate resources effectively, and make informed decisions about the platform's direction. 
By considering the perspectives of stakeholders, Moodle can enhance user experience, increase adoption, and deliver a product that aligns with the expectations of its diverse user base.

### References
- [1]	[“Moodle Architecture” – docs.moodle.org](https://docs.moodle.org/dev/Moodle_architecture) (accessed: May 26, 2023).
- [2]	Lakshmi, V. Vijaya, K. Y. Devi, and M. Aparna. "Innovative methods of teaching and learning." Alochana Chakra Journal 9, no. 6 (2020): 3567-3575.
- [3]	[“Moodle LMS 4.0 achieves WCAG 2.1 AA Accessibility compliance” – moodle.com](https://moodle.com/news/moodle-lms-4-0-achieves-wcag-2-1-aa-accessibility-compliance/) (accessed: May 26, 2023).
- [4]	[“Plugin files” – docs.moodle.org](https://docs.moodle.org/dev/Plugin_files) (accessed: May 26, 2023).

## ROLES & RESPONSIBILITIES
# Deliverable 1 (D1)
Due Day/Date/Time: Saturday, May 27, 2023; 22:00.
|Name/Task| OPENARCH Selection|	Research | Problem 1 |	Problem 2 | Problem 3 | Documentation|
|:---------:|:---------:|:---------:|:---------:|:---------:|:---------:|:---------:|
|Prashant Banavali|:white_check_mark:|:white_check_mark:|||:white_check_mark:|:white_check_mark:|
|Shubham Jagdishbhai Bhanderi|:white_check_mark:|:white_check_mark:|||:white_check_mark:|:white_check_mark:|
|Rutvij	Bhatt|:white_check_mark:|:white_check_mark:|:white_check_mark:|||:white_check_mark:|
|Poornaa Himadri Bhattacharya|:white_check_mark:|:white_check_mark:||:white_check_mark:||:white_check_mark:|:white_check_mark:|
|Khushboo Saraf|:white_check_mark:|:white_check_mark:||:white_check_mark:||:white_check_mark:|


































