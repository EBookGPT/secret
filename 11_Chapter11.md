# Chapter 11: Workplace Secrets

Welcome to the eleventh chapter of our book on secrets! In this chapter, we delve into secrets within the workplace. Just like families, workplaces are social systems where individuals interact with one another on a daily basis. As such, they are bound to harbor their own secrets, both benign and sinister.

In this chapter, we will follow the footsteps of Sherlock Holmes as he uncovers some of the most intriguing workplace secrets. Through his keen observations and analytical mind, we will witness how he unearths lies, deceit, and greed that lurks within the confines of an office.

But it's not all darkness and gloom - we'll also explore the lighter side of secrets within the workplace. From office romances to hidden talents, there are plenty of secrets that can bring a smile to our faces.

So sit back, get comfortable, and get ready to solve some mysteries!
# The Case of the Stolen Designs

Sherlock Holmes had received a rather curious request one Monday morning. A senior executive from a prestigious design firm had contacted him, claiming that their latest designs for a groundbreaking product line had been stolen. The designs were worth millions of pounds and had taken the team over a year to develop. Needless to say, the firm was in a panic.

As soon as Sherlock entered the office, he could see the tension in the air. Employees were scurrying around the office, trying to put on a brave face while also searching for any clues that might help them find the stolen designs. 

Sherlock began his investigation by examining the offices themselves. He found no signs of forced entry, which meant that whoever had taken the designs must have had access to the building. He also noticed that the firms' senior executives were not only the ones with the most to gain from the incident, but also the only ones with the level of access needed to acquire the designs.

Next, Sherlock analyzed the activity on the company servers. He discovered that someone had accessed the firm's network with a stolen login credential belonging to the head of IT. From there, the thief had been able to easily download the designs and send them to themselves via email. 

Faced with this evidence, Sherlock confronted the head of IT, who quickly broke down and admitted to the theft. The executive had been bribed by a competitor to steal the designs and had leveraged the weakness in the IT system to gain access. The executive was promptly fired and prosecuted, and the designs were eventually recovered.

In the end, Sherlock learned a valuable lesson about secrets in the workplace. Just because someone has access to sensitive information doesn't mean that they can be trusted. It takes a vigilant eye to spot the signs of deceit and the courage to confront those responsible for their actions.
# The Code to Crack the Case

As we followed Sherlock Holmes through the Case of the Stolen Designs, we witnessed his incredible ability to decipher clues, analyze data, and find patterns that others might miss. But how did he do it? Let's take a closer look at the code he used to solve the case.

## Code Example 1: Network Analysis

Sherlock used a variety of tools to analyze the activity on the firm's servers. Here is an example of some Python code he used to parse the server logs and identify the IP addresses associated with the theft:

```python
with open('server.log') as f:
    for line in f:
        if 'accessed designs' in line:
            ip_address = re.search('\d+\.\d+.\d+.\d+', line).group()
            users[ip_address].append(username)
```

This code uses a combination of regular expressions and file I/O to extract the IP addresses associated with network activity related to the stolen designs.

## Code Example 2: Email Analysis

Sherlock also analyzed the email traffic associated with the theft to identify the recipient of the stolen designs. Here is an example of some R code he used to parse the email headers and extract the relevant information:

```r
library(readr)

emails <- read_csv('email_headers.csv')

stolen_designs_emails <- filter(emails, to_address == 'competitor@example.com' & subject == 'Stolen Designs')

recipient_email <- stolen_designs_emails$from_address[1]
```

This code uses the `readr` package in R to read in a CSV file containing email header information. It then uses the `filter()` function from the `dplyr` package to extract the relevant emails based on the recipient and subject. Finally, it extracts the email address of the sender, which was ultimately used to tie the theft to the head of IT.

By using these and other analytical tools, Sherlock was able to efficiently extract valuable information that helped him crack the case of the stolen designs. This just goes to show that even the most intricate secrets can be uncovered with the right code and detective skills.


[Next Chapter](12_Chapter12.md)