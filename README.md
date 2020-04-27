# Twitter-API-COVID-19-
Original Idea: Twitter API to get tweet data of popular emojis used in COVID-19 months. Comparison of popular emoji's that were tweeted 6 months ago vs today. 
Expectations: Rise in "Covermouth Emoji", "Virus Emoji", "Sick emoji", "Praying emoji"
Issue: Twitter does not allow free access to tweet data older than 1 week without using their Enterprise APIs (https://developer.twitter.com/en/pricing); Only live tweets can be streamed for free. 

New Idea: Any Tweet containing keywords such as Covid or Corona virus will be streamed and their fields will be analyzed. The tweets' hashtags can be mapped to a wordcloud for analysis on popular topics that are mentioned during any COVID-19 related tweet. 
Result: 
  - Many hashtags mentioned #StrongerTogether #StayAtHome #FlattenTheCurve 
  - Others mentioned trending topics #FeverDetectionCamera #BorisIsBack (recovering from COVID-19), #BJPCourruption
  - Some made humor of the situation: #NBAhasLeftTheChat (cancellation of sporting events), #PleaseDontDrinkLysol (Reference to President Trump's comment of injecting disinfectants to combat COVID-19 - https://www.washingtonpost.com/nation/2020/04/24/disinfectant-injection-coronavirus-trump/)
