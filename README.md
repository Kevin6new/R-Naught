# R-Naught

The World Health Organization has declared the outbreak of the novel
coronavirus, Covid-19 as pandemic across the world. With its alarming surge of
affected cases throughout the world, lockdown, and awareness (social distancing,
use of masks etc.) among people are found to be the only means for restricting
the community transmission. In a densely populated country like India, it is very
difficult to prevent the community transmission even during lockdown without
social awareness and precautionary measures taken by the people. A group of our
students have developed an app to support police in identifying who all have
higher risk of covid infection and should be tested. All the variants of the corona
virus can be distinguished and recorded in the database. This app works by
computing the risk of exposure associated with each person by front and back
tracking covid patient's contacts. A few parameters like contact duration and
humidity in the contact location are considered for computing the risk of infection.
In shopping malls and for travel, instead of covid negative certificate, a low level
risk certificate of the app can be used. This app mainly focuses on development of
an Android application which can inform people of their probability of contraction.
This Android application sends a unique code to another phone which has installed
the same app via Bluetooth. The app uploads the details of their contact into the
Neo4j database. The application also notifies the users if they have come in
contact with a covid positive patient. The app also gives details of the hotspots
surrounding a person based on their location. The app helps to make a calculated
assumption to identify the patient zero(source) from a set of covid positive
patients. Using Neo4j Graph Database for much faster processing and ease of
mapping data to obtain a better picture. Factors like multiple levels of contact
tracing and duration of contact makes prediction more accurate than existing
prediction models. Much more efficient exposure prediction enabling person to
perform a test. To achieve all these functionalities, many tools, and APIs like
beacon,Neo4j are used in this application. Neo4j Graph database as database
server as it is faster in processing to help identify multiple contacts of person and
gives more importance to relationships. Send and Receive user id’s via app installed
in smartphones. Contact time and other attributes (Weather ) are sent and stored
in Neo4j database. The corresponding contacts of a person are retrieved and their
probability of contraction is calculated. Processed data is sent back to the
corresponding user along with precautions needed to be taken. Therefore, this
application can be used as a tool for creating further social awareness about the
arising need of precautionary measures to be taken by the people of India.

This is my undergrad final year project the owner of the repo where the project was stored was my group mate so I downloaded the project and uploaded it into my repo that is the reason why its showing it been uploaded recently.
