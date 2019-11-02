# A frontend technical challenge
 
**Hello candidate,**

This repository serves as a plain, forkable starting point for your frontend technical challenge.

In this challenge you will create an interface that can search a collection of items and display relevant results. The items will be retrieved via a read-only API that will return a JSON feed of collection products. The feed can be accessed by appending the query parameter `?view=tech_challenge` to any collection page on the ShopThrilling site, for example:  
<https://shopthrilling.com/collections/clothing?view=tech_challenge>

The [index.html](./index.html) file within this repositiory provides a vanilla AJAX example of how to retrieve products. You can see this example running here:  
<https://shopthrilling.github.io/tech-challenge/>

Your challenge solution should fulfill the following requirements:
- Provide an input for search terms.
- Upon submission of a search term, dynamically display relevant products from the Clothing collection.
  - Search terms should match against the product title and type.
  - Search terms should be case insensitive.
  - Search terms should match regardless of the order they are entered, for example the search term "dress green" should return a product with the title "Green Dress".

In addition to the requirements above you can choose from the following additional features to implememnt if time permits:
- Sort results by relevance.
- Implement your solution using a modern library or framework.
- Retrieve all paginated products, instead of just the first page of 100 results.
- Implement typeahead search.
- Make it pretty.
- Include an easter egg that, if found, would be impressive and/or entertaining :)

You should spend at most 2 hours on this challenge. Start by forking this repo. When you're finished send a link to your public fork. Ideally your code will run via GitHub Pages, directly from the repo.

**Best of luck!**
