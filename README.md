# alexa_shopper

Skill to query crawler-collected grocery store sale data and find cheapest store to buy a particular item. My shopper crawler checks local grocery ads for the week and uploads all results to a database, which alexa_shopper references when the user asks it to find the cheapest ocurrence of a particular item.

Example: "Where can I find the cheapest sardines?" will prompt alexa_shopper to check the database for any sardines listed in any of the weekly ads, and then report the lowest price and which store is selling them.
