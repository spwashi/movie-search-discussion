# Glossary

Terms and definitions for the Search-by Title Feature

## Movie Enthusiast

### Definitions
- Our target audience
- Any person who has seen (or expressed interest in) enough [movies or shows](#movies-or-shows) that they'd search for multiple titles using this API.

## Movies or Shows

### Synonyms
- A work
  - Notes:
    - This only holds in contexts where it's assumed that only Movies or Shows are being referenced. Outside those contexts, it is ambiguous.

### Definitions
- An entity having a [Title] and a [set of data] that often correspond to information found on IMDB, Metacritic, and Rotten Tomatoes

### Sub-terms
- Title
  - The title that can most uniquely identify a given resource
    - Notes:
      - It might not always be possible to uniquely reference a work by title. 
      - We should consider adding a "search by IMDB ID" feature.
- Set of Data
  - A set of information including the following attributes:
    - Title
    - Directors (optional)
    - Genres (optional)
    - Poster (optional)
    - [...]