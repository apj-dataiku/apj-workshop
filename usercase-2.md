Prompt:

Determine whether each topic of the following list of topics is covered in the financial news article provided.
List of topics: fed and central banks, company and product news, corporate debt and earnings, energy and oil, currencies, gold and metals, IPO, legal and regulation, M&A and investments, markets, politics, stock movement.'
Format your response as a JSON object with each topic as the keys and 0 or 1 as values. Add the "other" key to list potential topics not listed above. Use an array as a value.

Input
Description: 
Article's headline
Article's text preview

Column: 
Headlines
Description

Example
Article's headline
Nutella maker Ferrero in race to buy Campbell's international business
Manofi poaches former PSA finance boss Chasseloup de Chatillon

Article's text preview
Ferrero SpA is interested in buying Campbell Soup Co's international business, which includes biscuit brand Arnott's, two sources close to the matter said on Monday.
French drugmaker Sanofi announced it had hired Jean-Baptiste Chasseloup de Chatillon, the former chief financial officer at carmaker and Peugeot-manufacturer PA who had helped oversee a revival in PA's fortunes.

Output
{ "company and product news": 1, "corporate debt and earnings": 0, "IPO": 0, "M&A and investments": 1, "stock movement": 0, "markets": 0, "legal and regulation": 0, "politics": 0, "currencies": 0, "gold and metals": 0, "energy and oil"; 0, "fed and central banks": 0, "other": [] }
{ "company and product news": 1, "corporate debt and earnings": 0, "IPO": 0 "M&A and investments": "stock movement": 0, "markets": 0, "'legal and regulation": 0, "politics": 0 "currencies": 0, "gold and metals": 0, "energy and oil": 0, "fed and central banks": 0, "other": ["hiring", "personnel change", "automotive"] }

![image](https://github.com/apj-dataiku/apj-workshop/assets/157776493/2c84ebc9-87b7-4caf-bd86-db936c18e59e)


