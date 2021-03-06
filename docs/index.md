---
layout: default
toc_entry: index
---
# Introduction

This document set describes how to build a Personal Information Managment (PIM) system as discussed in the related of the blog post [A Personal Information Management System: Introducing Scrapbook][blog]. In that post we describe why we built our own PIM system and we take a high-level look at how it was built. We call our PIM system "Scrapbook". This web site discusses in detail how you can create a version of Scrapbook yourself on Windows using the .NET Framework or .NET Core. In the interest of reduced complexity, we present here a simplified version we call {{site.sn}}. 

After building and running the code, you should have a simple {{site.sn}} site populated with ten entries and supporting assets. 

This document set covers both {{site.sn}} implemented on the .NET Framework and .NET core. There is also another documentation site (yes, we love to document!) that is built with a different technology. That sister website is [travelmarx.github.io/scrapbook101core/][newsite].

---
**NOTE**

Updates to this code and documentation for the .NET Framework Scrapbook101 (this site) stopped in September 2019. All further development code-wise and documentation-wise will be on [travelmarx.github.io/scrapbook101core/][newsite].

---

## A brief recap

The blog post referenced above discusses our reasons for creating a Scrapbook application. To summarize, in our PIM we wanted to:

* Deal with ever-increasing amounts of personal **archival** data, both physical and digital, in a consistent way.
* Capture **context** about data so that when we referred to our data int the future we would understood why we saved it and why it was important.
* **Find** our data quickly and on-demand, for example, using natural language or a chat bot.
* **Own** our data and not have it live in a social network or service that locks the format or controls our access to it.

The way we could accomplish this was to create a custom PIM system consisting of software, programming frameworks, and cloud services working together to achieve the four principles described above.

While {{site.sn}} is a pared-down version of what we described in the blog post, it has enough of the basic functionality to be a good starting point for someone interested in creating their own Scrapbook.

## Why this site?

Why is {{site.sn}} documented here and not on [blog.travelmarx.com][tm]? For two reasons. First, we were interested in trying out [GitHub Pages][ghp] for technical documentation. And second, demonstrating code and talking about it in a Blogger post is not easy for a writer or reader. Hence, this GitHub Pages site was born.

Creating this site was an odyssey into new tools and practices that we thought were interesting to document as well. If you want to know a little bit about how this site was created, see [About This Site][about].

We also have documentation created with [docFX][docfx], which is here [travelmarx.github.io/scrapbook101core/][newsite]. Docfx enables you to build documentation like shown here (conceptual topics) along with the API documentation (which we can't with the technology used here, Jekyll).

[about]: about-this-site
[web]: https://travelmarx.github.io/scrapbook101/
[blog]: http://blog.travelmarx.com/2017/12/a-personal-information-management-system-introducing-scrapbook.html
[demo]: http://www.travelmarx.com/
[tm]: http://blog.travelmarx.com
[ghp]: https://pages.github.com/
[doc]: https://travelmarx.github.io/scrapbook101core/
[docfx]: https://dotnet.github.io/docfx/
[newsite]: https://travelmarx.github.io/scrapbook101core/
