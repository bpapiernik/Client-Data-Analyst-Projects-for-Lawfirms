# Client-Data-Analyst-Projects-for-Lawfirms

# Webscraping Lawyer Database

This code utilizes web scraping methods to maintain and update a lawyer database by systematically extracting information from the American Academy of Matrimonial Lawyers (AAML) website. It begins by iterating through the paginated directory of lawyers, scraping names and profile links from each page using HTML element targeting. Once the links are gathered, the script visits each lawyer's profile page to extract additional details, such as the law firm name, telephone number, and email address. To ensure the process is robust, it handles missing information by assigning NA values where data is unavailable. The code incorporates respectful scraping practices by including a pause between requests to avoid overloading the website server. Progress indicators are included to monitor the scraping process. The extracted data is stored in a structured dataframe, which can be used for analysis or integrated into a larger lawyer database for administrative or informational purposes.

https://github.com/bpapiernik/Client-Data-Analyst-Projects-for-Lawfirms/blob/main/Webscraping%20Law%20Website%20Database.Rmd
