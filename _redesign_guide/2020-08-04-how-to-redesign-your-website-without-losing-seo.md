---
title: 'Extra: Redesign SEO Troubleshooting'
date: 2020-07-29
description: A post
featured_image:
---




Launching a new website or changing content on the site without the input of someone who's thinking about the technical marketing side of your design can lead to some unintended consequences.







_We wrote another article on common reasons organic search traffic decreases. Sometimes it just happens. Read that and save yourself a lot of headache before digging into the technical SEO._







## List of the top technical SEO issues that cause traffic drops after redesign







### Changing your important search engine elements







Sometimes a developer will clone content from the site perfectly. Other times, they will forget to carry over the important things. Here's a short list of items you must copy perfectly:







  * Meta title
  * H1
  * Linking within content (most notably, the internal links to your other pages)
  * Other headers (H2, H3 most importantly)
  * Image titles and alt tags
  * Meta description






### Changing URLs







**This is almost always the main factor causing traffic drops after a redesign.**







Another way redesigning or changing your website can affect your search rankings is by changing the URLs. The URL of your web pages is extremely important. This is what Google will cache in a search engine results page. It's also what contains your internal and inbound link signals.







Let's take a look at a very common example of a link change during a website redesign:







**Previous URL:**








https://www.gaintap.com/services/seo/








**New URL:**








https://www.gaintap.com/our-services/seo/








All we did here was change the "services" category to "our-services." Not a big deal, right? Wrong! By doing this we just created all these issues:







  * Any links pointing to the previous URL are now broken. This means if we had lots of positive inbound links going to that page, they no longer help rank that page or the site. It also means our internal navigation to that page is broken.
  * Google is now ranking both results in search. Even though there is just one page of content on our site, that old URL is cached in Google's results. Most likely, people will click that old result and get a 404 page.
  * That page is going to have to get recrawled, cached and signals will have to build up from scratch.






**The importance of 301 redirects**







In order to prevent all those bad things from happening, we need to use a 301 redirect to point the old URL to the new URL. If you're on Wordpress, a plugin like [Redirection](https://wordpress.org/plugins/redirection/) is suggested. You can also modify your redirects in your .htaccess file but this is something an experienced developer should handle for you.







**More on those broken links...**







When you change your URLs you break any internal links or external links pointing to that URL. This is really bad because if you have good links pointing to a page, those links will no longer increase the ranking potential of this page or your site. Broken links are a major reason for ranking drops during site launches. It is extremely important to work with someone who is knowledgeable about search engine optimization and not just a web development company or designer. Not all designers and developers think about search engine optimization.







### Improper migration off a development site







Another reason you may see ranking drops and traffic drops after launching a new website is because the developer did not fully migrate your site off the development server. Most development sites will have the following in place:







  * A robots.txt file that blocks all search bots
  * Development domain or subdomain (mysite-dev.com or dev.mysite.com for example)






#### Failure to update the robots.txt file







Sometimes a site will launch without updating the robots.txt file. This prevents your site from being crawled and all pages will drop out of search results. This obviously kills your traffic.







#### Leaving "no-index" tags in







Sometimes a developer will apply the "no-index" tag directly to thesection of the site. In this case, this needs to be removed from all pages that you want ranking in search.







#### Leaving development links in the new site







This is most common with images and direct linking internally. All links with the development site's URL should be updated to the live site's URL. If you're on Wordpress you can use a find and replace plugin or do a SQL query in your database.







**Sub-domain example**







Here's an example of a possible development server subdomain.







**Development site**: http://**dev**.mysite.com/services/







**Live site**: http://**www**.mysite.com/services/







**Domain example**







Here's an example of a development server using a totally different domain.







**Development site**: http://www.**mysite-devserver**.com/services/







**Live site**: http://www.**mysite**.com/services/







#### Leaving the development site up after launch







Sometimes a developer will leave the development site up after launch. This causes a few major issues.







First, if the development site is direct linking to the live site, you will have a ton of links pointing to the live site that look spammy.







Second, you may be linking back to the development site from your live site. Doing this causes search bots to crawl your live site then crawl your development site. This caches the development site in search which makes it look like your site is a complete clone of another site. Use a [tool like Screaming Frog](https://www.screamingfrog.co.uk/seo-spider/) to crawl your site and identify these issues.







## Content changes can affect SEO due to:







  * Changing content like text, images, links, or removal of entire pages
  * Changing the structure of your website such as moving content categories under different areas of the site
  * Adding lots of poorly optimized images, video and animations that slow down the browsing experience
  * Changing the URLs of your content which causes them to get re-cached as new pages and breaks incoming links
  * Failure to keep the same page titles and meta descriptions






## How design and SEO often clash.







![An example of an H1 and H2 tag. The H2 is larger than the H1 in this example. Most designers will use the H1 because it is larger, in reality it should be used for the most important terms of the page.](https://www.gaintap.com/wp-content/uploads/2017/05/h1-h2-example.jpg)_Most website designers and editors will use the H1 tag to style text to be larger than other text on the page. For SEO purposes, the H1 tag should be the tag that "summarizes" your page content. It's an important ranking factor and shouldn't be used just to style text. In this example, the H1 and H2 tags have been used for SEO and not styling. The H2 has been styled using CSS to be larger than the H1 because the H1 tag carries the "money terms" for this web page. This illustrates how using HTML tags for design can have a negative impact on SEO by sending misleading signals to Google._







It's important to note how design changes affect the SEO on your site. Some will have little impact on your traffic. If you change the site background from red to orange, expect little change. However, if you decide to remove all of your H1 tags on your pages, you may see your search rankings slide.







Why is this the case? Because Google has a ton of indicators it looks at when it ranks content and H1 tags are one of them. The H1 is meant to be the visible title of the page. Misusing it for styling text is going to throw weird signals at Google about what your page is about.







There is even an overlap with images. For example you may be replacing all your stock photos with new illustrations. Visually, we're seeing a design difference. But "under the hood" in the code, you need to make sure that the title of the image and the alt tag of the image stays the same as this is important content for search engines. You may also have links from other websites pointing to those images and removing them will break "the good stuff" Google looks at as a ranking factor.







## Common ways a redesign can cause SEO issues.







Here are some major common issues that can affect your search traffic after relaunching your site. There are almost always going to be exceptions for everything so if you want a professional opinion on your situation get in touch with us about our [technical redesign services](https://www.gaintap.com/capabilities/redesigns/).







### Reducing the amount of text on a page gives Google less context about your topic







One way you can kill your search rankings is if you reduce the text drastically on a web page. For example if you go from a page that has 1,600 words of content, presuming this is high quality writing, to a web page that has 300 words, you will likely lose search rankings in Google and other search engines. This is because the search engines rely on that text to tell them what your web page is about. If you do this to pages that send visits to your site you will see a noticeable drop in your search traffic. If you do this to pages that send people to your site who buy things, then you will see a drop in sales.







### Reducing the number of pages breaks links and reduces your keyword variations







I've seen this on some sites when they launch their website and are revising their service offerings. They will remove pages or sometimes hundreds of pages. Again, it's the same as above. If you do anything that reduces the number of people who visit your site _and buy from you,_ you're going to see a drop in sales.







I'm not talking about removing duplicate pages of content, pages that get zero visits, correcting scripting issues that generate bogus pages and that stuff. I'm talking about doing things to the content on your website that negatively impacts getting qualified people to it from organic search.







When you remove pages you risk:







  * Breaking links pointing to them from other quality websites
  * Breaking links pointing to other pages on your website
  * Reducing your ability to rank for searches because you no longer have content Google wants to show






All of these things can affect your organic SEO. Let's talk about ways to reduce the risks when you redesign your content.







## Playing it safe with SEO while updating your content







### **Identify key pages, proceed with caution**







When making edits to your website's content you should keep in mind which pages are driving traffic to your site and prioritize these. Make sure you carefully edit the content as needed. Use a scalpel, not a cleaver. If you don't know how to do this, get in touch with us.







However, if a page is not sending traffic to your site, by all means you should edit this page in order to get Google or other search engines to care about it. Consider consolidating content from poor performing pages to create a cohesive "bigger" post that answers more questions around a topic. Or split up a page that covers too many different topics and create smaller more focused chunks. You can even link them together into a multi-step guide.







### **Cross-sell, don't cut**







Think twice before removing a page for an old product or service you no longer offer. If it's bringing in traffic that's _related_ to your services and products, it's best to cross-sell on that page versus completely removing it.







Take a look at this page from Best Buy for an out-of-stock item. What do you notice?





![Selection of phones on Best Buy illustrating how to properly keep a web page without removing it](https://www.gaintap.com/wp-content/uploads/2017/05/bestbuy-item-out-of-stock.png)_This page for an out-of-stock item on Best Buy's website shows how you can keep a page and funnel traffic from it to similar pages. The original searcher is looking for a specific mobile phone and is presented with other options to choose from. This not only preserves some of the SEO and visits, it likely results in more sales for the company than if they removed the page._





They could have removed this page and let you land on a dead 404 page. But you're more likely to stay if you see something similar to what you expected to see in the first place, like more phones.







**Now here's the important part about SEO and traffic that is often disregarded during redesigns.**







This is a screenshot of the estimated search metrics for this product page. Roughly 1,000 visits per month from Google organic search.





![Organic traffic history from AHREFs for bestbuy.com for their Blackberry Keyone page](https://www.gaintap.com/wp-content/uploads/2017/05/organic-traffic-for-keyone.png)_This image shows you a screenshot of the estimated organic search metrics for Bestbuy.com specifically for the out-of-stock Blackberry Keyone's product page. There are roughly 1,000 visits from the USA per month. If this page was removed it would likely drop out of Google's search index and they'd no longer receive visits to this page._





If they killed this product page, this URL would drop out of Google's search index and they'd likely lose these visits unless they have other Blackberry Keyone content that can rank. Instead, they grab these visits and put another product in front of them that they may be willing to buy.







### **Understand how people use your site before cutting content**







It's important to understand how people use your website before making changes. Here's an example from a past client. I worked with a company that wanted to focus more on high-end audio visual sales. They had a very popular product on their site that they wanted to get rid of. It was for easel rentals, literally pads of paper on stands that would be used during meetings or event conferences. Their sales team decided to remove the easel rentals from their website along with hundreds of other products that they thought were two low-end and were not leading to these bigger sales. What do you think happened?







They lost visits and sales for these products, but they also lost bigger sales opportunities. Why? Because they couldn't up-sell this traffic. They couldn't educate these visitors on their higher level services. If a meeting planner who wanted a $50 easel rental gets educated on the company's nationwide coverage and bigger services, they may work with the company for those bigger services.







I hope this has helped you think more carefully about your site migration or redesign. If you have questions please ask us we are also happy to help consult with you on your website changes.



