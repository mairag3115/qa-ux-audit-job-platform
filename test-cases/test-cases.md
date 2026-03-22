\# Test Cases



\## TC-01 – Search for a job by keyword

\*\*Precondition:\*\* User is on the homepage  

\*\*Steps:\*\*

1\. Open the platform

2\. Enter a job title in the search bar

3\. Click search



\*\*Expected Result:\*\*  

The system displays job listings related to the keyword entered.



\---



\## TC-02 – Filter jobs by location

\*\*Precondition:\*\* Search results are displayed  

\*\*Steps:\*\*

1\. Open search results

2\. Select a location filter

3\. Apply the filter



\*\*Expected Result:\*\*  

Only jobs matching the selected location are displayed.



\---



\## TC-03 – Open a job offer

\*\*Precondition:\*\* Search results are visible  

\*\*Steps:\*\*

1\. Click on a job listing



\*\*Expected Result:\*\*  

The job details page opens correctly with complete information.



\---



\## TC-04 – Apply to a job

\*\*Precondition:\*\* User is logged in and viewing a job offer  

\*\*Steps:\*\*

1\. Click on “Apply”

2\. Complete required fields

3\. Submit application



\*\*Expected Result:\*\*  

The application is submitted successfully and a confirmation message is displayed.



\---



\## TC-05 – Validate empty search

\*\*Precondition:\*\* User is on the homepage  

\*\*Steps:\*\*

1\. Leave the search field empty

2\. Click search



\*\*Expected Result:\*\*  

The system displays either a validation message or relevant default results.



\---



\## TC-06 – Validate broken or confusing filters

\*\*Precondition:\*\* Search results are displayed  

\*\*Steps:\*\*

1\. Apply multiple filters

2\. Remove one filter

3\. Check updated results



\*\*Expected Result:\*\*  

The system updates results correctly and reflects active filters clearly.



\---



\## TC-07 – Validate navigation back to results

\*\*Precondition:\*\* User is on a job details page  

\*\*Steps:\*\*

1\. Open a job offer

2\. Return to previous page



\*\*Expected Result:\*\*  

The user returns to the same search results page without losing context.



\---



\## TC-08 – Validate responsive clarity

\*\*Precondition:\*\* Platform is open  

\*\*Steps:\*\*

1\. Open the platform on a smaller browser window

2\. Check readability and layout



\*\*Expected Result:\*\*  

Content remains readable and key actions are visible.



\---



\## TC-09 – Validate back navigation after application flow

\*\*Precondition:\*\* User is logged in and has opened a job offer  

\*\*Steps:\*\*

1\. Open a job listing

2\. Start the application flow or enter the job details page

3\. Click the browser back button

4\. Observe the search results page



\*\*Expected Result:\*\*  

The user returns to the search results page in a normal and fully interactive state without visual overlays or blocked elements.

