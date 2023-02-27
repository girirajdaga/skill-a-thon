# skill-a-thon

This document repo created for Team Trusting India from Affinidi for the Skill-a-thon


## Product document	

### What is the Problem statement (Unmet need)? 

The digital landscape is flooded with apps and platforms that cater to specific domains, often forcing users to repeatedly log in and out of various systems. Unfortunately, this approach prioritizes the outcomes of the platforms or marketplaces, rather than the needs of the customer. 

The service providers spend time and effort in establishing trust by performing background verifications out of band leading to wastage of human resources.  

As-is solutions are based on platforms that require both citizen and the service provider to be on the same platform to access the opportunities which restricts the accessibility in a diverse country like India. 


### Solution description 

Our solution envisions an interview less, presence less and paperless world where workforce can remain job ready always through continuous education, skilling and have access to new opportunities at their fingertips powered by Decentralized skilling and education network, open standards for information exchange using W3C VCs creating portable trusted data and interoperable systems that can cater to billion people accelerating the dream of an inclusive “always on” India. 
 

### Target Audience 

 - Organizations of all sizes who can easily register and post new jobs that gets published on the DSEP network – think of white-collar jobs like Software developer as well as Blue collar jobs like Delivery Boy 

 - Individuals can also become Jobs providers – think of need for drivers, maids, part time accountants  

 - Citizens looking to upgrade their livelihood and stand out in job applications compared to their peers  

 - Coverage – all of India, extensible to add Google Translate and language translation/ voice chat enabled features to be accessible for diverse audiences.

### UserFlows
We focused on Challenge 1 and 3, to build an integrated Jobs and course discovery and fulfilment journey leveraging Verifiable Credentials to reduce the cost and time of establishing trust. We focused on showing interoperability and portability between systems if they are built using Open standards and specifications. The solution is extensible in future to cover additional related scenarios and enrich the journey with more credentials issued, stored and shared over DSEP to reduce the cost of establishing trust across ecosystems.  

 - User will search & select upskilling courses on the MyBuddy mobile application leveraging decentralized skills and employment network (DSEP /search and /select) 

 - User will select and submit enrolment with the course provider to share their intent of upskilling (DSEP /confirm) 

 - User will get a link from the course provider to complete their learning and take a quiz 

 - User will browse to the training quiz portal (PWA) and complete the tasks necessary to qualify for the course completion certificate 

 - Training Quiz application uses India DPG Sunbird RC to sign and issue a Proof of Skill Verifiable Credential to the user  

 - User stores the issued credentials in his/her credentials wallet already integrated on the Training quiz portal 

 - User goes back to the MyBuddy application and can check the status of the course enrolment now updated as completed along with VC url from the Training provider. (DSEP /status) 

 - MyBuddy app can optionally add the Proof of Skills to user’s Credentials wallet – which is also integrated with MyBuddy app  

 - Employer will sign up on a multi-tenant Job publishing portal by providing Name and Organization (in future KYB checks can be added) 

 - Employer will post a new job from the interface that would be published on the DSEP network (repeat as required)  

 - Now that the user is upskilled and job ready, they will search for relevant jobs (DSEP /search and /select) 

 - User will select a relevant job from the list and Attach certificates from the wallet to be included in their job application  

 - User will apply to the selected job with trusted verifiable credentials (DSEP /confirm) 

 - This will complete the user journey to submit the job application. 

 - Employer can view all jobs and submitted application on the Jobs portal. They can clearly see applications submitted with VCs  

 - Employer checks the details of Job Application and leverages Affinidi Verify APIs to independently verify the submitted VCs shared by candidate  

 - Employer see “green” tick for verified data and can proceed to accept/reject the candidate 

 - User will browse to the submitted Job application on the MyBuddy App and can validate the status of Job Application to close the loop (DSEP /status) 


### Features  

MyBuddy consumer facing mobile application (EUA) providing unified experience for end user to discover new upskilling and job opportunities from a single app creating an “always” job ready workforce.  

 - The fully working prototype leverages two domains on DSEP and extensible to cover all four domains 

   - Training & Courses  

   - Internships & Jobs 

 - Citizen centric application where user can “store” and “share” trusted documents in a platform agnostic Credentials Wallet and leverage them during “checkout” processes irrespective of where the issuance happened.  

   - Built on Open standards and Specifications, the application leverages Verifiable credentials to accelerate establishing trust in the paperless digital world 

   - Improves accessibility of the trusted data for citizens across platforms 

 - Flexible application workflow that caters to Blue collar as well as White collar job seekers (unorganized and organized sectors) and easy to extend the application architecture  

 - Provides paperless course certificates in the form of W3C Verifiable Credentials as proof of skills to prospective employers increasing the trust in job applications & helping accelerate interoperable systems for India scale with choices to every builder (consumer and provider) 

 - Mock interfaces for Provider side experience to illustrate the end to end journey 

   - A Training Quiz Portal where the user completes the tasks necessary to qualify for Course Certificate 

   - A Multi-tenant Employer Jobs Portal showcasing how an individual or an organization can become a Jobs provider easily and publish job opportunities to the DSEP Network 

 - Showcases the power of interoperability creating independent ways for Service Providers to “verify” the paperless certificates – without any knowledge of issuance system or the software used for issuing the certificate  

   - Illustrate a working sample of Showcases the power of interoperability using W3C VCs as the format for data exchange between participants of the ecosystem allowing  

   - Standards based implementation showcasing interoperability between tools and multiple systems in an ecosystem. Course completion certificate is issued using Sunbird RC and then Verifying the certificate using  

 - The solution is extensible to create Proof of Work through a decentralized peer to peer network empowering employers to broadcast request for Background check through DIDAuth and Messaging services in a privacy preserving way. The users of wallet may chose to respond with a reference check and Employers may utilize that as to further accelerate trust building in job applications 


### Architecture
Consumer facing app flow with DSEP network for /search, /select, /confirm and /status - here[https://swimlanes.io/#3VbBbiM3DD13voK3JsZOku0xBQLE2SBtF2kNpEEPRdEwGtoWopGmksaOUfTfS0ozHo+ddPeQXHqyLUqP5OMjzaijoXO4cja0NXmYo9J2Adg0oG0kjypqZ2Gt4xI+3V3PwFJcO/8E0UGlg3IrfuSaxvnYWh01hcK6yIjamDZEj5ECtAEXBG4Od4ReLT/wpyEVAW0lnufa1zC9vvr8M1zOfgzwuDmI5/r+MsVkiP3hQo7ikuDe6rmmCqaXM/A0J09WESijyUaosSLAFWqDj4Zg7jz8gOoJ49LZoouSnrFu2BgUWfTaQTlk5TnIFTKQcq0PnIYgtE144tQSRxy9cvI8EpD1ztTiNlGFED2nz6H1fDXoo1a6EUAmVLgsitvNtK2qjWRXXtwH8rdomSrBKZmKIzYcn4MYrjxhqoR4vWwao1X6fReZ4eFV8QoIlOUF7Hg7h4fvzs4e4JfPe0HAb555Js+MlnzC98LGqgc4nUxCKt5kcsTub11F5hiK8e3kZR+gvy2KmZJ6svnXJ4x4m26GQ5iLvrJS2CGGHMHRgHLclXHqHVYKQ+wUJr5Gam3cmsVRibSy0BrvolPOpKJedQUWbn9yj2GrgQ18P9JYpyx+vNKVPIAlYWUoBJAQRb6AIakCxR2Hgb0hSANMb4Icsq1loYqEsz1IGett3fi04QYJ3IMifWbo5OTkHP6eYyhDo60l/w98PAsSiWLvqR90zSL3rh5FvEdEscMrszy9EXbxdXr5QnlQjV450xuBmM3Cf4PA+lQetl4X6XK5ddwBwc55RpvltBJBGRD+aqUcqedamSrMYWhNZHPs34/jPHX2z+7tKBqRYQ6HIRTpFTPFNHdXPbEj1tGIqJ00+9wH8zcHBK1Rx6Srj2cMq1hDiseZM7qSuNEYQZP4Gz7u5opkGp9BVx+gDgv+3A9gr0VkZBsZojITRFgjxFENX2rSoee/ALTt9aL40qRII0KQRiOC6V5wiWrnCSqKPI2DzD/JV7Pk32SCQB4DrLNZLiz34Au1fdHfq6NGMtmXcQfPkFzRSM8Rfl+4/GfkXbtYiq7Zd4MhdCd/FPstl4WU275zM67Xthl2A2PdpZZ7QehD700mSfNdDd5c9Af2A03mnkyTrk/tzYS6A/81UlR5r/g/aLFL5d3F2Pl5UzUOZfgqOSbJvIsc++TeRY/jZTKvEzsrYa+1tEDygpb2ApX2wNESKULsl022/epRWylot2/4b7mavGijgX5/9dTwXggB67zg9lmewsA9///IetGGfNp9l3n+Lw==]

## Product demo	

## User guide	

## Source code	

## Developer guide
