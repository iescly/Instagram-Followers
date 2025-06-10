# Instagram-Followers
A simple Instagram script for adding likes, views, and followers to public accounts  
Version: 1.0.0
[![forthebadge Made-With-Python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)  

### Important Note
My Telegram account has been hacked. Please don't deal with my old account. DM `@iEscly` from now on.

## Overview
This Python script is a simple Instagram automation tool designed to simulate adding likes, views, and followers to public Instagram accounts.
 It provides a command-line interface where users can input an Instagram account name and choose to simulate actions like liking posts, viewing stories, or gaining followers. 
**Note**: This script is for educational purposes only, as automating actions on Instagram violates its Terms of Service and may lead to account restrictions.

### Features
- Validates Instagram account names and URLs via HTTP requests.  
- Simulates adding likes to Instagram posts, views to stories, and followers to accounts.  
- User-friendly CLI with colored output for better readability.  
- Includes basic error handling for invalid inputs or inaccessible URLs.  

Works On  
<a href="https://t.me/iEscly"><img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white"></a>  
<a href="https://t.me/iEscly"><img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"></a>  
<a href="https://t.me/iEscly"><img src="https://img.shields.io/badge/-kali%20linux-lightgrey"></a>  

## Requirements
- [Python 3.6 or Above](https://www.python.org/downloads/)  
- Required packages (listed in `requirements.txt`):  
  - `requests`  
  - `colorama`  

## Installation
1. Clone the repository:  
   ```bash  
   git clone https://github.com/iescly/Instagram-Followers.git  
   cd Instagram-Followers
   pip install -r requirements.txt
   python instagram-followers.py

   
 ##usage: 
 Launch the script with python instagram-Followers.py.
  Enter a public Instagram account name when prompted.
  Choose an option:
  1: Simulate adding likes to a post (requires a valid post URL).
  2: Simulate adding views to a story (requires a valid story URL).
  3: Simulate adding followers to the account.Follow the prompts to input URLs or confirm actions.
  The script will simulate the selected action and display progress.

## Example
Enter Instagram account name: example_user  
Please choose a bot category:  
[1] - Likes  
[2] - Views  
[3] - Followers  
> 1  
Enter your Instagram post URL (account must be public): https://www.instagram.com/p/abc123/  
Simulating like on https://www.instagram.com/p/abc123/  
1 likes added.  
...  
Finished: 5 likes added to https://www.instagram.com/p/abc123/.
