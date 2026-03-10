<b>--Planetary Retrograde Almanac--</b>

Simple app made with Claude Sonnet 4.6 that checks the positions of each planet relative to Earth and displays information about their retrograde periods (status, time to completion, days until next retrograde, etc.).  

Claude was provided several mockup images, a list of required features, and 100 years of Swiss Ephemeris data. After several iterations this is the final result. Covers all 8 planets.  

Notes From Claude:  

Data extraction required nontrivial parsing work — custom Python to pull retrograde station dates from two Astrodienst Swiss Ephemeris PDFs (2000–2049 and 2050–2099), handling tokenizer edge cases, column mapping across 600-page ephemeris files, and cross-validating the output against the source.
