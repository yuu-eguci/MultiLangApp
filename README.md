# MultiLangApp

Create multilingual localized app using ASP.NET MVC and deploy onto Azure.

## Development status

As easy deploy to Azure and multilingual support trial had been finished, this project has ended up.

I might clone it again only if I got something to be tried with ASP.NET MVC.

![](media/media.png)

## Problems left

It has the problem that the project doesn't have enough bin files after the clone. This is because the dependencies written in packages.config are different from them in Web.config.

- **Microsoft.AspNet.Mvc** is written in packages.config and that will be actually installed.
- While Web.config requires **System.Web.Mvc**, which doesn't exist. And the build fails.

To resolve that, this project's git includes bin folder. I know that bizzare but no other ideas. What's wrong with you ASP.NET MVC?
