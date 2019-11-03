# A frontend technical challenge

**Hello candidate,**

This repository serves as a plain, forkable starting point for your frontend technical challenge.

In this challenge you will create an interface that can search through a list of items and display relevant results. The items will be retrieved via a read-only API that will return a JSON feed of the [most popular New York Times science articles](https://api.nytimes.com/svc/topstories/v2/science.json?api-key=Gwxln5M3geWlhR6UE0TY1FUWKSG3wCil).

The [index.html](./index.html) file within this repository provides a vanilla AJAX example of how to retrieve articles. You can see this example running here:  
<https://shopthrilling.github.io/tech-challenge/>

Your challenge solution should aim to fulfill the following:
- Provide an input for search terms.
- Upon submission of a search term, dynamically display a link to the relevant article/s.
  - Search terms should match against the following article attributes:
    - title
    - section
    - byline
  - Search terms should be case insensitive.
    - e.g. the search term "kenneth chang" should return an article with the byline "KENNETH CHANG"
  - Search terms should match regardless of the order they are entered.
    - e.g. the search terms "meat growing" or "lab mush" should return an article with the title "Growing Meat in a Lab That Doesn’t Look Like Mush"

In addition to the requirements above you can choose from the following additional features to implememnt if time permits:
- Sort results by relevance.
- Implement your solution using a modern library or framework.
- Implement typeahead search.
- Implement approximate string matching, aka fuzzy search.
- Make it pretty.
- Include an easter egg that, if found, would be impressive and/or entertaining :)

You should spend at most 2 hours on this challenge. Start by forking this repo. When you're finished send a link to your public fork. Ideally your code will run via GitHub Pages, directly from the repo.

**Best of luck!**
