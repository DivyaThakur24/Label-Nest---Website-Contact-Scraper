# Label-Nest---Website-Contact-Scraper
### Write a Python script that:
1. Takes 2 company website URLs (you may choose any).
2. Extracts contact information such as email, phone number, and page link.
3. Saves results into a CSV file with columns:
   Website | Email | Phone | Page Found | Notes

(Optional Bonus): Add regex validation to check for invalid or duplicate entries.

### Expected Submission:
Code file (.py or notebook)
Output file (contacts.csv)
Screenshot of the script running

### Approach / Logic
1. **Input:** Two company website URLs (you can use any, e.g., https://www.python.org and https://www.djangoproject.com).

2. **Fetch** the HTML using requests.

3. **Parse** the content using BeautifulSoup.

4. **Extract** emails, phone numbers, and links using regular expressions (regex).

5. **Clean and validate** data (check for duplicates or invalid formats).

6. **Save output** to CSV using pandas.

   ![output screenshot](website_contact_scrapper.png)
