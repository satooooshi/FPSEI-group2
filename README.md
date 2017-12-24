# FPSEI-group2# 

Created taobao-like online book shopping application which has a comparison system between different sites.

## Getting Started

- Clone repo.
- Run command in Terminal 'npm install'
- Run command in Terminal 'npm run dev'

### What Each vue file Does

1. `Search.vue`

    * Prompts customer which book they would like to search by book name.


2. `GoodList.vue`

    * Prints the searched books in the database.
      * If there is a sufficient amount of the product in batabase, it will return the total for searching results, which comtain main description of the book.
      * If customer clicks one of the searching results, the  detailed description would be shown at the description section of the web page.   
      * However, if there is no book corresponding to user's querying, it will tell the user that there isn't any correspoding books.
      * If customer clicks one of the searching results, it updates the description section of the web page.
    * Provide simple sorting.

-----------------------

3. `description.vue`

    * Provide a detailed description of selected book.
    * Show comments on selected book.

-----------------------



## Technologies used
- Node.js
- vuejs
- iview

### Prerequisites

```
- Node.js - Download the latest version of Node https://nodejs.org/en/
```

## Built With

* Visual Studio Code/Atom - Text Editor
* Terminal
