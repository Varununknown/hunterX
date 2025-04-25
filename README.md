# HunterX
An - #Anti Piracy Tool  [ Ai - CyberSecurity ]

꺛꺘 Project Title: Piracy Hunter X – Smart AI Tool to Detect Piracy Links and Report, infect them.

��� Project Goal:
To automatically detect and infect or report pirated film download links from platforms like Telegram and websites, using film titles of recently released movies, and then generate an automatic report showing all the actions taken.


껩 How It Works – Step-by-Step:

✅ 1. Film Title Collector
     Automatically fetch the names of newly released movies (e.g., from IMDb,BookMyShow, or a simple JSON list).
     Example: “Pooja 2025”, “Action Hero 2”, “Vikram Returns”
    
꺍 2. Smart Link Searcher
     For each movie title:
        o Search the web (Google, Bing) for phrases like:
     "<movie name> full movie download"
     "<movie name> Telegram link"
        Scrape Telegram channel preview data (optional APIs or manually throughweb scraping or bot)
        Collect all suspicious links
    
� 3. Piracy Link Detector (AI filter)

   Use simple machine learning or keyword filtering:
    o If the link contains known piracy terms like watch free, leaked print, 480p, HD download, it’s marked as pirated.
    o Otherwise, marked as safe or unknown.
    
뢐 4. Action Engine – Send Warn mail to the aunathorised owner ] 
   Attempt to:
    o Delete links using Telegram Bot API (if it’s your bot) or reporting system.
    o Auto-generate takedown emails for piracy-hosting websites.
    o Mark status: Deleted / Reported / Infected 
  # send Mails to pritaed link owners
  ![Screenshot 2025-04-26 044125](https://github.com/user-attachments/assets/a635a138-9533-4ffa-9576-b746f17e7757)

굊 5. Auto Report Generator
     After scanning:
      o Show a report like:
     蘯蘰蘱蘲蘳蘴蘵蘶蘷蘸蘹 Movie: Pooja 2025
     꺪꺫 Links Found: 25
     ✅ Deleted: 15
     뢏뢐 Reported: 10
     괜괝괞괟괠괡괢괧괣괤괥괦 Time: 04/25/2025
     Display in a dashboard or download as PDF.


뜠Quick summary

 Uses Google search + scraping to find suspicious links.
 Uses a simple rule-based piracy detector.
 Display links and actions in a web page.
 Generate report. 
