# Information Gathering with Google Dorking

## Introduction to Google Dorking

Google Dorking, also known as Google hacking, is a technique that uses advanced search operators to find specific information on the internet that is not readily available through simple searches. It's a powerful tool for information gathering and can be used for various purposes, from cybersecurity to research.

## How it's Used for Information Gathering

Google Dorking is a powerful technique for information gathering that leverages Google's advanced search operators to uncover hidden or sensitive information on the internet. Here's how it's used:

- **Discovering Vulnerabilities:** Security professionals use Google Dorking to find websites with security vulnerabilities, such as exposed login pages, error messages that reveal sensitive information, or publicly accessible configuration files.

- **Finding Sensitive Information:** Google Dorking can be used to locate sensitive data that has been unintentionally exposed online, such as personal information, financial records, or confidential documents.

- **Competitive Intelligence:** Businesses can use Google Dorking to gather information about their competitors, such as their marketing strategies, pricing, or customer lists.

- **Research:** Researchers can use Google Dorking to find specific information for their studies, such as academic papers, datasets, or government reports.

## Categories of Dorks

Google dorks can be categorized based on the type of information they are designed to find. Here are some common categories with examples:

### 1. Filetype Dorks

These dorks are used to find specific file types.

- `filetype:pdf "confidential"` - Finds PDF files containing the word "confidential."
- `filetype:xls "password"` - Finds Excel files containing the word "password."

<img width="779" height="714" alt="image" src="https://github.com/user-attachments/assets/f2409ac9-d6ed-44fd-8e79-d6825545be44" />


### 2. Inurl Dorks

These dorks are used to find specific text in URLs.

- `inurl:admin "login"` - Finds URLs with "admin" in them that also contain the word "login."
- `inurl:gov "secret"` - Finds URLs with ".gov" in them that also contain the word "secret."

<img width="740" height="482" alt="image" src="https://github.com/user-attachments/assets/35e85270-5e9a-4f9f-bda9-22756ec20e9f" />


### 3. Intitle Dorks

These dorks are used to find specific text in the title of a web page.

- `intitle:"index of" "backup"` - Finds pages with "index of" in the title that also contain the word "backup."
- `intitle:"login page" "admin"` - Finds pages with "login page" in the title that also contain the word "admin."

<img width="770" height="726" alt="image" src="https://github.com/user-attachments/assets/687f8432-bca4-4454-b7c3-275a639bdeb7" />


### 4. Site Dorks

These dorks are used to limit the search to a specific website.

- `site:example.com "password"` - Finds the word "password" on the website "example.com."
- `site:gov "secret"` - Finds the word "secret" on government websites.

<img width="763" height="740" alt="image" src="https://github.com/user-attachments/assets/418560ff-9197-49f8-9e45-cd55a867775b" />


## Usage Instructions

To use Google Dorking, you simply enter the dork into the Google search bar. You can combine different dorks to create more specific queries. For example, you can use the following dork to find PDF files on government websites that contain the word "confidential":

`site:gov filetype:pdf "confidential"`

## Summary

Google Dorking is a powerful tool for information gathering that can be used for various purposes. By understanding the different categories of dorks and how to use them, you can find specific information on the internet that is not readily available through simple searches.

## Ethical/Legal Warnings

It is important to note that Google Dorking can be used for both ethical and unethical purposes. While it is a valuable tool for security professionals and researchers, it can also be used by malicious actors to find and exploit vulnerabilities.

It is your responsibility to use Google Dorking in an ethical and legal manner. Do not use it to access information that you are not authorized to access, and do not use it to harm others.

**Disclaimer:** This information is for educational purposes only. The author is not responsible for any misuse of this information.
