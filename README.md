# GETTING STARTED WITH HACKTOBERFEST? 🎃
![enter image description here](https://github.blog/wp-content/uploads/2022/10/hacktoberfestbanner.jpeg)

Are you passionate about open source? Do you enjoy collaborating with developers from around the world? If so, you'll be excited to hear about Hacktoberfest - a month-long celebration of open source software. In this blog post, we'll explore what Hacktoberfest is all about, how it works, why you should participate, and how to make your first pull request. Let's dive in! 🚀

## What is Hacktoberfest? 🎉

Hacktoberfest is an annual event that takes place every October. It was created by DigitalOcean in collaboration with GitHub to promote open source contributions and encourage developers to get involved in the open source community. The primary goal of Hacktoberfest is to support and foster a vibrant open source ecosystem. 🌐

## How does it work? 🤔

Participating in Hacktoberfest is simple. All you need to do is sign up on the Hacktoberfest website and submit at least four pull requests to any public GitHub repository between October 1 and October 31. But remember, quality matters! Your pull requests should add value to the project and follow the project's guidelines. It's not just about quantity. it's about making meaningful contributions. ✨

## Why should you participate? 🌟

Hacktoberfest provides an excellent opportunity to enhance your coding skills, learn from experienced developers, and collaborate with a global community of open source enthusiasts. By participating, you can:

-   Build your portfolio and showcase your contributions to potential employers or clients.
-   Network with fellow developers and expand your professional connections.
-   Receive cool swag, t-shirts (or the option to plant a tree) 🎁
-   Contribute to meaningful projects and make a positive impact on the software ecosystem.
-   Improve your understanding of version control systems like Git and gain hands-on experience.

## How to participate? 🚩

To participate in Hacktoberfest, follow these steps:

1.  Sign up on the [Hacktoberfest website](https://hacktoberfest.digitalocean.com/).
2.  Find projects that interest you and align with your skills. We'll cover how to find projects in the next section.
3.  Familiarize yourself with the project's guidelines, code of conduct, and contribution process.
4.  Make your first pull request! We'll guide you through the process in the next section.

## Prerequisites 📚

Before diving into Hacktoberfest, it's essential to have a basic understanding of Git and GitHub. If you're new to version control systems, take some time to learn the fundamentals. We will see step by step how to get started with github keep reading. it's beneficial to have some knowledge of the programming languages and frameworks used in the projects you plan to contribute to. Non-coders can also participate by providing design ideas, making changes in docs or by helping others.

## How to find projects? 🔎

Finding projects to contribute to is an exciting part of Hacktoberfest. Here are a few ways to discover open source projects:

-   Explore the [Hacktoberfest website](https://hacktoberfest.digitalocean.com/) and browse the curated list of participating projects.
-   Visit GitHub's [Explore](https://github.com/explore) section and filter projects by language or topic.
-   Check out the [Awesome Hacktoberfest](https://github.com/MunGell/awesome-for-beginners#hacktoberfest) repository, which lists beginner-friendly projects.
-   Join developer communities, forums, or social media groups where people share project recommendations.

Remember to choose projects that align with your interests and skill level. It's essential to contribute meaningfully rather than simply chasing the Hacktoberfest rewards.

## Making your first pull request 🚀
#### Feel free to use this repository for your first pull request and consider it as a warm-up exercise to kickstart your open source journey! 🔥
-   Fork this Repository using the button at the top on right corner.
-   Clone your forked repository to your pc ( git clone "url from clone option.)
-   Create a new branch for your modifications (ie.  `git branch new-participant`  go to the new branch  `git checkout new-participant`  or simply do  `git checkout -b new-participant`)
- Add your profile data in  `main/participant/` 
- Create a markdown file in `main/participant/` this path like below.

	```
	main/participant/<YOUR-USERNAME>.md
	```
	Copy this template into your file, fill your information, paste this in the ` <YOUR-USERNAME>.md ` file
	```
	---
	name: YOURNAME
	institution/company: INSTITUTION_NAME/COMPANY_NAME
	github:USERNAME
	---
	```
-   Add your files (`git add -A`), commit (`git commit -m "added my info"`) and push (`git push origin new-participant`)
-   Create a pull request
- Wait for Pull Request to merge
-   Star this repository ⭐️
### Congratulations on Your First Contribution! 🎉 🎉
#### If you have found a suitable project from [this repository](https://github.com/MunGell/awesome-for-beginners#hacktoberfest) , let's proceed with the following steps to make your first pull request:

1.  **Read the Readme File**: Start by thoroughly reading the Readme file of the project from top to bottom. Understand what the project does, how it works, and how to set it up properly.
    
2.  **Explore Good First Issue Labels**: Navigate to the "Issues" tab of the project repository. Look for labels such as "good first issue" or "hacktoberfest". These issues are specifically curated for newcomers like you. Select an issue that interests you.
    
3.  **Review and Communicate**: Read the issue description carefully. If you have any questions or need clarification, don't hesitate to ask in the comments section. Request to be assigned to the issue and discuss how you plan to approach and solve it. Alternatively, you can propose your ideas and open a new issue for discussion.
    
4.  **Fork the Repository**: Click on the "Fork" button at the top right corner of the project repository to create your own copy of the repository on your GitHub account.
    
5.  **Clone the Repository**: Clone the forked repository to your local machine using the following command:
    
    
    `git clone https://github.com/your-username/repository.git` 
    
6.  **Create a New Branch**: Create a new branch for your changes. It is recommended to name your branch in a descriptive and meaningful way. For example:
    
    
    `git checkout -b my-feature` 
    
7.  **Make the Necessary Modifications**: Make the required modifications or additions to the codebase, addressing the issue you selected.
    
8.  **Commit and Push**: Commit your changes and push them to your forked repository using the following commands:
    
    
    `git add .
    git commit -m "Your descriptive commit message"
    git push origin my-feature` 
    
9.  **Open a Pull Request**: Go to the original project repository and open a pull request. Provide a clear and concise description of the changes you made and their purpose. Be sure to reference the issue number in your pull request description if applicable.
    
10.  **Review and Address Feedback**: Wait for the project maintainers to review your pull request. They may provide feedback or suggest improvements. Address any feedback received and make the necessary changes accordingly.
    
11.  **Merge and Celebrate!**: Once your pull request is approved, it will be merged into the project. Congratulations on your successful contribution! You can now celebrate your accomplishment and continue making more valuable contributions to the open source community.

## Avoiding spam pull requests ❌

As Hacktoberfest gained popularity, some participants began submitting low-quality or spam pull requests just to reach the required count. However, starting from 2020, Hacktoberfest has implemented certain measures to prevent spam contributions. Only pull requests that are labeled as "hacktoberfest-accepted" or "hacktoberfest-accepted" in the participating repository will be considered valid.

When contributing, focus on adding value, fixing bugs, improving documentation, or implementing useful features. Be respectful of maintainers' time and follow the project's guidelines. Quality contributions will be appreciated and make a real impact on the open source community.

So, are you ready to embark on your Hacktoberfest journey? Sign up, find exciting projects, make meaningful contributions, and celebrate the spirit of open source! Happy hacking! 💻🎉
