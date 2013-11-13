## Tongva Park Plants
This dataset is the result of merging the GPS bounds of the various "hills" of Tongva Park with plants known to reside in those areas, grouped by the "type" of plant (e.g. Bulbs, Grasses).

### Data structure
We add an addional member, `PlantTypes`, to the Feature collection for each area, as in the following example:

    "PlantTypes": [{
		"Type": "Bulbs",
		"Plants": [{
			"Location": "Observation Hill",
			"Type": "Bulbs",
			"LatinName": "Crinum bulbispermum",
			"CommonName": "Corn Lily",
			"ThumbnailURL": "http://www.smgov.net/.../thumb_abc.jpg",
			"ImageURL": "http://www.smgov.net/.../abc.jpg"
		},
		{
			"Location": "Observation Hill",
			"Type": "Bulbs",
			"LatinName": "Zephyranthes candida",
			"CommonName": "Fairy Lily",
			"ThumbnailURL": "http://www.smgov.net/.../thumb_xyz.jpg",
			"ImageURL": "http://www.smgov.net/.../xyz.jpg"
		}]
	},
	{
		"Type": "Palms and Cycads",
		"Plants": [{
			"Location": "Observation Hill",
			"Type": "Palms and Cycads",
			"LatinName": "Dioon spinulosum",
			"CommonName": "Giant Dioon",
			"ThumbnailURL": "http://www.smgov.net/.../thumb_123.jpg",
			"ImageURL": "http://www.smgov.net/.../123.jpg"
		}]
	}]
