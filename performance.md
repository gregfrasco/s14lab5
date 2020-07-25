# Lab 5

## Performance Testing

Using Google’s PageSpeed Insight tools the lab5 Heroku site scores a 97 on mobile and 100 on desktop. The reason for a lower score is a lower score in the Speed Index for mobile and desktop. The Speed index shows how quickly the contents on the page are visibly populated. The site received a moderate speed ranking on mobile at 2.2 seconds and 0.6 seconds on desktop. To make improvements to the speed index, might want to try reducing initial server response time. Todo this might want to switch to a different hosting provider with more control. Using Heroku load balances and cost-saving measures come at a cost of response time. Perfectly excitable for hobby projects, but something to keep in mind. Another way to reduce time is to reduce the size of the CSS. I am using bootstrap CSS. I am only using a small number of classes for this project, and a non-minified version. Tree shaking and using a minified version would help, especially for mobile devices.

| Mobile                                                                                                        | Desktop                                                                                                       |
|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| ![image](https://user-images.githubusercontent.com/5147346/88445718-8bd51a00-cdf2-11ea-86ae-00537dd2396a.png) | ![image](https://user-images.githubusercontent.com/5147346/88445705-6a742e00-cdf2-11ea-910f-79388055056b.png) |

## Search Engine Optimization

Using seobility SEO checker, the lab site scored a 45%. Ways to improving this score are to add more meta tags and content describing the website. Although the website is crawlable, there are very few links allowing the search engines to travel to additional pages to learn more about the site.
Another way of increase SOE ranking on Google, is to register the site in Google Search Console. This way is to directly provided infomation about the site without a web crawler finding. It is also helpful to change infomation when the website is updated but a crawler hasn't visted yet.
