# data-sourcing-challenge
Data Sourcing Exercise
## In this challenge the use of API's is demonstrated by pulling information from "The New York Times" and using some of it to pull information from "The Movie Data Base"
### For this challenge the following libraries where needed:
- requests
- time
- dotenv
- os
- pandas
- json

### Each API provider has it's own specifications, in order to successfully pull the information the following pages where consulted:
- [New York Times (Dev Portal)](https://developer.nytimes.com/docs/articlesearch-product/1/overview)
- [The Movie Data Base (API/Devloper)](https://developer.themoviedb.org/docs/search-and-query-for-details)

### Besides the specification to pull information, each site also has specific limits on the number of requests and the frequency of these. The code includes "coold down" times to comply with these API Provider conditions

### In addition to the Python and Pandas commands used in previous challenges the following are used in this challenge
- requests.get()
- time.sleep()
- Try:, except:
- json.dumps().json()
- Pandas Merge (pd.merge())
