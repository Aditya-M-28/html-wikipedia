# HTML Wikipedia

A smaller and compact version of Wikipedia, that gives you information about anything, in a short and precise way.


## API Reference

https://www.mediawiki.org/wiki/API:Main_page

#### Initial Setup

- select form, input, results
- listen for submit events
- if empty value, display error
- create fetchPages()
- pass valid input value into the fetchPages()

#### Fetch Pages

- display loading while fetching
- construct dynamic url
- display if error
- display error no items
- create renderResults()
- pass valid results into renderResults()

#### Render Results

- iterate over the list
- pull out title, snippet, pageid
- setup a card
- set results with div.articles and list inside

## Tech Stack

HTML, CSS and JavaScript


## Screenshots

![Main Page](<Main Page-1.jpg>)

![Search Page](<Search Page-1.jpg>)

![Result Page](<Result Page-1.jpg>)

#### HTML Structure

- section.wiki
  - div.container
    - img
    - h3(text)
    - form.form
      - input.form-input type='text'
      - button.submit-btn (search) type='submit'
  - div.results
    - div.articles
      - a
        - h4
        - p (lorem20)
