# internship_web_scraping_expanded
## Final Project for DAT-129 (Python II) - Analysis of Indeed.com data collected with BeautifulSoup

### Abstract

This program uses Python's `requests`, `pandas`, `csv`, `time`, and `BeautifulSoup` modules to scrape a simple search for U.S. internships on the popular job search engine, Indeed.com. The program exports this data to csv files, then imports them back into Python as a `pandas` dataframe in order to analyze current trends in internship compensation, geographic locations, and industries. 

### Purpose & Inquiry Question

For this project, I set out to look at a snapshot of internship listings (posted within the last week of April 2021) on the popular job search engine Indeed.com. I was interested in exploring the following questions:

* What percentage of internship opportunities currently listed on Indeed are paid positions?
* Among the paid internship opportunities on Indeed, what are the pay rates like?
* Geographically, where are paid internships concentrated?
* Are certain industries more likely to pay their interns than others?

I hypothesized (before reading the 2016 report from NACE) that only about 20% of internship postings would be paid opportunities, that most paid opportunities would offer around $15 per hour, that paid opportunities would be concentrated in urban areas with high costs of living (NYC, the Bay Area, Chicago, and D.C), and that most of the paid opportunities would be in the fields of web development/engineering and finance. I backed away from the industry-related inquiry after realizing that, in this time of social distancing, it appears that the industries hiring interns right now are mostly ones where remote work is possible. For example, Indeed's Hiring Lab recently reported that [the percentage all marketing internships that offer remote work jumped from 14.3\% to 45.3\% during the pandemic](https://www.hiringlab.org/2021/04/27/remote-internships-jump-during-pandemic/).

### Background

Nearly ten years ago, Ross Perlin, author of *Intern Nation: How to Earn Nothing and Learn Little in the Brave New Economy*, estimated that U.S. employers hire for 1.5 million internships each year, and that approximately half of those internships are unpaid. More recently, in 2016, the National Association of Colleges and Employers (NACE) estimated that [around 60% of U.S. interns are paid, with most unpaid opportunities coming from social service fields](https://sites.sju.edu/careers/files/the-impact-of-unpaid-internships-on-career-development.pdf). NACE research on the topic of U.S. internships has also revealed that [college students who complete paid internships have far more favorable post-college employment outcomes than those who only complete unpaid internships](https://www.theatlantic.com/business/archive/2013/06/do-unpaid-internships-lead-to-jobs-not-for-college-students/276959/). In addition to offering interns less resume-building value than paid opportunities do, there are enduring concerns about the [equity](https://www.usnews.com/opinion/knowledge-bank/articles/2016-04-04/education-or-exploitation-should-all-internships-be-paid) and [legality](https://www.shrm.org/resourcesandtools/legal-and-compliance/employment-law/pages/is-your-unpaid-internship-program-legal.aspx) of unpaid internships. 

Despite all of this, unpaid internships still abound in the U.S. Meanwhile, young adults (ages 16-24) are facing unprecedented unemployment rates during the COVID-19 pandemic. The Bureau of Labor Statistics reported the following update on youth unemployment in summer 2020:

> Typically, the number of unemployed young people increases between April and July, as people who were not in the labor force while attending school begin seeking 
> employment. However, this year unemployment increased sharply in April because of the coronavirus pandemic. The number of unemployed youth rose from 1.7 million in February > to 4.9 million in May, and declined to 4.0 million in July. In July 2020, there were 1.9 million more unemployed 16- to 24-year-olds than in July 2019. About two-thirds of > the unemployed youth in July 2020 were looking for full-time work, a similar percentage to a year earlier.

### Analysis Steps

### Conclusions

### Limitations

### Future Research
