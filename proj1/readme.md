# Simplii
We worked on our assigned projects and faced several challenges while installing and running the project. Eventually, we were successful in running one of the projects. So, herein we will discuss how we managed to overcome the challenges and run the project successfully. On the top of that we will also discuss how the previous team could have improved their code or documentation and make this installation process more efficient.


### *Issue 1*
- In our first attempt, we wanted to work with a project titled J-Tracker, we cloned the github repository and tried to install the prerequisites of the project. But we found that there are some dependencies which now no longer exist or there is no support for those dependencies. Due to these deprecated libraries, we were not able to run this project and later we decided to work on another project named Simplii. Furthermore, in Simplii also we got dependency errors while installing the CFFI library of python. However, this error was solved when we removed the version number from the requirements.txt file.

### *Solution*
- In order to resolve this issue, the contributors must review the project periodically and check if any update is required or not. Also, replace the libraries which are no longer available or deprecated.
Also, the version control tools like GitHub should be used to track the changes in dependencies and if anything is updated in the project it should be mentioned in the documentation and change the requirements.txt file with proper version immediately. 
Moreover, preference should be given to the libraries and frameworks which have a large and active community. This increases the likelihood of timely updates and assistance when issues arise.

### *Issue 2*
- In the Simplii project, we encountered the challenge with compatibility of the project with various operating systems. Running the project on different OS platforms introduced different sets of dependencies that needed to be carefully managed. We had to make adjustments to certain parts of the code to ensure compatibility with newer versions of dependencies.

### *Solution*
- Contributors should have identified any OS-related issues that might have arisen when running the project on different operating systems. Further, they should include clear and comprehensive steps for addressing these issues in the project documentation to assist future developers. Also, we have to change the code a bit because it was compatible with older versions of python libraries.

### *Issue 3*
- In the Simplii project, we encountered another hurdle where the URI string for the database connection was hard-coded at four different locations in the code. This practice not only makes maintenance cumbersome but also increases the risk of errors during configuration updates.

### *Solution*
- To avoid the complications caused by hardcoded configuration strings, we should:
The ideal approach is to declare sensitive information like database connection strings as environment variables. This allows for centralized configuration management and simplifies updates. Alternatively, store configuration parameters in a dedicated configuration file. This file can be versioned separately and loaded into the application when needed. Avoid hardcoding values directly into the codebase. Atlast, ensure that all configuration parameters, their purpose, and any necessary setup instructions are well-documented. This includes specifying where and how to set environment variables or update configuration files.

### *Issue 4* 
- Finally, we found that the project lacked clear and comprehensive documentation, making it challenging to install and build successfully. Documentation is essential for onboarding new team members and maintaining the project over time.

### *Solution*
- To enhance our project documentation and make it more accessible, we should create a detailed README file that includes step-by-step installation instructions, configuration guidance, and troubleshooting tips. Use a consistent and easy-to-follow format.The contributors should have considered creating video tutorials demonstrating the installation and setup process if possible. Visual guides can be extremely helpful, especially for complex projects.
Also keeping documentation up-to-date with each code change or new release is important. This ensures that developers always have accurate and relevant information.

In conclusion, our experience highlighted various challenges that users or future developers may encounter when working on the project. It is worth noting that many of these challenges could have been mitigated or avoided entirely through diligent documentation maintenance. Additionally, conducting thorough testing of the requirements.txt file across different operating systems could have played a crucial role in preventing these issues. For our further implementations we will take care of these problems and try to make the installation and running process smoother.


