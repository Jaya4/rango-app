# rango-app
Django web app

This repo can be used to create a website called Rango that lets users browse through user-defined categories to access various web pages.Om the main page of the site,visitors will be able to see:
        the 5 most viewed pages;
        the five most rango’ed categories; and
        some way for visitors to browse or search through categories.

When a user views a category page, rango would like it to display:
        the category name, the number of visits, the number of likes;
        along with the list of associated pages in that category (showing the page’s title and linking to its url); and.
        some search functionality (via Bing’s Search API) to find other pages that can be linked to this category.

For a particular category, rango will record the name of the category, the number of times each category page has been visited, and how many users have clicked the “like” button (i.e. the page gets rango’ed, and voted up the social hierarchy).

Each category should be accessible via a readable URL - for example, /rango/books-about-django/.

Only registered users will be able to search and add pages to categories. And so, visitors to the site must be able to register for an account.

