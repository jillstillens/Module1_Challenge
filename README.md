# Module1_Challenge

RegTech - An analysis of SAI360

Overview

Financial regulation is a fascinating subject.  People shudder at the word "regulation", yet it is required to help provide stability for financial institutions and protections for the public who use them.   Anti-money laundering provisions, know-your-customer regulations, and capital requirements are several examples of well-known regulations in the current banking system.  Regulation is, in general, a lagging process.  That is, we must understand how a system is going to be used before it can be regulated.   I am reminded of the story where a college campus was completely re-landscaped over a summer break, except for any paths.  The landscapers deliberately did not build any specific paths around the new campus.  Instead, when the students returned in the Fall, they made their own paths.  After a few months the landscapers came in and paved the paths which the students made.  The landscapers had wanted to see how the space was going to be used before putting in those finishing touches.  Regulations are similar - we need to see how something is going to be used, before we can start building the infrastructure around it.

RegTech is the use of automated technology to help enforce governance, reporting, and compliance.  Regtech can be used, for example, to provide real-time monitoring of digital payments, to look for outlier transactions and flag them as potential money laundering. In this way, RegTech can be used to help enforce existing regulations, in addition to solving regulatory issues as new rules arise.   RegTech uses current technologies, such as AI, blockchain, and cloud technology, to parse through vast amounts of data for both financial institutions and regulatory agencies.  In addition, RegTech can be used to keep up with global regulatory changes, parsing through data provided by regulatory bodies to anticipate upcoming changes and translate those into comprehensible requirements.

Because of the fluidity of both the technology and regulations themselves, there are a significant number of global businesses, with heavy activity in both start-ups and consolidation.  For this case study I chose SAI360 from the Risk Management RegTech sector because they have been around for quite awhile and have an interesting background.

Business Activities 

SAI360 started back in 1922.  It was based in Australia at that time, and began with a focus on Environment, Health, and Safety (EHS) concerns for the construction of the Sydney Harbor Bridge.  In 2002 SAI360 took a more global approach, expanding its EHS model over more than 30 countries.  In 2010, the company began focusing on ethics and compliance solutions, which turned the company towards the domain of Environment, Social, and Governance (ESG).  In 2012 they implemented their first regulatory and compliance system, to support US Healthcare rules.  In 2016 they bought Modulo, uniting risk and compliance with digital capabilities to manage cybersecurity, data privacy, and GDPR regulations.  In 2017 they relocated from Australia to Chicago IL.  In 2019 they acquired Bwise (a regulatory compliance platform) from NASDAQ, allowing them to soon branch deeper into the financial sector by adding internal audit and regulatory compliance systems, to support risk management.  In 2021 they re-branded from SAI Global to SAI360, and they are now a heavy player in the Governance, Risk, and Compliance (GRC) space.  In March 2023, SAI360 was purchased by Symphony Technology Group (STG), a private equity group.

It is interesting to  note that the evolution of SAI360 began as addressing regulations in construction, then regulations in healthcare, then branching out into financial and other industries.  In other words, they started with a focus on regulations, then expanded and purchased their way into providing digital solutions for regulatory issues across multiple domains, as opposed to starting as a technology company and then trying to address regulatory controls.  This worked well for them because being able to understand and address regulatory issues had already been their business for many years, and putting the technology around it was secondary.  Regulations are particularly challenging because they vary by country and even by state, and they can be very dynamic.  A crisis occurs, quickly followed by changes to regulations, giving companies limited time to get all pieces implemented.  This is where third-party solutions can be so helpful, since it's their business to stay on top of regulatory changes, as opposed to a company trying to build and maintain an in-house solution.

Landscape and Results

Part of SAI360s financial offerings is based on COSO (Committee for Sponsoring organizations) Framework.  This Framework provides: Controls to make sure industry standard practices are being followed, Risk Management to identify and control enterprise risk, Control Activities to address internal controls to help a business ahieve its objectives, Information and Communication tracking to ensure legal compliance, and Monitoring to ensure employees follow internal and external controls.

All of this requires being able to parse through vast amounts of data.  The Risk Management category alone includes KYC, AML, activity by cyber criminals, and even criminal activities by internal employees.  SAI360 allows users to use natural language questions to parse through and present data needed for auditing and business decisions.  

In terms of technology, SAI360 is cloud-based, with SaaS based offerings, and runs on the Bwise platform.  They work on converting standard operating procedures into automated routines, with data coming from a single source of record.  They use Microsoft and Linus servers, with Python, Terraform and Powershell.  Data is stored and accessed under SQL Server, PostgresSQL, and Mongo.  Containerization is done by Docker and Kubernetes, with code under GitHub, Jenkins, and CircleCI.  

A major competitor in this realm include Suade (https://suade.org/solutions/) .  Suade seems a bit farther along with its offerings, referring to "Regulation as a Service" and "Risk as a Service", but overall the offering is very similar - parse through large amounts of regulatory data to condense into actionable activities to meet regulatory requirements.  Much of the focus is on tracking, translating, and reporting on upcoming regulatory changes, to try to stay ahead of those changes.   For both companies, functionality is broken down into smaller pieces which can be put together and customized by the customer as needed.

Recommendations

Although SAI360 seems to do a comprehensive job with tracking regulatory changes and their impacts, I could not find a solid use case where they were using AI to prevent violations.  I suspect they may do so, but if so it is a proprietary proccess which they are keeping under wraps.  In my research I also came across SymphonyAI (www.symphonyai.com) and almost used them for my case study, because they explicitly use AI to look for financial crimes - they parse through large amounts of data to look for outlier transactions, which could indicate violations, and report them for follow up.  Ultimately I decided to use SAI360 as my case study, but as I was doing this Recommendation section and was going to suggest a company like SymphonyAI would be a good fit for SAI360, I realized they are actually already related.  SAI360 is now owned by STG, and the founder of SymphonyAI, Dr. Romesh Wadhawani, is the founder of STG.  SymphonyAI is not a holding of STG as is SAI360, but they are clearly related (SAI == SymphonyAI, see?  Alas, I did not, until this section).  

I find this a bit ironic because I had originally chosen SAI360 due to its size (> 200 employees) and longevity.  When I had been looking at smaller companies, I kept running into challenges with the company having been bought by someone else.  This cycle is normal for an emerging technology - many startsups, some failures, much consolidation.  But it made it challenging as I was trying to find a smaller, less well known company on which to report.

SymphonyAI uses AI for transaction monitoring, Customer Due Diligence (including KYC), Payment Fraud, and more.  It does data mining using real-time data to look for payment issues; it has self service detection to auto adjust and correct; and it provides model transparency.  All of this would blend nicely with SAI360.  SAI360 can report on upcoming regulatory and reporting needs both internal and external, and SymphonyAI could be used to implement those needs.  It will be interesting to see how these companies come together in the future.


Sources:
https://en.wikipedia.org/wiki/Banking_regulation_and_supervision
https://www.investopedia.com/terms/r/regtech.asp
https://www.weforum.org/agenda/2022/06/what-is-regtech-and-what-does-it-mean-for-policymakers/
https://www2.deloitte.com/lu/en/pages/technology/articles/regtech-companies-compliance.html
https://www.sai360.com/industries/financial-services
https://www.sai360.com
https://www.techtarget.com/searchcio/definition/COSO-Framework
https://www.symphonyai.com/financial-services/



