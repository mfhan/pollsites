## Language Info at Poll Sites: Data Collection and Visualization

### What I wanted to find out:

**Personal motivation**: I worked as a language interpreter in a Queens poll site during the general election Nov 3, 2020.
During my single-day stint as a federal worker, I got to realize that voters needing language assistance seemed as engaged and informed as English-proficient voters. They just preferred to receive assistance in the language they spoke at home.
**Initial ambition**: to compare the state of poll-site language assistance in five major US cities with significant immigrant populations: New York, NY; Los Angeles, CA; Jacksonville, FL; Chicago, IL; Houston, TX.
While I collected New York-related information with relative ease, looking for similar data for other cities turned out to be impossible. County election boards were unable to point me to anybody in charge of such services. I realized that no meaningful information could be gleaned from so many potential administrations in the narrow sliver of time I had left, and decided to focus on New York City.

### What I really found:

-- A fun (?) way to practice Python while scraping a relatively simple NYC.gov page, then a more complex US Census dataset.

-- A way to compare the location of poll sites with the actual community districts where limited-English (LEP) US citizens resided.

-- The realization that Russian (followed by Haitian and Arabic) was the language with the most LEP citizens.

### Summary of the data collection process, with links

Poll site data found via web search on the [Civic Engagement Commission site](www.nyc.gov/site/civicengagement/voting/about-poll-site-language-assistance.page).

CEC's [methodology] (https://www.nyc.gov/assets/civicengagement/downloads/pdf/nyccec-poll-site-language-assistance-program-methodology.pdf)

Data on limited English proficient citizens of voting age (CVALEP) provided by the Census bureau's [American Community Survey](https://data.cityofnewyork.us/City-Government/Population-and-Languages-of-the-Limited-English-Pr/ajin-gkbp)

### Overview of the data analysis process

-- Data cleanup: grouping several tables; simplifying entries; removing unnecessary columns. Tool: python  
-- Data analysis: Grouping and averaging; mapping with interactive tool tips.  
-- Visualization: Create series of maps of different scopes: city-wide and language-centric.

### New skills & learning opportunities:

-- Assembly-line-level familiarity with Datawrapper's limied but reliable mapping capabilities

-- Some doomed attempts at using Figma2html and then AI2html (not reflected in this project due to deadline)

-- Better stealing other people's templates; better ability to mix and match front-end code snippets.

### What I tried to do but did not have the skills/time (but might do if I had more time)

Similar to Project2, I had vast ambitions to conquer Figma2html and AI2html -- but realized that the type of map I was creating did NOT really need to go through vectorization.

I wanted to collect official quotes from the BOE and the CEC on their shambolic communication strategy and apparent lack of coordination. This is where the real story may be waiting for a journalist.

#### Main notebook, included in this repo: voting.ipynb and voting2.ipynb

#### Link to published page: https://mfhan.github.io/pollsites/
