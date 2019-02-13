# MultiLanguageDemo
Get Insight to create your first Multi-Language application MVC Application

This demo project explains how to create a simple Multi-Language ASP.NET MVC 5 Web application. The application will be able to deal with English (United States), Spanish and French languages. English will be the default language. Of course, it will be very easy to extend the solution for including new languages.

To begin with, it's assumed that readers have a basic knowledge on ASP.NET MVC 5 framework. Other related technologies such as jQuery will be slightly commented througout the article owing to they have been used to add new functionality. I will focus my explanations on MVC framework components. Anyway, I will try to explain how each component works or, at least, providing you with links to get more detailed information. It's not the goal of this article to explain each line of code for each technology or repeat explanations that are very well documented in other articles. My goal will be to explain the main features of our demo application at the same time as remember key issues to get better insight and understanding.

That being said, our demo application will have a HomeController with three basic typical actions such as Index, About and Contact. Besides, we will derive this controller from a BaseController, as we will see later, to provide every controller with common functionality. So, content rendered in Views called from HomeController will be localized according to default or user selected language.

https://www.codeproject.com/Articles/1160340/Get-insight-to-build-your-first-Multi-Language-ASP
