# Regionaal-Datateam
In het landsdeel Noord-Holland/Flevoland is het Regionaal Datateam (RDT) actief om wegbeheerders te ondersteunen in de digitaliserings-opgave mobiliteit. Er is een data Top 15 (https://www.datapedia.nl/datatop15/nodes/datatop15) opgesteld met prioritaire datathema's die op orde gebracht dienen te worden. Als onderdeel hiervan heeft [Analyze](https://analyze.nl/) een aantal use-cases ontwikkeld die wegbeheerders ondersteunen in hun werkzaamheden, en concrete meerwaarde genereren uit de prioritaire datathema's en daarmee stimuleren om de datakwaliteit te verhogen/bij te houden.

De scripts in dit project vormen de basis van een [dashboard](https://app-bereikbaarheid-poc-001.azurewebsites.net/) met uitgewerkte use-cases. Wil je toegang tot het dashboard? Neem dan contact op het met Kernteam Data en Digitalisering van [MRA Smart Mobility](https://smartmobilitymra.nl/over-ons/ons-netwerk/), of met [Analyze](https://analyze.nl/).

# Structuur
API calls om data in te lezen zijn geschreven in Python en de data wordt weggeschreven naar een PostgreSQL database, waarna PostGIS gebruikt kan worden voor de geospatiale analyse. De notebooks zijn geschreven in Azure Synapse te draaien, daarom worden de PostGIS queries via Python aangeroepen. Desgewenst kunnen de PostGIS queries rechtstreeks op de database gedraaid worden.

# Credits
Dit project is begonnen als een opschaling van https://bereikbaarheid.amsterdam.nl/