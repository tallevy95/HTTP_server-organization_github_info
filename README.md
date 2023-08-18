# HTTP_server-organization_github_info
Junior SW Engineer - Home Assignment

	In this assignment, I was requested to write an HTTP server that provides information about
	a GitHub organization's repositories.


Description:
	
	- approach_1.py will generate a data.csv file containing the requested information (more on this later).
	- approach_2.py will generate a HTTP server using Flask that contains the requested information (more on this later).

 	** approach_1.py is an alternative approach for getting the requested inforamtion,
  	   but approach_2.py is the **primary** approach for the assignment.

	The requested information:
	- Name
	- Owner
	- URL
	- Creation time
	- Number of stars

	Given an organization name and a phrase, return a list containing the organization's
	visible repositories that match the provided phrase. 
 	If no phrase is provided, the endpoint should return the unfiltered list.

Installation:
	
	1. Clone the repository: git clone https://github.com/tallevy95/HTTP_server-organization_github_info.git
	2. Change the directory: cd HTTP_server-organization_github_info
	3. Install dependencies: pip install -r requirements.txt
	4. Run the project: python approach_<Number>.py  <Organization> <Phrase>
	   * <Number> can be 1 or 2
	   * <Organization> is a must (i.e: gofireflyio, aws, microsoft, etc.)
	   * <Phrase> optional - default value is None (must be length 3 or more)

Usage:
	
	To use this project, follow these steps:
		1. Run the selected approach as explained above.
		2a. For approach_1: open the csv file in the program directory.
		2b. For approach_2: Copy and paste the URL from the CMD, http://127.0.0.1:5000
