# InternChallenge

The purpose of this challenge is to assess the candidate in these areas:
1. Problem solving skills
2. Coding abilities
3. Creativity

## The Challenge: Lite URL
Have you seen bit.ly or goog.gl or tinyurl.com? These are URL shrinkers which provide a short alternate URL instead of a long one.
**You challenge is to create a simple product like that.**

### Usage Scenario

User X wants to share a "lite url" with User Y.

![Seq Diagram](/images/liteURL-seq.png)

* User X visits your product website (Lite URL) and pastes the long URL (e.g. an ebay URL)
* Your website gives a shorter version back to User X.
* User X shares the lite url with User Y through some way (tweet, email, txt, ..)

* User Y clicks on the lite URL.
* Your website redirects the browser to the original website with long url.

### Technical Requirements
1. Design a SQL database to store URLs.
2. Create an ASP.Net project (ASPX or MVC) with minimum two functions or pages:
	* index page (this page is used to accept long URLs)
	* redirect page (this page is used to accept short URLs and redirect to long URL)
3. Create a simple algorithm to ensure uniqueness of short URLs

### How we judge your solution
1. Completeness of task
2. Code Quality
3. Code comments

### Important Reminders
* You must be able to demonstrate the solution on yours or our laptop.
* Any version of ASP.Net is fine, but an MVC solution gets one more point.
* Any database is fine. Think simple! e.g. sqlite, MS Access. If using SQL Server or Oracle, prepare a DDL file. 
* Use Internet as a reference only. 
* We have sophisticated sensors deployed at our offices to identify candidates who copy-paste (:
