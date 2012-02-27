www.repfinder.com

ATTRIBUTE VALUES:

id attribute values:
	id="cycle"
	id="piece"

class attribute values:
	class="songTitle"
	class="cycleTitle"
	class="idNumber"
	class="composerName"
	class="composerNationality"
	class="poetName"
	class="poetNationality"
	class="Key" 
	class="Range" (notated as MIDI numbers)
	class="instrumentation"
	class="textSource"
	class="language"
	class="genre"
	class="subGenre"
	class="character"
	class="subject"
	class="mood"
	class="tempoMarking" (notated as beats-per-measure)
	class="difficulty"
	class="inclusion"

rel attribute values: 
	rel="title"
	rel="cycle"
	rel="cycleSong"
	rel="idNumber"
	rel="composerName"
	rel="composerNationality"
	rel="poet"
	rel="poetNationality"
	rel="highKeyKey"
	rel="highKeyRange"
	rel="mediumKeyKey"
	rel="mediumKeyRange"
	rel="lowKeyKey"
	rel="lowKeyRange"
	rel="instrumentation"
	rel="textSource"
	rel="language"
	rel="genre"
	rel="subGenre"
	rel="character"
	rel="subject"
	rel="mood"
	rel="tempoMarking"
	rel="difficulty"
	rel="inclusion"
	
	
All www.repfinder.com resources:
	list of all songs
	list of songs with a given characteristic
	a single song
	list of all song cycles
	list of all song cycles with a given characteristic
	a single song cycle
	list of songs NOT part of a song cycle 
	list of songs that are part of any song cycle

	
NOTATION:

The URIs for all people (composers and poets) and works (songs, cycles, text sources) will be identified by Library of Congress Subject Heading (LCSH).

LCSH subject heading conversion to URI:
		all punctuation and spaces will be removed 
		all diacritics will be normalized (Ges&auml;nge or Gesänge = Gesaenge)
	examples:
		"Joyce, James, 1882-1941" becomes /JoyceJames18821941/
		"Barber, Samuel, 1910-1981. Nuvoletta" becomes /BarberSamuel19101981Nuvoletta/
		"Brahms, Johannes, 1833-1897. Gesänge, viola, piano acc., op. 91" becomes /BrahmsJohannes18831897Gesaengeviolapianoaccomp91/

The URIs for "range" will be notated in MIDI format (pitches are assigned numbers rather than letter names)

The URIs for "tempo marking" will be notated in beats-per-measure (BPM)


QUESTIONS:

Currently, almost all of the list items within a resource are links (because I want these classes to be searchable).
Not only do I not like how this looks when rendered in a browser, I find it unnecessary. 
How can I designate an item as searchable without giving it an href?

The search forms I created act as a sort of advanced search. 
Should I create a new resource for advanced search, or should I streamline these all to a free text search? 
How would that work? 
Would it be as functional?

I don't understand how GET, PUT, POST, and DELETE function within the context of this assignment. 
Since I have two root resources (allSongs.html and allCycles.html), how will I be able to specify whether a new POST will be a song or a cycle?