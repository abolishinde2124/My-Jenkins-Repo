# Shared Libraries

In Jenkins, a shared library is a way to store commonly used code(reusable code), such as scripts or functions, that can be used by different 
Jenkins pipelines. 

Instead of writing the same code again and again in multiple pipelines, you can create a shared library and use it in all the pipelines
that need it. This can make your code more organized and easier to maintain. 

Think of it like a library of books, Instead of buying the same book over and over again, you can borrow it from the library whenever you need it.

## Advantages

- Standarization of Pipelines
- Reduce duplication of code
- Easy onboarding of new applications, projects or teams
- One place to fix issues with the shared or common code
- Code Maintainence 
- Reduce the risk of errors

![235724851-90a5cad6-ac0d-428b-9944-93fffea55180](https://github.com/user-attachments/assets/a9be0116-2514-43c6-b558-325bc40a07f9)

## Configure Jenkins to Use the Shared Library
Navigate to Jenkins Configuration:

1.Go to "Manage Jenkins" → "Configure System".
2.Add the Shared Library:

3.Scroll down to the "Global Pipeline Libraries" section.<br>
4.Click "Add" and provide the following details:<br>
5.Name: A unique name for the library (e.g., my-shared-library).<br>
6.Source Code Management: Choose the SCM (e.g., Git) and provide the repository URL.<br>
7.Credentials: (if needed) Add credentials for accessing the repository.<br>
8.Library Retrieval: Specify the branch or tag.<br>
9.Save the Configuration.
