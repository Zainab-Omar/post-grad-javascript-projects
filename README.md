# Upgrade Your JavaScript Project

## Introduction

JavaScript is everywhere. Although you'll find many strong opinions about
JavaScript, it continues to be critical to web development and has earned a
place as one of the most popular and widely used programming languages because
of it. Since it is so widely used, JavaScript is often offered as a language
option during coding interviews.

For these reasons, taking the time to practice your JS skills is definitely
worth it during the job search. By upgrading your portfolio project, you can do
just that while building a clear example of your abilities. Below are some
suggestions for what you can do to enhance your JavaScript project. As
JavaScript projects are made for the web, ideas for improving HTML and
CSS are also included here.

## Refactor

Similar to your Rails and CLI projects, refactoring a previous project is a good
way to assess how your abilities have improved. Consider the following questions
when refactoring your code:

- **Is the code DRY? Is there any redundant content that could be reduced or
  abstracted?** Under time constraints, it is easy to forgo the [Don't Repeat
  Yourself][dry] principle. There is no due date anymore, so take some time to
  clean up any repetitive patterns in your code.

- **Can you spot and unnecessary or overly complicated code?** While learning the
  basics, it is possible to misunderstand how specific code works. Sometimes, we
  try things until something sticks. Sometimes, the moment a piece of code
  works, we move on to the next task without reconsidering what we've written.
  Now is the time to look back and find examples of this in your project.

[dry]: https://en.wikipedia.org/wiki/Don%27t_repeat_yourself

For JavaScript in particular:

- Take out any JavaScript that exists in your HTML. Sometimes JavaScript can get
  added directly into an HTML file as a quick fix. This can make it more
  difficult to understand how things work.
- Think about how your code is structured. Most projects start off with a single
  `index.js` that contains _everything_. As a project gets more complex, having
  everything in a single file can make it challenging to understand what is going
  on, particularly for someone not familiar with it. First, take some time to
  organize your code so that it reads in a logical order. Second, consider
  breaking your code out into multiple files. This is not only an excellent way to
  refactor, but also to review how everything works. You can load the different files
  using HTML `script` tags.

For HTML and CSS:

- Use [Semantic HTML elements][] instead of generic elements like `div`. With
  semantic elements, you can convey _what_ a part of your HTML is for.
- Move all CSS to a separate, organized file. Sometimes we insert in-line CSS or
  `style` tags as a quick styling fix. The downside is that we end up cluttering
  HTML files. Also, styling defined in an HTML file usually takes precedent over CSS
  rules defined in a file, which can potentially cause unexpected styling behaviors.

[Semantic HTML elements]: https://www.w3schools.com/html/html5_semantic_elements.asp

## Finish and Add Features

Your project may meet all the requirements that were laid out at the time and be
slightly past the MVP stage. However, this does not mean it is fully developed.

Think about what features you can add to bring it to the next level. A few
suggestions specific to your JavaScript project:

- You should have some basic communication between your backend and frontend for
  CRUD functionality already. What else can be added? Are there any backend
  calls you weren't able to implement? Can you implement user authentication?
- Are there any external APIs that could be used to boost your project's
  functionality?

For your CSS:

- Establish a consistent theme across your app. CSS is often the last
  thing students work on during their JavaScript project, but it can also make
  your app more visually appealing. Non-technical visitors to a website may not
  grasp how complicated the code behind it is, but they can definitely recognize
  a well-designed website.
- Make your app responsive. Using [media queries][], design your
  project so it looks good regardless of whichever device it is being viewed on.

[media queries]: https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries

## Make Your App Accessible

Another vital addition you should consider for your JavaScript project is
accessibility. The internet is an essential resource for millions of people, but
many websites lack accessibility options, making them difficult or impossible to
use for many people.

For more information on web accessibility and why it is important, check out the
World Wide Web Consortium's [Introduction to Web Accessibility][access]. For
specific ideas on how you can make _your project_ more accessible,
[read through this checklist to help guide you][checklist].

[access]: https://www.w3.org/WAI/fundamentals/accessibility-intro/
[checklist]: https://dev.to/sylwiavargas/checklist-web-accessibility-3abl

## Deploy to GitHub

Deploying your project is essential for showcasing your skills. Sometimes,
potential employers may utilize a non-technical recruiter to find candidates to
hire. These recruiters won't be looking at your code on GitHub. Even for
recruiters or interviewers that have the technical skills to understand your
code, having a live, functioning example of your work is a way to generate
interest in your abilities.

There are many ways to deploy HTML and JavaScript sites online. Since your
projects are already hosted on GitHub, however, we recommend using
[GitHub Pages][] to deploy the frontend of your project. For many basic
projects, deploying is as simple as turning on the feature in your project's
**Settings** tab.

For the Rails backend, we recommend [Heroku](https://www.heroku.com/). Heroku
has a free hosting tier that many students have utilized over the years.
[They provide a detailed tutorial on how to get your Rails app deployed][heroku deploy].

> **Recommended:** Once you've deployed your project, make sure to do some
> quality assurance testing:
>
> - **Test every route on your backend**. Make sure your frontend and backend
>   are communicating properly.
> - **Click every link**. Make sure there are no bad links on your frontend.
> - **Navigate around your app in different ways**. If a visitor does something
>   slightly unexpected, can your app handle it?
> - **Open your app using a variety of devices and browsers**.
> - **Share the app with some friends and ask them to play around with it**. You
>   might know how things are supposed to work, but giving your app to someone
>   else can identify unexpected user behaviors. Better that your friends find
>   these and not a potential employer.
>
> Deploying your app is a big plus for building your online presence, but
> **deploying a broken app can be worse than not deploying anything!**

[GitHub Pages]: https://pages.github.com/
[heroku deploy](https://devcenter.heroku.com/articles/getting-started-with-rails5)

## Record a Demo Video

When your project is fully functioning and looking great, consider recording a
demonstration of how your app works. Recording a demo allows you to showcase
features you're particularly proud of. It also means you can provide context to
your application that may not be apparent from just looking at the app itself.

A demo recording should go through the essential parts of your application. One
bonus that comes from doing this - during interviews, you will often need to
talk about your projects. If you have a project listed on your resume, assume
that you may need to explain what the project is, as well as the challenges you
faced during development. A demonstration video will force you to practice this
pitch so you'll be more comfortable when you have to do it live.

A demo recording also acts as an excellent way to introduce yourself. You can
use it to show off a bit of your personality. It also shows your ability to
communicate complex topics - a critical skill on all tech related teams.

## Conclusion

As mentioned earlier, JavaScript is commonly used for interviews. Surveys
conducted by StackOverflow indicate that JavaScript is the most widely used
programming language currently. Don't just expect it to come up - prepare ahead
of time with a fantastic example of your skills!

- [Make your app accessible](https://dev.to/sylwiavargas/checklist-web-accessibility-3abl)

