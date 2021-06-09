# Headless WordPress
### GatsbyJS or NextJS

---

> ## What is a Headless WordPress?

> A headless WordPress site is one that uses WordPress for managing content and some other custom frontend stack to display that content. Headless WordPress enables content writers to use a familiar interface while giving web developers the flexibility to use any frontend technology stack.


---

# Should I use Headless WordPress?
Benefits

---
> ## Performance
>Headless WordPress only connects to your sites and apps through an API rather than having a login screen right there on the front end server.

---
> ## Security
> Consequently, hackers will have a much harder time brute forcing their way into your sensitive content.

---
> ## Future Proof Solution
> Headless CMS enables you to release content. You can deliver the content to Smart Speakers, Mobile Apps, VR/AR, Smart refrigerators, Connected cars, Moreover, it can assist you to send in devices that are yet to be released.

---

# CSR or SSR?

---

> The difference between CSR and SSR is when the page's HTML is generated.
> When using CSR, the HTML is generated in build time. Client Side Rendering pre-rendering makes it easy to cache and fast to deliver.
> _The term “static” comes from the fact that the HTML is static._ But it doesn't necessarily mean that the page is static.

---
> ## Client Side Rendering
>While you may not be familiar with this term, you're more than likely familiar with how you'd implement one of these; After all, this is the default when building an Angular, React, or Vue site.you'd:

---

> - You build the React code
> - You put it on a server
> - The client downloads the React code from the server
> - The React code runs and generates the HTML/CSS on the client's computer
> - The user then sees the content on screen after React runs

---

> ## Server Side Rendering (SSR)
> Because React has to initialize somewhere, what if we were to move the initial rendering off to the server? Imagine - for each request the user sends your way, you spin up an instance of React. Then, you're able to serve up the initial render (also called "fully hydrated") HTML and CSS to the user, ready to roll. That's just what server-side rendering is!

---

> - You build the React code
> - You put it on a server
> - The client requests data
> - The server runs the React code on the server to generate the HTML/CSS
> - The server then sends the generated HTML/CSS on screen
> - The user then sees the content on screen. React doesn't have to run on their computer

---

# GatsbyJS
[https://www.gatsbyjs.com/docs/](https://www.gatsbyjs.com/docs/)

---

> Gatsby is a meta-framework on top of React, there are very few limitations to what you can build with it — if you can build it with React, you can most likely build it with Gatsby. However, Gatsby adds powerful features on top of React that improve developer experience, site performance, and overall shipping velocity.

---

> Gatsby opens up many technological possibilities that can be highly beneficial for the project.
> The developer has more freedom in choosing tools, which allows them to make a truly customized and outstanding both user and development experience.

---

> - Gatsby allows you to bring your data from anywhere. … WordPress
> - Gatsby gives you fantastic performance out of the box.
> - Gatsby has an extensive open source ecosystem.
> - Gatsby's documentation is world-class.
> - Gatsby has a steep learning curve.
> - Gatsby has a lot of magic.

---

# NextJS
[https://nextjs.org/docs](https://nextjs.org/docs)

---

> NextJS is a open-source framework for building React applications. It comes with server-side rendering, serverless functions, SEO support and so so much more, out of the box.

---

> Next.js provides a backend that can server side render a response to request, allowing you to create a dynamic website.

---

> - Hot Code Reloading
> - Automatic Routing
> - Single File Components
> - Server Rendering
> - Ecosystem Compatibility
> - Automatic Code Splitting

---

# GatsbyJS or NextJS

---
GatsbyJS or NextJS
# Is Good for SEO?

---

> **Next:** It's super good for SEO because it allows to utilize server-side rendering (SSR). With SSR, your React websites and apps take lesser time while loading for the first time. Also, search engines can crawl NextJS websites and apps more easily.

---

> **Gatsby:** Gatsby is purely SEO friendly as the websites and apps built with Gatsby deliver pre-rendered HTML. your websites have good Lighthouse scores giving brilliant user experience (UX).

---
GatsbyJS or NextJS
# Server Side Rendered vs Statically Generated?

---
> Gatsby is a static site generator tool. A static site generator generates static HTML on build time. It doesn’t use a server.

---
> Next.JS is mainly a tool for server-side rendered pages. It dynamically generates the HTML every time a new request comes in with the use of a server.

---

# Of course, both can call APIs client side.
### The fundamental difference is Next requires a server to be able to run.
### Gatsby can function without any server at all.

---

GatsbyJS or NextJS
# Data Handling

---

> A fundamental difference between the tools is the way in which they handle data.
> Gatsby tells you how you should handle data in your app.
> Next leaves the decision entirely up to you.

---
> **Gatsby** uses something called GraphQL. GraphQL is a query language and if you’re familiar with SQL, it works in a very similar way. Using a special syntax, you describe the data you want in your component and then that data is given to you.

---
> Next on the other hand, how you manage your data is completely up to you. You have to decide on your own architecture how to manage data. The benefit of that is that you aren't tied into any tech that you may or may not want to be using.

---

# So what should I choose?
### Whether you should use Gatsby or Next depends very much on your use case, as really they are both awesome.

---
> ## When To Use Next.JS
> If you have lots of content or if you expect your content to grow a lot over time, then static generated web pages are not the best solution for you. The reason is that it takes much time to build the site if you have lots of content.

---
> ## When to Use Gatsby
> This is my personal preference, I use Gatsby when I am building my websites and blogs. The eco-system is perfect for hooking up to WordPress (it is literally a breeze) and there are some awesome guides on how to get going with it all.

---
## Cons?
There are no cons choosing between GatsbyJS or NextJS,
both are great tools and fit pretty well in the headless ecosystem.







