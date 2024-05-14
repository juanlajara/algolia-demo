# Best Buy Product Search with Algolia

## Project Overview

This project is part of a take-home assignment for a Solutions Engineer role at Algolia. The objective was to create a search interface using Algolia's search engine, showcasing my ability to index data, configure relevance settings, and build an intuitive user interface. For this project, I utilized Best Buy's Product Catalog dataset and implemented several features to enhance the search experience.

## Dataset

The dataset used is the Best Buy Product Catalog, which contains detailed information about various products sold by Best Buy, including product names, brands, descriptions, prices, and popularity rankings.

## Steps Taken

### 1. Indexing the Data

- **Algolia Account**: Created an Algolia account to access the indexing and search capabilities.
- **Data Indexing**: Indexed the Best Buy Product Catalog data using Algolia's dashboard. The data was uploaded and structured to ensure efficient searching and retrieval.

### 2. Configuring Relevance Settings

- **Searchable Attributes**: Configured the search to prioritize the following fields:
  - **Name**: Highest priority to ensure that products with the search term in their name appear first.
  - **Brand**: Secondary priority to allow users to find products by brand.
  - **Description**: Lower priority but included to enhance the search results by considering product descriptions.
- **Unsearchable Attributes**: Deliberately excluded fields like image links to avoid irrelevant matches.

### 3. Ranking and Sorting

- **Custom Ranking**: Set up a ranking and sorting system to prioritize search results based on:
  - **Popularity**: Most popular items appear first.
  - **Rank**: Items with higher customer ratings are prioritized.
  - **Price**: Higher-priced items are given a slight preference to promote products with a potentially higher profit margins.

### 4. Faceting and Filtering

- **Facets**: Created facets for price, rating, and brand.
  - **Price**: Added a range slider to filter products by price range.
  - **Rating**: Implemented a rating menu to filter products based on customer ratings.
  - **Brand**: Added a refinement list to filter products by brand.

### 5. Building the User Interface

- **InstantSearch Library**: Utilized Algolia's InstantSearch library to build the search interface.
- **UI Components**: Integrated various UI components to enhance user experience, including search box, filters, and result display.

### 6. Publishing the Project

- **GitHub Repository**: The project code is available in a publicly accessible GitHub repository.
- **GitHub Pages**: Published the project using GitHub Pages for easy interaction and demonstration.

### 7. Admin Access

- **Admin Access**: Granted Algolia admins access to the indexed data and relevance settings to facilitate review and feedback.

## Project Goals

The primary goal of this project was to demonstrate my ability to work with Algolia's search engine and create a user-friendly search interface. I aimed to provide a seamless and efficient search experience for users, ensuring that they can easily find products based on relevance, popularity, and other important criteria.

## Feedback for Algolia

Working on this project provided valuable insights into the capabilities and flexibility of Algolia's search platform. Here are some key takeaways and feedback:

- **User-Friendly Dashboard**: The Algolia dashboard is intuitive and easy to navigate, making the process of indexing data and configuring settings straightforward.
- **Documentation**: The comprehensive documentation and examples provided by Algolia were instrumental in understanding and implementing various features.
- **Relevance Tuning**: The ability to fine-tune relevance settings and ranking criteria allowed for a highly customizable search experience.
- **Faceting and Filtering**: The faceting and filtering options were powerful and enabled the creation of a dynamic and interactive search interface.

## Conclusion

This project showcases a robust and user-centric search interface built using Algolia's search engine. By focusing on relevance, ranking, and filtering, I aimed to provide an optimal search experience for users interacting with Best Buy's product catalog.

You can interact with the project [here](https://juanlajara.github.io/algolia-demo/).

## ais-ecommerce-demo-app

_This project was generated with [create-instantsearch-app](https://github.com/algolia/instantsearch/tree/master/packages/create-instantsearch-app) by [Algolia](https://algolia.com)._

## Run this project locally

To run this project locally, install the dependencies and run the local server:

```sh
npm install
npm start
```

Alternatively, you may use [Yarn](https://http://yarnpkg.com/):

```sh
yarn
yarn start
```

Open http://localhost:3000 to see your app.
