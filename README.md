# C# Learning Path
One of our students in the Zero to Mastery commmunity is studying C# at their university and asked for some resources. There is little else I like talking about than software development in C#, so I was more than happy to put this curated path together. I suggest taking it in the order, which involves taking one course on Udemy called [ASP.NET Core 6.0 Course - MVC - Blazor - Razor - EF Core](https://www.udemy.com/course/aspnet-6-course/) and then solidifying your knowledge with the learning paths from Microsoft.

This material up to the Next Steps section will give you a solid foundation in C# that is used in modern code bases. Completing the material starting with Next Steps requires purchasing additional courses but is included for those who want to go further towards becoming a full-stack engineer.

If you would like to create a copy of this repository for yourself so you can follow along, you can do so by forking this repository. [See How to Fork a Repo in GitHub for instructions](https://www.freecodecamp.org/news/how-to-fork-a-github-repository/).

## Learn .NET Basics
- [ ] [Course - SECTION 1 ONLY - ASP.NET Core 6.0 Course - MVC - Blazor - Razor - EF Core](https://www.udemy.com/course/aspnet-6-course/)
- [ ] [Microsoft Learn Path - Introduction and Overview](https://learn.microsoft.com/en-us/dotnet/core/introduction)

## Learn HTML, CSS, and Bootstrap
- [ ] [Course - SECTION 2 ONLY - ASP.NET Core 6.0 Course - MVC - Blazor - Razor - EF Core](https://www.udemy.com/course/aspnet-6-course/)
- [ ] OPTIONAL: [Course - COMPLETE BEGINNING THROUGH BOOSTRAP SECTION - The Complete Web Developer](https://www.udemy.com/course/the-complete-web-developer-zero-to-mastery/)

## Learn the MVC Pattern with Razor Pages
- [ ] [Course - SECTION 3 ONLY - ASP.NET Core 6.0 Course - MVC - Blazor - Razor - EF Core](https://www.udemy.com/course/aspnet-6-course/)
- [ ] [Learning Path - Microsoft - MVC](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-6.0&tabs=visual-studio)
- [ ] [Learning Path - Microsoft - Razor](https://learn.microsoft.com/en-us/aspnet/core/tutorials/razor-pages/?view=aspnetcore-6.0)
- [ ] [Razor Syntax Reference](https://learn.microsoft.com/en-us/aspnet/core/mvc/views/razor?view=aspnetcore-6.0)

## Learn about Entity Framework Core
There are two approaches to working with databases in EF Core:
1. Code first approach
2. Database first approach

*For developers, I highly recommend learning the code-first approach, as this is what most development teams use. The resources below cover a code-first approach.*

- [ ] [Course - SECTION 6 ONLY - ASP.NET Core 6.0 Course - MVC - Blazor - Razor - EF Core](https://www.udemy.com/course/aspnet-6-course/)
- [ ] [Learning Path - Microsoft - EF Core](https://learn.microsoft.com/en-us/training/modules/persist-data-ef-core/)

## Learn How to Create Your Own API
In the course below, you will learn how to use Swagger to create an interface for your API so that you can test it.

- [ ] [Course - SECTION 7 ONLY - ASP.NET Core 6.0 Course - MVC - Blazor - Razor - EF Core](https://www.udemy.com/course/aspnet-6-course/)
- [ ] [Learning Path - Microsoft - REST APIs](https://learn.microsoft.com/en-us/training/modules/build-web-api-aspnet-core/)

## Learn about Security and Authorization

- [ ] [Course - SECTION 8 ONLY - ASP.NET Core 6.0 Course - MVC - Blazor - Razor - EF Core](https://www.udemy.com/course/aspnet-6-course/)
- [ ] [Learning Path - Microsoft - Secure a .NET web app](https://learn.microsoft.com/en-us/training/modules/secure-aspnet-core-identity/)

## Next Steps
At this point, you have some solid back-end skills. A logical next step is to ensure that you understand Razor pages well. If you do, and can modify them, then congratualtions! You can develop full-stack applications, especially after you've completed section Eight of the ASP.NET 6.0 Course. This is a huge first step. But to make yourself truly marketable, it is important to learn a popular library or framework.

### Learn React
In most cases, if you want to become a full-stack developer, the logical next step is to learn React. You can do that through Yihua Zhang's The Complete React Developer Course from Zero to Mastery. In Yihua's course, you will build an app with Firebase. I recommend going through Yihua's course and then, as a special challenge for yourself, rebuild the back-end with C# and SQL server and deploy that to Azure DevOps.

### Learn DSA in C#
I suggest getting a solid foundation in data structures and algorithms in C#. To solidify your knowledge, one or two Zero to Mastery courses on this subject and implement your solutions in C#.

- [ ] [Course - Data Structures and Algorithms: In Depth using C#](https://www.udemy.com/course/data-structures-and-algorithms-in-depth-using-c-sharp/?src=sac&kw=c%23+data+str)
- [ ] [Course - Zero to Mastery - Master the Coding Interview: Data Structures and Algorithms](https://www.udemy.com/course/master-the-coding-interview-data-structures-algorithms/)
- [ ] Extra credit - [Course - Zero to Mastery - Master the Coding Interview: Big Tech (FAANG) Interviews](https://www.udemy.com/course/master-the-coding-interview-big-tech-faang-interviews/)
- [ ] Extra credit - Sign up for a Leetcode account for extra practice.

### Learn CI/CD, Unit Testing, and Microservices Architecture (in this order)
After you've done that, to get yourself closer to a senior-level developer, you can do the following, in this order. Specific details for suggested courses and resources coming soon...

#### CI/CD
- [ ] Learn about CI/CD and create build and release pipelines for your apps in Azure DevOps.

#### Unit Testing

#### Microservices
- [ ] Learn about Microservices in C#.

*Note: It is perfectly valid to deploy to AWS instead of Azure DevOps, but most courses that cover C# will have you deploy to Azure DevOps. It is also a little easier for beginners, due to the GUI that Microsoft provides, but AWS is definitely more popular. If you want to learn AWS instead, you can take a look at this book: Developing on AWS with C# by Noah Gift and James Charlesworth*

## A Question You Might Ask
*Why are we skipping sections 4 and 5 in the C# course?* I'm glad you asked! The reason is that a number of large-scale applications are built with frameworks like Vue and Angular or with React (which is technically a library). As a full-stack software engineer, I am personally seeing much more demand for React skills than for Razor and Blazor. That said, it doesn't hurt to learn them so that you understand the trade-offs of using them versus a different framework.

In addition, the "headless" model is becoming more popular, but there are still plenty of apps that use MVC, and MVC is a great starting point to understand concepts like the separation of concerns.

## Extra Credit Reading
Coming soon...

## Resources For Those Struggling with the Above Concepts
1. C# 7th Edition - Anne Boehm and Joel Murach - A caveat: This book covers the database first approach to Entity Framework. Developers should learn the code-first approach first (see above).
2. ASP.NET Core MVC - Mary Delamater and Joel Murach
