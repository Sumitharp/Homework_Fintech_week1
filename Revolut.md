# REVOLUT  

## Overview and Origin

Revolut was founded on 1 July 2015 by Nikolay Storonsky and Vlad Yatsenko. The company was originally based in Level39, a financial technology incubator in Canary Wharf, London. Revolut was initially launched in the UK and offered prepaid cards, multi currency exchange, international transfer to freelancers and Small and Medium Enterprises. It obtained European Bank license in 2018. In addition, Revolut is authorized in the UK by the Financial Conduct Authority (FCA) under the Electronic Money Regulations 2011.
 
Nilkolay Storonsky, who had master's in physics and economics, was a trader at Credit Suisse and Lehman Brothers prior to starting Revolut with Vlad Yatsenko, former Credit Suisse and Deutsche Bank developer. Storonsky realised that he was wasting hundreds of pounds on forex fees and commissions when he was travelling. When he found out that multi-currency card were not possible at that time, he decided to come up with a solution.    

In 2016, the Revolut app registered 100,000 users and secured its first Series A funding of $8.4 million. They also raised Series B, C and D funding of c. $906 million. Totally the company has raised $916.5 million as of Feb 16 2021 by way of private equity.  The largest funding was in Feb 2020 of $580 million in Series D led by investment firm TCV , an early investor in Facebook and Netflix, which **valued Revolut at $5.5 billion** (increased 3x from $1.7 billion in April 2018).

## Business Activities:

Revolut initially gained popularity by issuing *prepaid cards* and allowing users to spend money in different currencies at inter-bank exchange rates without paying high forex fees. These transactions are supported in 30+ countries and are executed in real-time between Europe, the US, Singapore, Japan, Australia.The AHA moment customers got from instant transfer with lesser clicks hooked them to use other products. 

Revolut has now evolved into new mobile app-based challenger bank which offers traditional banking services without costly overheads of physical branches. A customer can open an account within couple of minutes by downloading the app and providing personal information and confirming identity compared to visit-and-wait in traditonal banks. Revolut issues a physical card as well as a mobile app generated card for immediate use. The app generated cards are suitable for one-time, online transactions which automatically regenerate after each transaction. Its own 'Sherlock Flask' app process transactions under 50ms to check for fraud while the merchant termial displays "Processing Payment" (Latency of 50 milliseconds or less is considered very good).Since its implementation, Sherlock caught 96% of fradulent transactions and just 1c out of $100 was lost due to fraud.

Revolut's personal banking services include Early Salary, Pay and get paid, International transfers, Group Bills, Budget & Analytics, Cards, Junior Accounts, Crypto, Vaults, and Saving Vaults. Additionally, its business customers enjoy features like spending control with cards, and automating expense bookkeeping by using business APIs & Partner apps. Ease of use in the app enables Revolut to cross-sell new products like investment, crypto vault, analytics.

Revolut also launched a commission-free stocking trading app like Robinhood last year. 

## Technology:

Nikolay Storonsky, CEO and Founder said about their vision:
>“The reality is what we’re trying to achieve is [to] build a 10x better financial services company that is 10x >cheaper as well. The only way to do it is not building only one product, but building a platform with many products >on top of it.” 

Hence, Revolut has built its own end-to-end banking platform (core features). This makes Revolut agile, since they understand their product stack they can introduce new features quickly without third-party dependencies. 

Revolut built its core infrastructure with Google Cloud Platform's (GCP) Compute Engine virtual machines. They have setup highly secure and separate instances for its main infrastructure and applications.  The company has also made extensive use of Cloud APIs in conjunction with a third-party automation tool to achieve fully automated infrastructure provisioning and management of the platform (Google Case Study)

Their projects include building the mobile APIs, developing microservices to evolve the architecture, and perfecting a number of systems that the business depends on – risk management, fraud detection, or payment processing, to name a few. Revolut's technology is based predominantly on Java 8 on the backend and AngularJS on the frontend. Revolut takes advantage of Kotlin programming language to build a multiplatform architecture for iOS and Android. They are also planning to introduce Scala for new components. However, the company continues to use JavaScript, HTML, Python, TypeScript, Groovy, C++ and Clojure within their different areas of work.   As for data storage they use SQLite with Room OM.  For the front-end, by using the RecyclerView-based screen layout they establish and maintain UI elements which is developer friendly and easily extenssible.  They offer a minimalist approach in order to use external frameworks, with emphasis on maintainability and fast turnaround with TDD (Test Driven Development), DDD (Domain-driven Development), and Continuous Integration (CI) & Delivery.


## Landscape:

According to Research and Markets report on Neo and Challenger Banks 2020-27, this industry was valued at $20.4 billion in 2019, and the market size is projected to reach $471 billion by 2027, growing at a CAGR of 48.1% from 2020 to 2027. These bank are digital-only banks without any physical branches and operate on a partnered bank license in the market. These banks are continuously challenging existing traditional banks, by innovating & integrating several technologies in their product offerings and providing real-time services and client-centric products & services. Additionally, higher interest rates on deposits/savings compared to traditional banks, regulatory support, mobile based applications and expansion in emerging/unbanked economies are main drivers of this market.

Revolut can only be used through mobile app and is not available on computers as a website for individuals. So its market is anyone who uses mobile phone which in the EU is 469 million and in the US is 275.6 million at the end of 2020. Revolut presently has 500,000 business customers and **12+ million personal customers.** It predominantly services European Ecomonic Area countries, Switzerland, Australia and recently launched services in USA.There is significant growth potential even if 10% or 75 million users adopt Revolut.
 
Some of competitors in this Fintech space are NuBank (Brazil), Atom Bank Plc (UK), Fidor Solutions AG (EU), Monzo Bank Limited (UK), Movencorp, Inc. (USA), MYbank (EU), Number26 GmbH(Germany), Simple Finance Technology Corporation (taken over by BBVA), Tandem Bank (UK),UBank limited (Australia), WeBank (China). There are also single product or service companies which provide online disagreggrated services like Venmo/Paypal for payments, Mission Lane/Ollo for credit cards, Avant/Rocket loans for consumer loans, Affirm/Klarna for point-of-sale financing, Marcus by Goldman Sachs/Chime for deposits and debit cards. In the future, we will likely see that these single product companies start providing more services to their customers on the lines of traditional banks. There could also be mergers amongst the challenger banks and with traditional banks which want to provide services to their modern consumers.   

## Results:

Revolut’s losses trebled in 2019 to £104.7 million, following a year of rapid growth mainly due to increase in staff by 1,628 , as well as launch in the US and Singapore. In 2019, revenue increased 3x to £162.7 million from £58.2 million. Gross margin improved to 39% in final quarter of 2019 up from 17% at the beginning of the year. Most of its revenue is generated from cut in the interchange fee paid to Mastercard, membership fees of its cards, and business accounts.

Key performance indicators:
* Revenue growth: Increase of 180% on 2018
* Total retail investors: 10 million (3.5 million in 2018) increased to 12 million at the end of 2020.
* Daily active people: 231% increase yoy
* Total paid users:260% increase since last reporting date in 2018
* Weekly active business: 321% increase since last reporting


## Compared to Competition:

Revolut has performed better as compared to its European Economic Area (EEA) rivals. Revolut's revenue is 2019 was ~£160 million compared to Monzo's £67 million and Starling £30 million. At the end of  2019, Revolut had 10 million customers far greater than 2.5 million of Monzo and 1 million of Starling. Further, Revolut's average contribution per customer was £24 compared to £21 (Monzo) and £20 (Starling). Revolut's total transaction volume was £65 billion in 2019 almost 5x more than Monzo. However, Revolut's customer base is half that of NuBank (Brazil) which is seen as a revolutionary bank in Latin America, especially in countries like Brazil where the interest rate is very high and traditional banks charge high fees on every transaction. Additionally, Revolut's competitor Chime in North America has a large customer base in US (8 million in 2020) with upward of $200 million in revenues and 150,000 direct deposit users a month which the neo banks from EEA donot enjoy as they are still not primary accounts for most customers. There is also Sofi bank (USA) (2x Revolut's revenue) which generates most of its revenue from student loans and repayments.


## Recommendations:

Revolut can expand its horizons by servicing new geographies like Asia which are underbanked and have high mobile penetration.  

Center for Resposible Lending in its Overdarft Fees 2020 report states that traditional banks charged $11 billion in overdraft fees in 2019. Revolut can provide overdraft facilites at little or no charge on debit card purchases like Chime currently does (upto $100) which will make it more appealing to many customers.  Further, Revolut can also enter the student loan market like Sofi. These students would later continue banking with Revolut and use more services as they join the workforce.

Revolut has already launched crypto currency exchanges in Bitcoin, Bitcoin Cash, Ethereum, and Litcoin with more digital currencies expected soon. Unlike most crypto exchanges, when you sell crypto on Revolut, funds are immediately available to spend or transfer. This could be one of the major segments given the skyrocketing interest.

Being in the banking and financial sector, Revolut has to continuously bolster its fraud detection systems, risk management and compliance of regulatory framework. It is the key to its survival in this sector and any lapse could severely impact its operations.  

My recommendation for Revolut would be to continue generating customer AHA moment with technological advances and expand into new geographies, while complying with the regulatory framework.


Sources:
* https://www.revolut.com/en-US
* https://monzo.com/
* https://www.starlingbank.com/
* https://www.chime.com/
* https://en.wikipedia.org/wiki/Revolut
* https://www.lightico.com/blog/the-neobanks-are-coming-is-your-traditional-bank-ready/
* https://medium.com/revolut/under-the-hood-engineering-at-revolut-2dc183c04228
* https://www.researchandmarkets.$200 mi/reports/5118772/neo-and-challenger-bank-market-by-service-type?utm_source=BW&utm_medium=PressRelease&utm_code=vr6vnm&utm_campaign=1415707+-+Neo+and+Challenger+Bank+Market+to+Exhibit+a+CAGR+of+48.1%25+During+2020-2027&utm_exec=joca220prd
* https://www.businessofapps.com/data/revolut-statistics/
* https://craft.co/revolut/funding-rounds
* https://craft.co/nubank/competitors?competitors=nubank%2Catom-bank%2Cmonzo%2Cn26%2Cmonese%2Crevolut
* https://stackshare.io/companies/revolut
* https://wiredelta.com/how-was-revolut-developed/#:~:text=Revolut%20in%20technology&text=Their%20technology%20is%20based%20predominantly,introduce%20Scala%20for%20new%20components.
* https://soundcloud.com/wft/dan-westgarth-north-america-general-manager-for-revolut
* https://medium.com/revolut/building-a-state-of-the-art-card-fraud-detection-system-in-9-months-96463d7f652d
* https://youtu.be/Vku-FDTZYAo
* https://www.statista.com/
