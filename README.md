# GoogleDorks
    Note :Combination of these google dorks give enormous power for OSINT.I would keep updating it with time.
    
    site: Shows results to specific site for john carrier. 
    Example: site:facebook.com  John carrier

    intitle: Restricts results to titles of webpages.This will ask google to show pages that have the term in their html title. 
    Example: intitle:”Jobs in Defence”

    inurl: Restricts results to the URL of a website.Searches for specified term in the URL. 
    Example: inurl:register.php , inurl:about
    
    
    allintext:
    
    filetype: Searches for specific filetypes based on the extensions.
    Example: filetype:pdf site:indeed.com

    link: Searches for pages linking to a specified URL.
    Note:Google killed this operator in 2017, but it does still show some results—they likely aren’t particularly accurate though
    Example: link:www.indeed.com

    cache: Searches for a cached copy of a webpage when it was indexed by Google. 
    Example: cache:lums.edu.pk
    
    - sign remove the results from that name(may be site or titles)
    jobs -indeed
    
    Find non-secure pages
    Example: site:indeed.com inurl:-https
    
    Finding subdomains alongwith removal of www results
    Example: site:*.indeed.com -www
    
    Define:Too get defination and meaning of something  specific.It would show defination from different websites
    Example: define:lattice



## Real Scenario examples:

1-For finding hacked websites or which have hacked in the past(bb)
   ```site:*.edu.in Hacked ```
   
2-Search for open Telegram invites on a topic
    ```inurl:"https://t.me" "hacking"```
    
3-Explore LOG Files For Login Credentials
    ```allintext:password filetype:log after:2019```  
    ```allintext:username filetype:log```
    
4-For finding login pages
     ```intext:"username" and intext:"password"```
     
5-For finding people emails respective to your your specific person
     ```site:mit.edu "cryptographer|security|hacking" "gmail.com" ```
     
     
