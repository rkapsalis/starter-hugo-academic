---
title: Fix your recommender system to fix your profitability
subtitle: _How bias in Recommender Systems affects e-commerce, society and eventually your profits_

# Summary for listings and search engines
summary: _How bias in Recommender Systems affects e-commerce, society and eventually your profits_

# Link this post with a project
projects: []

# Date published
date: "2022-05-21T00:00:00Z"

# Date updated
lastmod: "2022-05-21T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/ZiQkhI7417A)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

tags:
- Recommender Systems
- E-commerce
- Machine Learning
- Bias

categories:
# - Demo

links:
  # - icon_pack: fab
  #   icon: twitter
  #   name: Follow
  #   url: 'https://twitter.com/Twitter'
  - icon_pack: fab
    icon: medium
    name: Published on Medium
    url: 'https://medium.com/code4thought/fix-your-recommender-system-to-fix-your-profitability-d75c457c1c6c'
  - icon_pack: 
    icon: 
    name: Originally published on Code4Thought
    url: 'https://code4thought.eu/2022/05/16/fix-your-recommender-system-to-fix-your-profitability/'
---

> _How bias in Recommender Systems affects e-commerce, society and eventually your profits_

In 2021:

* **Almost 70%** of internet users in the EU, have bought or ordered goods or services for private use [source: [Eurostat](https://ec.europa.eu/eurostat/web/products-eurostat-news/-/ddn-20220202-1)].
* In the US, e-commerce sales were estimated to be approximately **870 billion** dollars [source: [Digital Commerce 360](https://www.digitalcommerce360.com/article/coronavirus-impact-online-retail/)].

Undoubtedly the COVID-19 pandemic has fuelled a significant increase in internet usage both in e-commerce sales and in content-provider systems. However, the key factor behind this increase is the utilization of Recommender Systems (RecSys) by an exponentially growing number of [services](https://www.mdpi.com/2079-9292/11/1/141/htm).
Recommender (or recommendation) systems* provide recommendations to users, based on user behavior data, either [explicitly or implicitly](https://en.wikipedia.org/wiki/Recommender_system#:~:text=When%20building%20a%20model%20from%20a%20user%27s%20behavior%2C%20a%20distinction%20is%20often%20made%20between%20explicit%20and%20implicit%20forms%20of%20data%20collection.). Ideally, RecSys offer continuous user engagement with content, as well as increasing loyalty and satisfaction of users. But what are the major contributing factors behind these?

1. RecSys can provide personalized content. A [recent study](https://www.mckinsey.com/business-functions/marketing-and-sales/our-insights/the-value-of-getting-personalization-right-or-wrong-is-multiplying) in the US showed that **71%** of customers expect companies to deliver personalized interactions and **76%** of them get frustrated when they don't get it.
2. RecSys can offer a vast amount of similar items to those recently purchased, viewed or rated by the users and as a result they spend more time interacting with the products.

What is more, these systems can have a serious impact on sales promotions (e.g. what types of products users can select and consume), as sellers can persuade customers to buy specific items. All the aforementioned benefits of RecSys can lead to increased consumption and thus, higher profits for businesses.
<figure>
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/n4pe2av4ncbytuq8rudx.png">
  <figcaption>Image 1: Examples of RecSys benefits on popular systems</figcaption>
</figure>
 
&nbsp; 

## Bias in RecSys
Despite the above mentioned benefits of RecSys, there are a number of performance and ethical issues that need to be addressed and investigated. Apart from well known performance issues in RecSys such as [cold-start and data sparsity](https://www.ijcai.org/Proceedings/13/Papers/495.pdf), little attention has been paid to ethical issues, until recently. In this article, we will focus on how the ethical issues related to recommender systems and their impact merely on us (either as consumers or citizens and users) can also significantly impact e-commerce platforms.

<figure>
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rugcflsfha3faunf7ac0.png">
  <figcaption>Image 2: Long tail diagram (dataset: <a href="https://grouplens.org/datasets/movielens/100k/">movielens-100k</a>)</figcaption>
</figure>

One of the most important types of bias that arise in RecSys is **popularity bias**. This type of bias describes the phenomenon of popular items ("head") being recommended frequently while less popular ("long-tail"), niche products, are recommended rarely or not at all. The 80/20 ratio is based on the Pareto principle: for many outcomes, roughly 80% of consequences come from 20% of cause.
> But why is popularity bias so important?

&nbsp; 

## Popularity bias in society
It was previously mentioned that RecSys offer continuous user engagement and [this is highly correlated with company profitability](https://www.forbes.com/sites/michaelfertik/2019/12/16/why-customer-engagement-should-be-every-businesss-top-priority-in-2020/?sh=387165706214). The more the users are engaged the more likely it becomes for a platform to increase their sales as well as their profitability. But that doesn't come without a cost.
First and foremost, popularity bias in RecSys highly affects society. For instance, it has played a vital role in the wide spread of misinformation and fake news as [it hinders significantly the quality of the content provided to users](https://www.nature.com/articles/s41598-018-34203-2). Additionally, the article "[How Facebook got addicted to spreading misinformation](https://www.technologyreview.com/2021/03/11/1020600/facebook-responsible-ai-misinformation/)", describes a similar case. There we can see that machine learning models programmed to maximize engagement bear the risk to increase polarization, amplify fake news and hate speech and lead to unpredicted consequences, such as election sway and the genocide of the Rohingya Muslim minority in Myanmar.
Popularity bias [is also highly connected with a phenomenon called "echo chambers"](https://www.nature.com/articles/s41598-018-34203-2) where users only encounter opinions that reflect and reinforce their own, without encountering opposing opinions.

<figure>
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/vnhf3xcxme5e8jmu2jy2.png">
  <figcaption>Image 3: Echo chambers on Twitter. Nodes represent a user who sent a message, and edges, a user retweeting another user (Blue represents liberals and red conservatives) [Source: <a href="https://www.pnas.org/doi/10.1073/pnas.1618923114">PNAS</a>]</figcaption>
</figure>
 

&nbsp; 


## Popularity bias impact in e-commerce
The effects of popularity bias can also have a significant (negative) business impact especially on e-commerce systems. Apart from popularity bias, there are some other aspects of RecSys quality that need to be addressed, which are presented in Image 4.

<figure>
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kax3cggdlpjb2x4n2y2p.png">
  <figcaption>Image 4: Aspects of RecSys quality and their business impact</figcaption>
</figure> 
 

&nbsp; 


## Study & Findings
In order to investigate the business impact of popularity bias and of the other aspects of RecSys quality (Diversity, Coverage and Novelty) and to gain a better understanding of their sources, an extensive study was held by our team, using a real dataset provided by a major electronics retailer. The dataset contained 8.263 ratings, 3.078 products and 276 users.
The first step of the process was to build 11 different RecSys models utilizing 11 different algorithms, from classical to the most recent, State-Of-The-Art, approaches (see Image 5 for more details). Each of these systems produced a list of 10 items for every user. Then, we had to evaluate the results produced by the respective RecSys. For this purpose 12 different metrics were selected.

<figure>
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/8hl0zpjuy22kle7tb728.png">
  <figcaption>Image 5: Algorithms and evaluation metrics used in the study</figcaption>
</figure>
&nbsp;

## Findings
The main findings of our study are as follows:

🔎  &nbsp; From [Average Recommendation Popularity (ARP)](https://arxiv.org/abs/1205.6700) (Image 6) it is apparent that **<u>most of the algorithms recommended the most popular items</u>**. More specifically, despite the fact that the average number of ratings per item in the dataset is 2.68, all the algorithms' scores, except ItemKNN, NGCF and Random are much higher than this value.
&nbsp; 

🔎  &nbsp; The algorithms used, not only recommend the most popular algorithms, but they tend to **<u>completely ignore user preferences</u>**, as shown in the [Popularity Ranking-based Equal Opportunity (PopREO)](https://dl.acm.org/doi/abs/10.1145/3397271.3401177) chart in Image 6.

<figure>
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/brwiwxj6xtutfgns458y.png">
  <figcaption>Image 6: Popularity bias as measured by 2 different metrics (the lower the better)</figcaption>
</figure>

 
🔎  &nbsp; The results of this study indicate that RecSys developers should be aware of the [bias-accuracy trade-off](https://blogs.oracle.com/ai-and-datascience/post/unlocking-fairness-a-trade-off-revisited) and should avoid using algorithms that enlarge this phenomenon (of bias), as shown in Image 7. It has to be mentioned that the poor results in accuracy are caused by the: 

1. very high percentage of dataset sparsity (almost 99%)
2. uneven distribution of ratings
3. relatively small number of ratings

<figure>
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ee8l772wk1ovbv6ntdiy.png">
  <figcaption>Image 7: Accuracy-popularity bias trade-off</figcaption>
</figure> 
 
🔎  &nbsp; Algorithms may not cover all the items given as input, this can be clearly seen in Image 8. Consequently, **a significant amount of items will remain unseen for the majority of users**, affecting the number of sales and decreasing user satisfaction. Moreover, it was found that diversity is not always connected with popularity bias and except our baseline algorithm, itemKNN and NGCF all the other algorithms are not enhancing diversity in recommended items

<figure>
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/c5f1kqqwxlhvd7hk4cgu.png">
  <figcaption>Image 8: Some RecSys algorithms have very low scores in Coverage, Diversity and Novelty</figcaption>
</figure>  
&nbsp; 

## Conclusion
In terms of accuracy, users should be highly encouraged to rate products. RecSys need vast amounts of data to produce meaningful results. But in most cases, there are a number of customers that haven't offered explicit feedback to the system. Cookies might be one of the most effective ways to overcome this problem by collecting user data. However this bears additional overhead for managing risks related to privacy and GDPR compliance.
&nbsp; 
As regards popularity bias and other aspects of RecSys quality, the proposed solutions depend on whether the e-commerce system owner has access to the model or not. If they have access to the model then a bias mitigation technique ([pre-processing, in-processing, post-processing or a combination of these](https://analyticsindiamag.com/a-guide-to-different-bias-mitigation-techniques-in-machine-learning/)) can be used. Otherwise, some other mediocre solutions can be applied such as encouraging users to rate recently purchased products.
&nbsp; 
Last but not least, bias can affect item providers (either sellers or manufacturers). The rationale behind this is that if the product belongs to the long tail category or if it is new, it may never be recommended to users.
In conclusion, e-commerce businesses need to control popularity bias, diversity and novelty because they highly affect user satisfaction and their profits as well.

---

*Note: in this article we refer to collaborative filtering systems and more specifically top-n recommenders that produce a list of top-n recommendations, as an output, for each user.
<!-- ## Overview

1. The Wowchemy website builder for Hugo, along with its starter templates, is designed for professional creators, educators, and teams/organizations - although it can be used to create any kind of site
2. The template can be modified and customised to suit your needs. It's a good platform for anyone looking to take control of their data and online identity whilst having the convenience to start off with a **no-code solution (write in Markdown and customize with YAML parameters)** and having **flexibility to later add even deeper personalization with HTML and CSS**
3. You can work with all your favourite tools and apps with hundreds of plugins and integrations to speed up your workflows, interact with your readers, and much more

{{< figure src="https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/master/academic.png" title="The template is mobile first with a responsive design to ensure that your site looks stunning on every device." >}}

## Get Started

- 👉 [**Create a new site**](https://wowchemy.com/templates/)
- 📚 [**Personalize your site**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=(%23MadeWithWowchemy%20OR%20%23MadeWithAcademic)&src=typed_query)
- 💡 [Request a **feature** or report a **bug** for _Wowchemy_](https://github.com/wowchemy/wowchemy-hugo-modules/issues)
- ⬆️ **Updating Wowchemy?** View the [Update Tutorial](https://wowchemy.com/docs/hugo-tutorials/update/) and [Release Notes](https://wowchemy.com/updates/)

## Crowd-funded open-source software

To help us develop this template and software sustainably under the MIT license, we ask all individuals and businesses that use it to help support its ongoing maintenance and development via sponsorship.

### [❤️ Click here to become a sponsor and help support Wowchemy's future ❤️](https://wowchemy.com/plans/)

As a token of appreciation for sponsoring, you can **unlock [these](https://wowchemy.com/plans/) awesome rewards and extra features 🦄✨**

## Ecosystem

* **[Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli):** Automatically import publications from BibTeX

## Inspiration

[Check out the latest **demo**](https://academic-demo.netlify.com/) of what you'll get in less than 10 minutes, or [view the **showcase**](https://wowchemy.com/user-stories/) of personal, project, and business sites.

## Features

- **Page builder** - Create *anything* with [**widgets**](https://wowchemy.com/docs/page-builder/) and [**elements**](https://wowchemy.com/docs/content/writing-markdown-latex/)
- **Edit any type of content** - Blog posts, publications, talks, slides, projects, and more!
- **Create content** in [**Markdown**](https://wowchemy.com/docs/content/writing-markdown-latex/), [**Jupyter**](https://wowchemy.com/docs/import/jupyter/), or [**RStudio**](https://wowchemy.com/docs/install-locally/)
- **Plugin System** - Fully customizable [**color** and **font themes**](https://wowchemy.com/docs/customization/)
- **Display Code and Math** - Code highlighting and [LaTeX math](https://en.wikibooks.org/wiki/LaTeX/Mathematics) supported
- **Integrations** - [Google Analytics](https://analytics.google.com), [Disqus commenting](https://disqus.com), Maps, Contact Forms, and more!
- **Beautiful Site** - Simple and refreshing one page design
- **Industry-Leading SEO** - Help get your website found on search engines and social media
- **Media Galleries** - Display your images and videos with captions in a customizable gallery
- **Mobile Friendly** - Look amazing on every screen with a mobile friendly version of your site
- **Multi-language** - 34+ language packs including English, 中文, and Português
- **Multi-user** - Each author gets their own profile page
- **Privacy Pack** - Assists with GDPR
- **Stand Out** - Bring your site to life with animation, parallax backgrounds, and scroll effects
- **One-Click Deployment** - No servers. No databases. Only files.

## Themes

Wowchemy and its templates come with **automatic day (light) and night (dark) mode** built-in. Alternatively, visitors can choose their preferred mode - click the moon icon in the top right of the [Demo](https://academic-demo.netlify.com/) to see it in action! Day/night mode can also be disabled by the site admin in `params.toml`.

[Choose a stunning **theme** and **font**](https://wowchemy.com/docs/customization) for your site. Themes are fully customizable.
 -->
<!-- ## License

Copyright 2016-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/wowchemy/wowchemy-hugo-modules/blob/master/LICENSE.md) license. -->
