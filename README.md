# Pewlett-Hackard Analysis

## Overview of the Analysis

The purpose of this analysis is to understand the impact the “silver tsunami” will have on staffing needs at Pewlett-Hackard. The silver tsunami being an upcoming wave of employees, born from years 1952 to 1955, with eligibility for retirement. Additionally, we also must understand how many employees will remain with the company to offer mentorship to the next generation of Pewlett-Hackard employees, and if we have enough mentors on staff to make the transition successful.

## Results

* Retirement Title - This deliverable details all employees with upcoming retirement dates who are still with the company. Titles are isolated to the most current title held by the employee.

![retirement_title_image](https://user-images.githubusercontent.com/110419577/198190811-ad44f74f-50c3-478e-83d1-367baf986f45.png)

* Unique Titles - This table summarizes information from the Retirement Title table to only include employee number, first name, last name and title.

![unique_titles_image](https://user-images.githubusercontent.com/110419577/198190844-6ddc755d-d387-44cc-81db-511a1e6ade05.png)

* Retiring Titles - This table reflects the consolidated employee count per title of all positions up for retirement. This allows us to see how many of each position will need to be backfilled during the silver tsunami.

![retiring_titles_image](https://user-images.githubusercontent.com/110419577/198190872-a257b3b4-395c-4670-b587-9f000034f6a9.png)
    
* Mentorship Eligibility - This table reflects all current employees who are eligible to serve as mentors to the next generation of Pewlett-Hackard employees. Titles are detailed to understand areas of expertise in providing training.

![mentorship_eligibility_image](https://user-images.githubusercontent.com/110419577/198190980-e7b74df1-fa3f-4073-a74c-f42f17475269.png)

## Summary

When the silver tsunami is complete, we can anticipate that a total of 72,458 positions will need to be filled. Since this is a large number that spans over the length of three years, I decided to break out the first year of the silver tsunami to understand the most immediate training needs. To plan for the first year the silver tsunami, I pulled information on all current employees born in 1952 as they will be the first to be eligible for retirement. I found that within the first year of the silver tsunami, the following position counts will need to be filled:

![first_year_title_count_image](https://user-images.githubusercontent.com/110419577/198192456-4bf4acb6-fc51-4e7b-b61c-b1c1d335e90c.png)

It will be a difficult task to train for all positions opening in the first wave of the silver tsunami alone. Pewlett-Hackard has 1464 employees who can serve as mentors to take on mentoring the next generation of employees. To better understand how many mentors are available for training per title, I performed a count of all titles that those with mentorship eligibility hold. The count is broken out into position as follows:

![mentorship_titles_image](https://user-images.githubusercontent.com/110419577/198192828-b362d4a0-136e-46cb-898d-59ae7c0b8399.png)
    
There are far less mentors available than positions that will require new employees. The ratios of mentor to trainee are as follows:
 
* Senior Engineer - 1:44
* Senior Staff - 1:12
* Engineer - 1:6
* Staff - 1:13
* Technique Leader - 1:13
* Assistant Engineer - 1:4
* Manager - 0 mentors available
    
 As indicated above, this presents the greatest risk for training for the role of Senior Engineer as the ratio of mentor to trainees is 1 to 44. An effective way to resolve this may be to review current promotable employees working as Engineers. This will allow for training to be spread over a longer period of time, reducing the need for mentors to train a large amount of new employees all at once. 
 
It should also be noted that even though there are zero Manager mentors, we may be able to find mentors in those who served this role in the past and were promoted. Additionally, since there are few Manager positions to fill, it may be easier to find new external candidates with a previous history in management to take on these roles.

