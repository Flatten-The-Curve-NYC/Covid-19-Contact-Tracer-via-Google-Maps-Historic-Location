# Flatten The Curve NYC (now working with [CoronaTrace](https://github.com/Corona-Trace))

 We have joined forces with [CoronaTrace](https://github.com/Corona-Trace). Check out their repos and progress!



OLD
========

Our Vision
=====

Simple
-----
Use  everyone's already recorded location trails to bolster [contact tracing](https://en.wikipedia.org/wiki/Contact_tracing). Through better contact tracing, we can better deploy limited tests and improve containment policies -- [flattening the curve](https://en.wikipedia.org/wiki/Coronavirus_disease_2019#Prevention).

Our goal is that if we can be efficent with tracing contact,  containment, quarantine, and other measures that cut into our lives can slowly be rolled back while keeping people safe and healthy.

How?
-----
* Web App - Node.js (or other platform?)
  * Upload Google Timeline information (ideally automatic, but if not manually download .kml file from https://takeout.google.com/ and upload) 
  * Parse location data and disgard data before COVID-19 outbreak
  * Remove PII (personally identifiable information) before storing
  * Some PII will be readded by user (not from .kml info) so user can be contacted
  * Prove authenticity users - need to confirm the database doesn't get corrupted with fake information
  * User accounts will have COVID-19 infection status
  * If user becomes infected, they change their status 
  * If interactions with infected occured, all contacts with interactions are notified

Containment / Principles of Contact Tracing 
======
Containment is the best way to slow this epidemic. But for containment to be effective, it needs:
1. Rapid identification (and quarantine) of infected individuals, and 
1. Determining Close Contacts; the determination of whom they have had close contact within the previous days and weeks, and decontamination of locations the infected individual has visited. 

Rapid identification relies heavily on the availability of tests. Since virus testing is quite far out of our wheelhouse, we applaud all the companies that have moved quickly to make testing more ubiquitous and leave it at that!

On the other hand, determination of close contacts is something that we think software can have a big impact. With almost half of the world’s population carrying a device capable of GPS tracking, location trails – timestamped logs of an individual’s location -- are often automatically created. If you haven’t seen your Google Map’s location history check out: https://www.google.com/maps/timeline. 

By comparing a user’s location trails with those from diagnosed carriers of infectious disease, one can identify users who have been in close proximity to the diagnosed carrier and, if the exposed users take appropriate action, reduce the spread of the infectious disease. 

However, first-generation contact-tracing tools, deployed against the current 2019 novel Coronavirus (COVID-19) crisis, can also be – and have been – used to expand mass surveillance, limit individual freedoms and expose the most private details about individuals. Citizencentric, privacy-first solutions that are open-source, secure, and decentralized (such as MIT Private Kit: Safe Paths) represent the next generation of tools for disease containment in an epidemic or pandemic.

Note this section is heavily based on the white paper by MIT Private Kit: Safe Paths (http://privatekit.mit.edu/). 


New York’s Unique Challenge
======
Many of us are staying at home, and when out for essential reasons, we are following the CDC’s distancing guidelines, but in a city with almost 9 million people, contact with the infected is almost inevitable. 

Further compounding the issue is the anonymity of that contact. It is unlikely that a New Yorker would be able to recount all of the other people they came in contact with while picking up their prescriptions at Duane Reade or stocking up on groceries at Morton Williams. 

Isn't this being done?
=====
Sorta!
* [MIT Private Kit: Safe Paths](http://privatekit.mit.edu/)
* Rumors about Facebook and Google working on this. [The government might want your phone location data to fight coronavirus. Here’s why that could be okay.](https://www.vox.com/recode/2020/3/18/21184160/government-location-data-coronavirus)

Where Flatten The Curve NYC differs from MIT Private Kit: Safe Paths?
-------
[MIT Private Kit: Safe Paths](http://privatekit.mit.edu/) are forward looking location tracking. For MIT Private Kit, people will install and the location history commences from that point forward. 

We cannot afford to wait for that location history, and feel that with the wealth of existing location data (https://www.google.com/maps/timeline), we can expand on the principles and ideas espoused by MIT Private Kit: Safe Paths and make the adoption more ubiquitous.

The more location data of infected and uninfected individuals will make contact tracing more effective, enable better containment, and therefore flatten the curve in New York City.

Contributing
======
**In short - we want your help!** Check out our CONTRIBUTING.MD


Related Documents
======
* [Phones Could Track the Spread of Covid-19. Is It a Good Idea?](https://www.wired.com/story/phones-track-spread-covid19-good-idea/)
* [CoEpi: Community Epidemiology In Action](https://www.coepi.org/)
* [The government might want your phone location data to fight coronavirus. Here’s why that could be okay.](https://www.vox.com/recode/2020/3/18/21184160/government-location-data-coronavirus)

