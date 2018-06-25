# WordPress A/B Testing Plugin Development - Test Assignment

Goal: create a Wordpress A/B testing plugin which creates a test between two landing pages, and counts the visitors and conversions for each page
 
Instructions:
1.  	Create a custom post type for the landing pages
2.  	Each landing page will have a field on its admin section to select between two front end templates
3.  	The plugin will allow us to create a test between two landing pages, the admin will be able to enter a name for each test.
4.  	When a user visits page #1 he will stay on that page or be redirected to page #2, (50% of the traffic for each page)
5.  	The number of visitors on each page will be stored on the DB
6.  	The amount of times a user has clicked the CTA button on the page will be stored on the DB, please make sure to store no more than 1 click per visit
7.  	The front end can be simple and minimal, there will be two possible templates (see section #2) and the one selected on the admin section be displayed to the visitor (as selected on section #2), the landing page will have a simple form on it (name, email address and a CTA button)
8.  	The data saved on sections #5 and #6 will be displayed on a table on the admin section for each tests (name of test, number of visitors for each page and number of conversions on each page [cta clicks])
9.  	The plugin will be able to escape server side caching, therefore redirects should happen on client side
10.  All code should be located on a wordpress plugin which will be able to be installed on any wordpress theme
