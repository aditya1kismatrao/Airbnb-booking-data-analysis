# Airbnb-booking-data-analysis for New York City Market data

### Data Processing:
Converted some the columns into a usable numeric format, subdivided some categorical variables into dummy columns, replaced missing values, clustering of latitude-longitude columns into area, topic modelling on description column.

### Kaggle competition statistics:
Data prediction AUC - 95.355
Model used - XGBOOST 
Number of features – 44
Parameters - scale_pos_weight=2.61, seed=42,n_estimators=1400,learning_rate=0.05,min_child_weight=3,max_depth=7,gamma=0

### Questions answered through model prediction:
Which Neighborhoods have high review scores?
How does Airbnb rental price vary across the neighborhoods?
Which areas have high booking rates?
Superhost analysis: What is the most important attribute of superhost? How important is host response rate?


### Business Proposal
Location score with high values tend to have high price range  The investor has to charge high rental price to recoup the purchase cost or to pay the mortgage. They cannot be priced higher than hotels.
Safe bet for new investor : Areas near Staten mall, orchard beach Pelham bay park, where although audience reach is lower but booking rate and review location scores are on higher side and competitive pricing strategy can be adopted.
However for veteran host he can choose to buy properties in prime areas of central Manhattan or airport area where volume of bookings and reach is comparatively high, and competition is stiff.
For superhost analysis - based on visualizations it's safe to say that review score rating contribution is highest when it comes to booking rate. Apart from that host should also have high listing count and response rate. Location of properties also plays a significant role. Also older the host better are his chances and count of amenities should also be substantial for achieving superhost status.
While NY might seem like a place with ''only-job'' mindset, its actually very family/kid focused being the safest of US metropolitan states. Thus, being family/kid friendly is an important amenity to have for visiting families. 
With NY's car traffic and parking issues, free street parking is an amenity that should definitely be present.
NY is a place with a lot of things to do. So people would generally prefer long stays in order to explore NY properly. Thus, having a long stay option is beneficial.
Also Internet, washers, cable tv coffee makers etc are other amenities that a host can add to improve the booking rate.

