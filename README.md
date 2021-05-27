![GRC in a nutshell](https://www.softexpert.com/wp-content/uploads/2016/09/xframework-grc-2.png.pagespeed.ic.7RthXjt7xe.png)

# :tada: Grand Repository Challenge accepted!

This is a list of resources (most are free, some are cheap, a handful are expensive) for security GRC folks.

Each of you probably has a different title. Cyber Risk Managers, Security Compliance Program Managers, Business Information Security Officers, Security Risk & Compliance Senior Analysts, Third-Party Risk Management Governance Leads, GRC something, etc.

This variety is naming isn't that great because it's *easier* for software developers to come together as a community to organize knowledge and share information. A major foundation of knowledge is useful and relevant to most SWE.

Our field is only a couple of decades old and has exponentially developed in the past five years.

Some of us work for SaaS companies (me! :bowtie:), the financial sector, healthcare, government, retail and a dozen other industries. Scope, budget, stakeholders and degrees of resentment can vary but there's a solid foundation common to most of us (let's say about 80%).

So I thought, why not build a similar knowledge management platform... I know it's a GitHub repo but that makes my endeavour sound a lot more serious and technical than it actually is. I just thought content curation lists were amazing and that we should have one!

This is GitHub which means, Pull Requests are more than welcome! Nothing here is gospel, definitions are often subject to debates and heated discussions on LinkedIn and everyone has a different opinion on G, R and C (hatred for C is probably consensual IMHO).

Feel free to share your resources, correct my faulty Frenglish or add cooler emojis.

> *This contains an awful lot of expert puns and boomer jokes* 

## :notebook_with_decorative_cover: Contents

- [:tada: Grand Repository Challenge accepted!](#tada-grand-repository-challenge-accepted)
  - [:notebook_with_decorative_cover: Contents](#notebook_with_decorative_cover-contents)
- [:mortar_board: What is Security GRC?](#mortar_board-what-is-security-grc)
  - [:guardsman: Governance](#guardsman-governance)
  - [:chart_with_upwards_trend: Risk Management](#chart_with_upwards_trend-risk-management)
  - [:gun: Audit & Compliance](#gun-audit--compliance)
  - [:octopus: Compliance Models](#Compliance-models)
- [:books: Books](#books-books)
- [:tv: Talks/Videos](#tv-talksvideos)
- [:telephone_receiver: People you should know](#telephone_receiver-people-you-should-know)
  - [:sunglasses: Thought Leaders](#sunglasses-thought-leaders)
  - [:iphone: Follow them on LinkedIn](#iphone-follow-them-on-linkedin)
- [:octocat: Repositories](#octocat-repositories)
- [:microphone: Podcasts](#microphone-podcasts)
- [:scroll: Certifications](#scroll-certifications)
- [:triangular_ruler: The Knowledge Trifecta](#triangular_ruler-the-knowledge-trifecta)
  - [:floppy_disk: The Technical](#floppy_disk-the-technical)
  - [:lock_with_ink_pen: The Security](#lock_with_ink_pen-the-security)
  - [:briefcase: The Business](#briefcase-the-business)

# :mortar_board: What is Security GRC?

The security GRC field is covering lots of ground and include a varied number of tasks and responsibilities. Some of them will sound exciting, some will reignite very painful memories. 

## :guardsman: Governance

Governance, as the name implies, focuses on how security is managed and its oversight. This could include building the security strategy, managing the security programme and ensuring continous monitoring of workstreams.

This would also be the area responsible for orchestration and metrics for your security programme. In other words, the always useful dashboard with 15 graphs and thousands of data points would be include in the governance efforts.

## :chart_with_upwards_trend: Risk Management

How do I know what's the priority for my security programme? Lockdown end-user access or focus on patching? (probably both lol) The only way to make rational decisions regarding what to do is to perform risk assessments.

Risk is traditionally explained as a factor of a threat and a vulnerability. Pretty simplistic (probably false as well) but it gets the job done:
* A threat is a potential harmful event that could impact your organisation
* A vulnerability is a known weakness that could be exploited
* A risk is threat * vulnerability... A risk is the impact if the threat exploits the vulnerability (R = T*V)

A robust risk management program would also include some quantitative features to make sure senior management and business executives understands the financial costs associated with some of the identified risks. Nothing has to be too precise or too detailed, having numbers in the right ballpark and being able to evidence why you chose them is well more than enough.

## :gun: Audit & Compliance

Once you know what your direction is and you know what to focus on, how do you know you're on track? There's two ways:
* Auditing allows you to know if the controls you chose and your security programme is working effectively
* Compliance is how close are you to the baseline either set by yourself or by a 3rd party body (ISO, AICPA, insert acronyms)

Often hated (often for good reasons), audit and compliance folks have to be annoying by nature. They assess how things you said you'd do are actually done in the real world. More often than not, things are either not done as they should or not done at all. Probably because no one has read the policies you took six months to write!

## :octopus: Complaince Models

Well...  There are a lot.  Your orginizaation likely is using some of these, but certainly not all.  Executive leadership drives policy at a high level based on business objectives.  Certain compliance is compuslary:  Sarbanes-Oxley Act (SOX) for US publically traded companies; General Data Protection Regulation (GDPR) applies to any organisation operating within the EU, as well as any organisations outside of the EU which offer goods or services to customers or businesses in the EU.

Sarbanes-Oxley Act - SOX - https://www.congress.gov/bill/107th-congress/house-bill/3763   
General Data Protection Regulation - GDPR - https://gdpr-info.eu/  
Federal Information Security Modernization Act - FISMA - https://www.cisa.gov/federal-information-security-modernization-act  
Payment Card Industry Data Security Standard - PCI-DSS - https://www.congress.gov/bill/107th-congress/house-bill/3763  
Health Insurance Portability and Accountability Act - HIPAA - https://www.hhs.gov/hipaa/index.html  
Security and Privacy Controls for Information Systems and Organizations - NIST SP 800-53 - https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final  

# :books: Books

* [**Measuring and Managing Information Risk**, *Jack Freund & Jack Jones*, 2014](https://learning.oreilly.com/library/view/measuring-and-managing/9780124202313/)
  * The FAIR book itself. Self explanatory, if you want to know more about risk quantification this is a must-read, the story in the intro is meme material.

* [**How to Measure Anything in Cybersecurity Risk**, *Douglas Hubbard & Richard Seiersen*, 2016](https://learning.oreilly.com/library/view/how-to-measure/9781119085294/)
  * Amazing primer on Cyber Risk Quantification as a whole. Keep these things in mind:
    * Your problem is not **as unique** as you think
    * You **have *more* data** than you think
    * You **need *less* data** than you think

* [**The Cybersecurity Manager's Guide**, *Todd Barnum*, 2021](https://learning.oreilly.com/library/view/the-cybersecurity-managers/9781492076209/)
  * Probably the best information security book you'll ever read, Todd has been the CISO of GoPro for 6 years and worked in a variety of industries in the last three decades
  * What defines our field:
    * Nobody Really Cares
    * Nobody Understands
    * Fear Drives Our Industry
  * The Four Cornerstones of your Security Program:
    * Documentation
    * Governance
    * Security Architecture
    * Communication, Education and Awareness

# :tv: Talks/Videos

* A [great foundational talk](https://www.youtube.com/watch?v=dt2IqidgpS4) to understand how every framework are working into one another:
  * :green_book: **Control Frameworks** such as *NIST 800-53* or *CIS 20 Controls* for building your security baseline
  * :orange_book: **Program Frameworks** such as *ISO 27001* or *NIST CSF* to standardize an overarching security program
  * :blue_book: **Risk Frameworks** such as *NIST 800-37* or *FAIR* to identify, measure and quantify risk

* I have a full playlist of over [80 videos focus on Risk Management and Cyber Risk Quantification,](https://www.youtube.com/playlist?list=PLj4UOrWWdhG-Lqk9DOvShUdbwRZcGWhRH) will update it soon but it already has a lot.
  * This quick live [Quantitative Cyber Risk Analysis](https://www.youtube.com/watch?v=fHUv8TJC6kM&list=PLj4UOrWWdhG-Lqk9DOvShUdbwRZcGWhRH&index=5) from *Evan Wheeler* is a great overview of how straightforward a quantitative analysis can be
  * *Steve Reznik* has numerous talks on how FAIR can help build meaningful KRIs but [this one](https://www.youtube.com/watch?v=w4x1tWTiCHg&list=PLj4UOrWWdhG-Lqk9DOvShUdbwRZcGWhRH&index=16) is a starting suggestion

# :telephone_receiver: People you should know

## :sunglasses: Thought Leaders

* :dvd: Everything written by [***Ryan McGeehan***](https://scrty.io/).
  * His website references over a dozen articles on Risk Management. Some of them are [*waaaay*](https://magoo.medium.com/hypothesis-risk-and-science-439fc8b05ffb) over my head
  * His various experience at Coinbase and Facebook and as a Start-up security advisor makes his input super relevant if you're working at SaaS company as an example

* :bank: Everything written by [***Phil Venables***](https://www.philvenables.com/home).
  * His take on most subjects are worth the read, he has a great analysis of the [*Compliance vs. Security*](https://www.philvenables.com/post/compliance-vs-security) debate
  * Phil has over 20 years of experience in security leadership at Goldman Sachs and now the CISO of Google Cloud

## :iphone: Follow them on LinkedIn

# :octocat: Repositories
  
HIPAA Compliance Policies https://github.com/catalyzeio/policies/  
Comply - SOC2-focused compliance automation tool https://github.com/strongdm/comply  
GovReady-Q Compliance Server - GRC platform for highly automated compliance assessments and documentation. https://github.com/GovReady/govready-q  
  
# :microphone: Podcasts

SECURITY NOW - Hosted by Steve Gibson, Leo Laporte https://twit.tv/shows/security-now

# :scroll: Certifications

Consider that these are not listed in a particular "order of importance."  You should allign your current skills and long term goals when determining a path to certification.  
  
CRISC - ISACA - Certified in Risk and Information Systems Control (https://www.isaca.org/credentialing/crisc)  
  
GRCP - OCEG - GRC Professional Certification (https://www.oceg.org/certifications/grc-professional-certification/)  
  
CRMA - theiia - Certification in Risk Management Assurance (https://na.theiia.org/certification/crma-certification/pages/crma-certification.aspx)  
  
PMI-RMP - PMI - PMI Risk Management Professional (https://www.pmi.org/certifications/risk-management-rmp)  
  
CISM - ISACA - Certified Information Security Manager (https://www.isaca.org/credentialing/cism)  
  
CISSP - isc2 - Certified Information Systems Security Professional (https://www.isc2.org/Certifications/CISSP)  
  
# :triangular_ruler: The Knowledge Trifecta

**We are offered jobs but we have a career.** We're the only one accountable for our career path and the best way to make the best of this is to continuously learn.

This section might seem out of place for a content curation repository but I'm passionnate about this, sorry.

Security is a very young field and ours in even younger. Career pathways are still developing and no one *actually* know the sureway to a GRC leadership role or a CISO position.

The only thing that's certain is that this is the best thing that could happen to us. We can build our own paths. The only way we do this is through learning. Our field is about understanding, managing and translating. We understand the technical, manage security projects and translate into security terms business requirements.

If you're a jack-of-all-trades, love learning new things, being inquisitive but always having the business goals in mind, then it's the field for you. If you're not, it's probably the field for you anyway or you wouldn't be here!

## :floppy_disk: The Technical

Understanding the technical landscape.

A Modern GRC Implementation Roadmap is Powered by Technology
1. Start With Your GRC Framework
2. Choose Your Technology
3. Plan for the Adoption of Tech-Driven Solutions
4. Day-to-Day Monitoring of Your GRC Strategy


## :lock_with_ink_pen: The Security

Understanding the security measures

## :briefcase: The Business

Understanding the business language

What drives strong GRC programs?  
*A Clearly defined business case and plan for implementing and supporting a GRC program  
*Written policies, procedures and standards of conduct  
*Assigned Compliance Officer, Compliance Committee and high level oversight  
*Effective training and education  
*Effective lines of communication, especially for internal reporting  
*Effective systems for routine monitoring, auditing and identification of compliance risks  
*Procedures and system for prompt response to compliance issues  
  
