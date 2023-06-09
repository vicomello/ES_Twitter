# data

data.csv has the experience sampling data and cross-sectional data.

## Experience sampling variables 
(each row is an answered ES survey)
- `ResponseId`: unique identifier for each response
- `random_id`: random id for each participant
- `used_tt`: if participant has user Twitter (1) or not (0) in past 30 minutes 

Functions of Twitter use
- `distract`: if participant has used twitter for escapism past 30 min
- `entertain`: if participant has used twitter for entertainment past 30 min
- `promote`: if participant has used twitter for self promotion past 30 min
- `information`: if participant has used twitter for information seeking past 30 min
- `interact`: if participant has used twitter for social interaction past 30 min

Behaviors on Twitter:
- `w_tweeted`: whether participant tweeted in past 30 min
- `w_liked`: whether participant liked a tweet in past 30 min
- `w_rt`: whether participant tweeted in past 30 min
- `w_commented`: whether participant replied to a tweet in past 30 min
- `w_messaged`: whether participant messaged anyone in past 30 min
- `w_visited`: whether participant visited any profiles in past 30 min
- `w_trending`: whether participant checked the trending topics in past 30 min
- `w_scrolled`: whether participant scrolled down the feed in past 30 min

Interacting with others:
- `interact_other`: whether participant interacted with anyone with opposing views in past 30 min on twitter

Other social media platforms:
- `facebook`: whether participant used facebook
- `instagram`: whether participant used instagram in past 30 min
- `tiktok`: whether participant used tiktok in past 30 min
- `snapchat`: whether participant used snapchat in past 30 min
- `whatsapp`: whether participant used whatsapp in past 30 min
- `wechat`: whether participant used wechat in past 30 min
- `another`: whether participant used another social media paltform in past 30 min
- `no_other`: whether participant used no other platform in past 30 min

Experienced emotions (Modified SPANE):
- `positive`
- `negative`
- `sad`
- `afraid`
- `joyful`
- `angry`
- `bored`
- `lonely`
- `disgusted`
- `anxious`
- `excited`
- `tired`
- `pos_aff`: average for positive emotions (positive, joyful, excited)
- `pos_aff`: average for negative emotions (negative, sad, afraid, angry)

Social interactions:
- `interact`: whether participant has interacted with anyone in past 30 min
- `in_person`: whether interaction was in person (1) or not (0)
- `quality_interaction`: rating of interaction quality

Sense community:
- `sense_community`: whether participant feels like they belong in a community
- `respect_community`: whether participants feel respected in a community

Polarization:
- `republican_warm`: how warm participant feels towards republicans
- `democratic_warm`: how warm participant feels towards democrats
- `polarization.x`: absolute value of difference in warmth between parties

Conspiracy tendency:
- `news_suspicion.x`: the degree of suspicion in news
- `trust_gvt.x`: the degree of trust in government

Personal:
- `where`: where the participant is
- `working_hours`: whether participant is during work/school hours or not

Survey info:
- `day`: day of survey
- `time`: time of survey
- `StartDate`: same of "day", but different format
- `attention_check`: whether participant passed attention check (those who didn't are not in data)
- `day_0`: day that first survey was sent to participant
- `days_elapsed`: number of days that passed since day_0
- `obs`: number of observation (1-35), varies by amount of surveys answered by participant

## Cross-sectional variables
(varies by participant, repeats in some rows)

Personality (Big 5 Inventory-2):
- `extraversion`
  - `sociability`
  - `assertiveness`
  - `energy_level`
- `agreeableness`
  - `compassion`
  - `respectfulness`
  - `trust`
- `conscientiousness`
  - `organization`
  - `productiveness`
  - `responsibility`
- `neuroticism`
  - `anxiety`
  - `depression`
  - `emotion_vol`: emotional volatility
- `openness`
  - `int_curiosity`: intellectual curiosity
  - `aes_sensivity`: aesthetic sensitivity
  - `creative_ima`: creative imagination

Satisfaction with life:
- `sats_w_life`

Self-esteem:
- `self_esteem`

Loneliness:
- `emotional_loneliness`: emotional loneliness component
- `social_loneliness`: social loneliness component
- `loneliness`: overall loneliness score

Trait boredom:
- `boredom`

Trait impulsivity:
- `impulsivity`

Twitter use:
- `tt_smartphone`: whether participant uses Twitter on smartphone
- `tt_laptop`: whether participant uses Twitter on laptop
- `tt_desktop`: whether participant uses Twitter on desktop computer
- `tt_tablet`: whether participant uses Twitter on tablet
- `tt_other`: whether participant uses Twitter on another device 
- `tt_weekly`: weekly frequency of Twitter use
- `tt_daily`: daily frequency of Twitter use

Sense of community:
- `online_community`: whether participant feels part of any online community
- `sense_community`: how much sense of belonging participant gets online
- `psych_sense_community`: psychological sense of community

Functions of social media use scale:
- `entertainment`: using Twitter for entertainment
- `interacting`: using social media for social interaction
- `promoting`: using Twitter for self-promotion
- `info_seeking`: using Twitter for information seeking
- `coping`: using Twitter for escapism

Online habits:
- `news_consump`: degree to which participant consumes news online
- `follow_rlpeople`: degree to which participant follows accounts of people they know in real life
- `follow_humour`: degree to which participant follows humurous pages
- `follow_news`: degree to which participant follows news pages
- `follow_influencers`: degree to which participant follows influencers
- `follow_business`: degree to which participant follows business accounts
- `follow_famous`: degree to which participant follows celebrities
- `follow_politician`: degree to which participant follows politicians
- `follow_blogs`: degree to which participant follows blogs
- `follow_incommon`: degree to which participant follows other users with interests in common
- `follow interesting`: degree to which participant follows interesting content

Social Media Addiction:
- `SM_addiction`

Ideiology and Politics:
- `political_id`: self-reported ideology, dem to rep (-3 to 3)
- `pol_engagement`: overall score of political engagement
- `dem_feelings`: how warm participant feels towards democrats
- `rep_feelings`: how warm participant feels towards republicans
- `polarization.y`: overall polarization (absolute value)
- `con_ideology`: conservative ideology support
- `lib_ideology`: liberal ideology support
- `trust_gvt.y`: trust in government
- `married_dem`: how upset they would be if a close friend or family member married a democrat
- `married_rep`: how upset they would be if a close friend or family member married a republican

News habits:
- `news_consumption`: how often participant consumes news
- `news_socialmedia`: frequency of social media use on social media
- `news_newspaper`: frequency of news consumption on newspapers
- `news_searchengine`: frequency of news consumption on search engines
- `news_aggregator`: frequency of news consumption on news aggregators
- `news_cabletv`: frequency of news consumption on cable tv
- `news_suspicion.y`: general suspicion of news
- `shared_regret`: how much participant shares something and regrets later

Demographics (collected by prolific):
- `age`: participant's age
- `Nationality`: participant's nationality
- `Sex`: participant's self-reported sex 
- `ethnicity`: participant's ethnicity
