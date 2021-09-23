# PRAW_to_Excel
A scraper linked to PRAW that scrapes posts and comments off of Reddit for user specifed subreddits, for a user specified keyword.



Example scrape_session inputs:
sub = ['Stopfossilfuels',

'divestment',

'environment',

'energy',

'climate',

'renewableenergy',

'electricvehicles',

'climateactionplan',

'climateoffensive',

'everythingscience',

'extinctionrebellion',

'sustainability',

'asksciencediscussion',

'solar',

'greennewdeal',

'climatechange',

'nuclear',

'infrastructurist',

'oil',

'greeninvestor',

'renewable',

'nuclearpower',

'sustainable']  

query = ['hydrogen']

path = (".../hydrogen")

scrape_session(sub, query, path)
