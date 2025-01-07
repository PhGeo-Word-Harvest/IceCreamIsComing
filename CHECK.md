# BASICS  
### Github Organization  
:white_check_mark: Github Organization exists  
:no_entry: Github Organization **not** assigned (or not public):  
1. Goto https://github.com/orgs/PhGeo-Word-Harvest/people  
2. Check if KMicha is listed as Members  
3. Else: 'Invite member' KMicha  

---
  
### NewsAPI  
:white_check_mark: NewsAPI key exists  
:white_check_mark: NewsAPI respone fine  
:white_check_mark: NewsAPI status fine  
:white_check_mark: NewsAPI results found  

---
  
### GeonamesAPI  
:white_check_mark: Geonames key exists  
:white_check_mark: Geonames respone fine  
:no_entry: Geonames status **failed**:  
Please recheck the API key and its assignment:  
1. Please register with username (i.e.: PhGeo_Word_Harvest) at https://www.geonames.org/login  
2. Assign the choosen username as new organization secret at https://github.com/organizations/PhGeo-Word-Harvest/settings/secrets/actions/new  
   * Name:  **GEONAMES_KEY**   
   * Value: **Your username here**   

---
  
### RapidAPI  
:no_entry: RapidAPI key **missing**:  
1. Please register at https://rapidapi.com/auth/sign-up  
2. Login and 'Subscribe to Test' at https://rapidapi.com/bonaipowered/api/google-news22  
3. Make sure to enter 'Start Free Plan' and press 'Subscribe' - **don't** enter credit card data!  
2. Copy your API key from (**X-RapidAPI-Key**) from the same site  
3. Assign the API key as new organization secret at https://github.com/organizations/PhGeo-Word-Harvest/settings/secrets/actions/new  
   * Name:  **RAPIDAPI_KEY**   
   * Value: **Your key here**   

---
  
