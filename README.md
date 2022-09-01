# Glassdoor Customer Retention Prediction

Problem statement:

You are the analytics lead on our Jobs Marketplace team, which is responsible for ensuring that customers realize value from Glassdoor's jobs products. When customers are happy with performance, as measured by the applications they receive, it translates into value for Glassdoor as we are able to retain and grow accounts.  

Glassdoor sells a subscription jobs product called Job Slots. A job slot is like a recurring job posting that customers have access to over the life of the contract. Customers pay up-front and can select from a range of 
Job Slot packages, which differ based on the number of slots included. Customers can swap jobs in and out of the job slot, enabling them to use the posting flexibly as hiring needs change. While Glassdoor does not
guarantee a specific level of delivery per slot, our ad platform does try to assign an application goal based on a variety of factors (e.g. location, job type, contract size, etc). Glassdoor traffics job slots using a bidding 
algorithm that increases bids when an account is underperforming its application target and lowers bids when it is pacing ahead.  Our search algorithm the surfaces jobs to job seekers based on a combination of
relevance and business value (i.e. the bid amount).

Customers evaluate performance based on the number of applications they get vs. the cost-per-application. The volume and cost a customer realizes ultimately depend on a variety of factors: the size of the deal, location, industry, roles the employer is trying to fill, the attractiveness of the employer to job-seekers, etc. We believe that customers decide to renew or not based on the performance factors above, though there are likely other reasons.

Which factors or combination of factors best predict an employer's likelihood to retain (i.e. renewed_flag = 1)? And how well does your chosen model predict retention? Please list any assumptions you made in the
