
# assignment2

## Part 1: Problem Discovery and Validation Problem Statement 
Many people shop online but face difficulty comparing the prices of the same product across different websites. They often have to open many shopping apps or websites to check prices, discounts, delivery charges, and product availability. This process takes time and sometimes people end up paying more than necessary. 
Research and Validation 
Method 1: Competitor Research 
I looked at popular price comparison websites and shopping platforms. Most of them either compare only a few stores or show outdated prices. Some websites also have too many advertisements, making it difficult for users to find the best deal. 
https://www.google.com
https://camelcamelcamel.com

Method 2: Community Research 
People on online shopping forums and social media often ask questions like: 
* “Where can I get this product at the lowest price?” 
* “Which website has the best discount today?” 
* “I wish there was one app that compared prices automatically.”These discussions show that many online shoppers face the same problem.
 https://www.reddit.com
 https://www.reddit.com
 Painkiller or Vitamin?This product is a Painkiller because it solves a real problem. It saves users both time and money by helping them quickly find the best price without visiting multiple websites. 

 ## Part 2: Product Definition and Tier Classification
 Criteria	Standard Tier
Product:  	Web-based Price Comparison Platform
Tier:	    Standard
Estimated Build Time:	3–6 months
Development Team:	3–6 developers (Frontend, Backend, UI/UX, QA)
Pricing Model:	Free platform with affiliate commissions from partner stores, optional Premium subscription for advanced features (price alerts, wishlist tracking, ad-free experience), and advertising revenue
Realistic Revenue Gate:	USD 5,000–20,000 per month from affiliate commissions, premium subscriptions, and advertisements
Justification:	This product fits the Standard Tier because it can be developed within a few months by a small team. It requires integration with multiple online shopping websites, product search, price comparison, discount tracking, and regular price updates. It has a sustainable revenue model through affiliate marketing and premium features and can be expanded with AI recommendations, personalized shopping, and support for more online stores as the user base grows.


## Part 3: Tech Stack Justification
Component |	Technology Chosen |	Justification
Frontend  | React.js | React enables fast development using reusable components and has a large ecosystem, making it suitable for a solo developer or small team. It also scales well as the application grows.
Backend	| Node.js with Express.js | Node.js is lightweight, easy to learn, and allows the same language (JavaScript) to be used for both frontend and backend, reducing development time and maintenance effort.
Database | PostgreSQL | PostgreSQL is open-source, reliable, and free for small projects. It can easily handle thousands of products and users while supporting future growth.
Authentication | Firebase Authentication | Firebase Authentication provides secure login with email and Google accounts without building a custom authentication system, reducing development time and security risks.
Hosting | Vercel (Frontend) + Render (Backend) | Both services offer generous free tiers that are sufficient for launching an MVP and can be upgraded easily as traffic increases.
Payments | Stripe |Stripe provides secure payment processing and subscription management, eliminating the need to build and maintain a custom billing system.

Justification Against the Required Criteria
1. Time to Market
The selected technologies allow a single developer or a small team to build and launch the platform within the 3–6 month Standard Tier timeframe. React, Node.js, and Firebase provide ready-made tools that reduce development time.
2. Team Size and Skill Fit
The entire application uses JavaScript for both the frontend and backend, reducing the learning curve and making it easier for one developer or a small team to maintain the project.
3. Cost at Low Scale
For 0–1,000 users, the expected costs are very low:
* Vercel: Free tier for frontend hosting.
* Render: Free or low-cost backend hosting.
* PostgreSQL: Free database plans are available.
* Firebase Authentication: Free for small numbers of users.
* Stripe: No monthly fee; transaction fees apply only when payments are processed.
This keeps startup costs minimal while validating the product idea.
4. Ecosystem Maturity
All selected technologies have mature ecosystems with extensive documentation and community support. Libraries are readily available for authentication, API integration, UI development, and payment processing, allowing faster development and easier troubleshooting.
5. Scalability Ceiling
If the platform gains significant traction, the chosen technologies can scale without requiring a complete rebuild. Hosting plans can be upgraded, PostgreSQL can handle much larger datasets, and React and Node.js are commonly used in production systems serving millions of users.

Technologies Not Used
* No custom billing system: Stripe will handle all payment processing and subscriptions because it is more secure, reliable, and faster to integrate.
* No custom authentication system: Firebase Authentication will manage user login instead of building authentication from scratch, reducing security risks and development effort.
* No self-managed servers: Cloud hosting services (Vercel and Render) will be used to minimize infrastructure management and operational costs.
This approach follows the class principle that the real competitive advantage is building and growing the user base (distribution), not spending time creating custom infrastructure that already has reliable third-party solutions.

## Part 4: Mobile App vs Web App Decision

Decision Factor	Analysis	Reason
1. Distribution Channel: Web users can access the platform directly through a URL, search engines (SEO), or social media without downloading an app. This makes it easier to attract new users through Google searches for product prices and deals.
2. Hardware and OS Access Needs: The platform does not require device-specific features such as the camera, GPS, push notifications, or offline functionality. Users only need an internet connection and a web browser to compare prices.
3. Usage Pattern: Price comparison is usually an occasional activity performed before making a purchase. Many users shop from laptops or desktop computers, making a web application more suitable than a mobile-first solution.
4. Iteration Speed: A web application allows instant updates and bug fixes without waiting for app store approval. This enables faster feature releases and continuous improvements based on user feedback.
5. Monetization: Web payments for premium features can be processed directly through Stripe, avoiding the 15–30% commission charged by mobile app stores. Affiliate commissions can also be tracked more easily through the web platform.
Final Decision and Justification
The product will be developed as a web application because it offers the fastest time to market, lower development and maintenance costs, and easier distribution through search engines and direct links. Since users typically compare prices only when they are shopping, a web platform better matches their usage pattern than a mobile app. Additionally, using Stripe for premium subscriptions avoids app store fees and provides greater flexibility for monetization. If the platform gains significant traction, a mobile application can be developed later to complement the web version, but launching on the web is the most practical and cost-effective choice for the MVP.

## Part 5: SDLC Approach

SDLC Model: Agile
For this project, I would use the Agile SDLC model because it allows the product to be built step by step while improving it based on user feedback. Since this is a new idea, it's important to test it early instead of spending months building features that users may not need.

Mapping Agile to the Three-Phase Blueprint
1. Discover and Validate
The first step is to create a one-page discovery memo that explains the problem, identifies the target users, and summarizes the research from competitors and online communities. This helps confirm that the idea solves a real problem before development starts.
2. Build and Ship
Next, I would build an MVP with the main feature of comparing product prices from different online stores. AI tools can be used to speed up coding, fix bugs, and help with UI design, making development faster and more efficient.
3. Launch and Report
Before releasing the product publicly, I would conduct a bug bash to find and fix issues. The MVP would then be launched to a small group of users to collect feedback through interviews and surveys. Based on this feedback, improvements can be made before a wider release.
Why Not Waterfall?
I don't think Waterfall is a good choice for this project because it requires everything to be planned before development begins. For a new product like this, user feedback is essential and the idea may change along the way. Agile gives the flexibility to make improvements after each stage, which makes it a much better fit.

## Part 6: Distribution and Go-to-Market Plan 

Target Users 
* Students 
* Working professionals 
* Online shoppers 
* Families looking for the best deals 
Marketing Strategy 
* Share helpful shopping tips on social media. 
* Collaborate with technology and shopping influencers. 
* Post in shopping communities and discussion groups. 
* Use SEO so people searching for product prices can easily find the website. 
* Offer affiliate discounts and referral rewards. 
## Part 7: Success Criteria
The project will be considered successful if: 
* The website is fully functional. 
* Users can compare prices from multiple stores. 
* At least 100 users test the platform. 
* Positive user feedback is collected. 
* Search results are accurate and updated regularly. 
* Users save both time and money while shopping. 
## Part 8: Timeline 
Week 1-Research the problem, study competitors, and collect user feedback. 
Week 2-Design the website layout and database. 
Week 3-Develop product search and price comparison features. 
Week 4-Add user login, improve the interface, and fix bugs. 
Week 5-Test the website with users, collect feedback, and make final improvements. 
Week 6-Launch the product and promote it on social media and online communities. 
Reflection 
While researching this idea, I found that many online shoppers experience the same problem of checking prices across different stores. Existing solutions are often incomplete or difficult to use. This project can save users time, reduce unnecessary spending, and make online shopping more convenient. 
Competitor Links 
1. Google Shopping https://shopping.google.com 
2. PriceRunner https://www.pricerunner.com 
3. PriceGrabber https://www.pricegrabber.com 
4. ShopMania https://www.shopmania.com 
Community Links 
1. Reddit – Online Shopping https://www.reddit.com/r/OnlineShopping/ 
2. Reddit – Frugal https://www.reddit.com/r/Frugal/ 
3. Reddit – Buy It For Life https://www.reddit.com/r/BuyItForLife/
4. Quora – Price Comparison Discussions https://www.quora.com/search?q=price%20comparison%20shopping 