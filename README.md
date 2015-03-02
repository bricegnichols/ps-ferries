# ps-ferries
Example web service providing list of current and retired ferry boats operating in the Puget Sound.

Two lists of ferry boats are provided, retired and current vessels. The data is contained in csv and json formats in this repo and served up by a simple php file (api.php) by the single HTML file (index.hmtl). For both the current and retired data, the following fields are available for each ferry vessel:

- Ferry name
- Ferry class (essentially a boat type, representing a size and construction or service era)
- Automobile capacity
- Passenger Capacity
- General notes about the ship

Additionally, a photo of the ship is provided when available as a direct link to a third party host. 

The data is from [Wikipedia] (http://en.wikipedia.org/wiki/Washington_State_Ferries) with slight editing for brevity. 
