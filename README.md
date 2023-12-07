# Google Search Operators 
### Documentation for Developers

---

<div align="center">
  <img src="https://kinsta.com/wp-content/uploads/2021/06/how-to-change-search-engine-1024x512.png" alt="Search Engines" width="800"/>
</div>

## Introduction
Searchengine Operators are special characters and commands that extend the capabilities of a regular text search. They can be used to refine and filter search results to find more specific information. The most commonly used operators are from Google, but other search engines also support most of these operators. 
This documentation provides a comprehensive list of Google Search Operators, along with their syntax, examples, and descriptions.

## General Information how Operators work
Where to use operators:
* in the search bar of the browser
* in the search bar of a search engine
<br>
*Note: not all search engines support operators or use other operators*
<br>
*Note 2: some websites may use operators for their own search function, but this documentation is only about search engines*

How to use operators:
* operators don't need to follow a specific order (e.g. c# function filetype:pdf is the same as filetype:pdf c# function)
* operators can be combined (e.g. c# function filetype:pdf OR filetype:docx)

<details>
  <summary>

  ## How to use this documentation
  </summary>

This documentation is divided into sections based on the type of operator. 

Have a look at Table of Contents down below:
All operators are listed in the table of contents. 

The most commonly used operators are listed first in a table for quick reference.
After that comes a section with examples of how to use operators in real world scenarios. (This section is still work in progress)

After that comes a section with a cheat sheet for all operators.

For more exlanation on the operator itself, there is a section for each operator that consists of a description, syntax, and examples.
Ever examples is a link to Google searche, so you can try it out yourself without having to copy and paste the query.
</details>

## Disclaimer
This documentation is not affiliated with Google or any other search engine. It is intended for educational purposes only.
Content is based on publicly available information and may be subject to change.

## How to contribute
If you want to contribute to this documentation or have any suggestions or mistakes to report, please open an issue.

Please star this repository if you find it useful and share it with your friends and colleagues - thank you :)

---

## Table of Contents
1. [Commonly Used](#commonly-used)
2. [Examples](#examples)
3. [Cheat Sheet](#cheat-sheet)
4. <details>
    <summary>
      Basic Operators
    </summary>
  
    * [Quotation Marks](#quotation-marks)
    * [Minus Operator](#minus-operator)
    * [Wildcard Operator](#wildcard-operator)
    * [Grouping Operator](#grouping-operator)
    * [OR Operator](#or-operator)
    * [AND Operator](#and-operator)
      
  </details>
  
5. <details>
    <summary>
      Content searching Operators
    </summary>

    * [intitle:](#title-search-intitle)
    * [intext:](#content-search-intext)
    * [filetype: or ext:](#filetype-or-extension-search)
    * [allintext:](#all-text-search)
    * [allintitle:](#all-title-search)
    * [AROUND(X)](#proximity-search-aroundx)
      
  </details>
  
6. <details>
    <summary>
      Website searching Operators
    </summary>

    * [site:](#website-search-site)
    * [related:](#related-sites-search-related)
    * [inurl:](#url-search-inurl)
    * [allinurl:](#all-in-url-search-allinurl)
    * [cache:](#webpage-cache-search-cache)
      
  </details>
  
7. <details>
    <summary>
      Specific Operators
    </summary>
    
    * [in:](#unit-conversion-in)
    * [define:](#word-or-phrase-definition-define)
    * [weather:](#weather-search-weather)
    * [stocks:](#stock-information-search-stocks)
    * [map:](#map-search-map)
    * [movie:](#movie-information-search-movie)
    * [source:](#news-source-search-source)
    * [before:](#date-based-search-before-and-after)
    * [after:](#date-based-search-before-and-after)
    * [location:](#location-based-news-search-location)
    * [daterange:](#date-range-search-daterange)
      
  </details>
  
8. [Summary](#summary)
9. [Resources](#resources)
---
 
## Commonly Used
| Operator | Syntax | Description |
| --- | --- | --- |
| filetype: or ext: |`filetype:` or `ext:` | Search for specific types of files. |
| intext: | `intext:` | Search for pages with a particular word in their content. |
| site: | `site:` | Search for results from a particular website. |
| OR | `OR` or `\|` | Search for results related to X or Y. |
| AND | `AND` | Search for results related to X and Y. |
| Grouping | `( )` | Combine multiple operators for complex queries. |


## Examples

### Combine multiple operators for complex queries.

Real world examples and use cases for comples queries will be added here.

If you have a good example, please open a issue and add your example in the description.


## Cheat Sheet

### Basic Operators

| Operator | Syntax | Example | Description |
| --- | --- | --- | --- |
| Quotation Marks | `""` | ["Java Spring Framework"](https://www.google.com/search?q="Java+Spring+Framework") | Search for an exact word or phrase. |
| Minus Operator | `-` | [C# -Unity](https://www.google.com/search?q=C%23+-Unity) | Exclude results that mention a word or phrase. |
| Wildcard Operator | `*` | [Python * library](https://www.google.com/search?q=Python+*+library) | Match any word or phrase. |
| Grouping Operator | `( )` | [(Java OR Kotlin) REST API](https://www.google.com/search?q=(Java+OR+Kotlin)+REST+API) | Combine multiple operators for complex queries. |
| OR Operator | `OR` or `\|` | [Servermanager Java OR Python](https://www.google.com/search?q=Servermanager+Java+OR+Python) | Search for results related to X or Y. |
| AND Operator | `AND` | [Node.js AND Express](https://www.google.com/search?q=Node.js+AND+Express) | Search for results related to X and Y. |


### Content Search

| Operator | Syntax | Example | Description |
| --- | --- | --- | --- |
| intitle: | `intitle:` | [intitle:\"React.js documentation\"](https://www.google.com/search?q=intitle:%22React.js+documentation%22) | Search for pages with a particular word in the title tag. |
| intext: | `intext:` | [intext:\"Docker containerization\"](https://www.google.com/search?q=intext:%22Docker+containerization%22) | Search for pages with a particular word in their content. |
| filetype: or ext: |`filetype:` or `ext:` | [C++ filetype:pdf](https://www.google.com/search?q=C%2B%2B+filetype:pdf) | Search for specific types of files. |
| allintext: | `allintext:` | [allintext:\"Ruby performance tips\"](https://www.google.com/search?q=allintext:%22Ruby+performance+tips%22) | Search for pages with multiple words in their content. |
| allintitle: | `allintitle:` | [allintitle:Java best practices](https://www.google.com/search?q=allintitle:Java+best+practices) | Search for pages with multiple words in the title tag. |
| AROUND(X) | `AROUND(X)` | [REST AROUND(4) design](https://www.google.com/search?q=REST+AROUND(4)+design) | Search for pages with two words or phrases within X words of one another. |


### Website Search

| Operator | Syntax | Example | Description |
| --- | --- | --- | --- |
| site: | `site:` | [site:stackoverflow.com](https://www.google.com/search?q=site:stackoverflow.com) | Search for results from a particular website. |
| related: | `related:` | [related:docs.python.org](https://www.google.com/search?q=related:docs.python.org) | Find sites related to a given domain. |
| inurl: | `inurl:` | [inurl:github](https://www.google.com/search?q=inurl:github) | Search for pages with a particular word in the URL. |
| allinurl: | `allinurl:` | [allinurl:AWS tutorial](https://www.google.com/search?q=allinurl:AWS+tutorial) | Search for pages with multiple words in the URL. |
| cache: | `cache:` | [cache:nginx.org](https://www.google.com/search?q=cache:nginx.org) | Find the most recent cache of a webpage. |


### Specific Operators

| Operator | Syntax | Example | Description |
| --- | --- | --- | --- |
| in: | `in` | [$500 in GBP](https://www.google.com/search?q=%24500+in+GBP) | Convert one unit to another. |
| define: | `define:` | [define:SQL](https://www.google.com/search?q=define:SQL) | Search for the definition of a word or phrase. |
| weather: | `weather:` | [weather:Seattle](https://www.google.com/search?q=weather:Seattle) | Search for the weather in a location. |
| stocks: | `stocks:` | [stocks:GOOGL](https://www.google.com/search?q=stocks:GOOGL) | Search for stock information for a ticker. |
| map: | `map:` | [map:server conference](https://www.google.com/search?q=map:server+conference) | Force Google to show map results. |
| movie: | `movie:` | [movie:\"The Matrix\"](https://www.google.com/search?q=movie:%22The+Matrix%22) | Search for information about a movie. |
| source: | `source:` | [Python source:realpython.com](https://www.google.com/search?q=Python+source:realpython.com) | Search for results from a particular source in Google News. |
| before: | `before:` | [Java before:2022-01-01](https://www.google.com/search?q=Java+before:2022-01-01) | Search for results from before a particular date. |
| after: | `after:` | [C# after:2022-01-01](https://www.google.com/search?q=C%23+after:2022-01-01) | Search for results from after a particular date. |
| location: | `location:` | [location:\"Silicon Valley\" cloud technology](https://www.google.com/search?q=location:%22Silicon+Valley%22+cloud+technology) | Find news from a certain location in Google News. |
| daterange: | `daterange:` | [Node.js daterange:11278-13278](https://www.google.com/search?q=Node.js+daterange:11278-13278) | Search for results from a particular date range. |

<details open>
<summary>
  
  ## Basic Operators
</summary>

#### Quotation Marks:

The Quotation Marks operator is used to search for an exact word or phrase. It is particularly useful when you want to find results that contain the specified words in the exact order they are enclosed within the quotation marks.

*Syntax:* `""`

*Example:* ["Java Spring Framework"](https://www.google.com/search?q="Java+Spring+Framework")

*Description:*
Search for an exact word or phrase.

---

#### Minus Operator:

The Minus Operator is used to exclude results that mention a specific word or phrase. This is helpful when you want to refine your search by excluding certain terms.

*Syntax:* `-`

*Example:* [C# -Unity](https://www.google.com/search?q=C%23+-Unity)

*Description:*
Exclude results that mention a word or phrase that is written after the minus.

---

#### Wildcard Operator:

The Wildcard Operator, represented by `*`, is used to match any word or phrase. It is useful when you want to search for variations of a term or when you are unsure about specific details.

*Syntax:* `*`

*Example:* [Python * library](https://www.google.com/search?q=Python+*+library)

*Description:*
The Wildcard Operator allows for flexibility in your search by matching any word or phrase in the specified position.

---

#### Grouping Operator:

The Grouping Operator, represented by `( )`, allows you to combine multiple operators to create complex queries. It is useful for creating logical combinations of search terms.

*Syntax:* `( )`

*Example:* [(Java OR Kotlin) REST API](https://www.google.com/search?q=(Java+OR+Kotlin)+REST+API)

*Description:*
By using the Grouping Operator, you can create more sophisticated search queries by specifying the logical relationships between different terms. 
**EXAMPLE:** [Combine multiple operators for complex queries.](#examples)

---

#### OR Operator:

The OR Operator, represented by `OR` or `|`, is used to search for results related to either X or Y. It broadens the search by including pages that contain either of the specified terms.

*Syntax:* `OR` or `|`

*Example:* [Servermanager Java OR Python](https://www.google.com/search?q=Servermanager+Java+OR+Python)

*Description:*
When using the OR Operator, the search results will include pages that contain either of the specified terms, helping to extend your search.
**EXAMPLE:** [Search for results related to X or Y.](#examples)

---

#### AND Operator:

The AND Operator, represented by `AND`, is used to search for results related to both X and Y. It narrows down the search by including only pages that contain both of the specified terms.

*Syntax:* `AND`

*Example:* [Node.js AND Express](https://www.google.com/search?q=Node.js+AND+Express)

*Description:*
When using the AND Operator, the search results will only include pages that contain both specified terms, helping to refine and focus your search.
**EXAMPLE:** [Search for results related to X and Y.](#examples)

</details>

<details open>
<summary>
  
  ## Content Search
</summary>

#### Title Search (intitle):

The intitle operator is used to search for pages with a particular word in the title tag. This can be handy when you want to find web pages where a specific term is included in their title.

*Syntax:* `intitle:`

*Example:* [intitle:"React.js documentation"](https://www.google.com/search?q=intitle:%22React.js+documentation%22)

*Description:*
Search for pages with a particular word in the title tag.

---

#### Content Search (intext):

The intext operator is used to search for pages with a particular word in their content. This is useful when you want to find pages that contain a specific term within their textual content.

*Syntax:* `intext:`

*Example:* [intext:"Docker containerization"](https://www.google.com/search?q=intext:%22Docker+containerization%22)

*Description:*
Search for pages with a particular word in their content.

---

#### File Type or Extension Search:

The filetype: or ext: operators are used to search for specific types of files. This is beneficial when you are looking for files with a particular extension, such as PDF, to find documents.

*Syntax:* `filetype:` or `ext:`

*Example:* [C++ filetype:pdf](https://www.google.com/search?q=C%2B%2B+filetype:pdf)

*Description:*
Search for specific types of files. This is beneficial when you are looking for files with a particular extension, such as PDF, Word, or Excel files.

List of supported file types: https://support.google.com/webmasters/answer/35287?hl=en

---

#### All Text Search (allintext):

The allintext operator is used to search for pages that contain multiple words within their content. It helps narrow down results to pages where all specified terms appear in the textual content.

*Syntax:* `allintext:`

*Example:* [allintext:"Ruby performance tips"](https://www.google.com/search?q=allintext:%22Ruby+performance+tips%22)

*Description:*
Search for pages with multiple matching words in their content.

---

#### All Title Search (allintitle):

The allintitle operator is used to search for pages with multiple words in the title tag. It helps refine your search to pages where all specified terms are included in the title.

*Syntax:* `allintitle:`

*Example:* [allintitle:Java best practices](https://www.google.com/search?q=allintitle:Java+best+practices)

*Description:*
Search for pages with multiple matching words in the title tag.

---

#### Proximity Search (AROUND(X)):

The AROUND(X) operator is used to search for pages with two words or phrases within X words of one another. It helps find content where specific terms are in close proximity, providing more contextually relevant results.

*Syntax:* `AROUND(X)`

*Example:* [REST AROUND(4) design](https://www.google.com/search?q=REST+AROUND(4)+design)

*Description:*
Search for pages with two words or phrases within X words of one another, e.g. REST AROUND(4) design will find pages where REST and design are within 4 words of each other.


</details>

<details open>
<summary>
  
  ## Website Search
</summary>

#### Website Search (site:):

The site: operator is used to search for results from a particular website. It helps narrow down your search to pages that belong to a specific domain.

*Syntax:* `site:`

*Example:* [site:stackoverflow.com](https://www.google.com/search?q=site:stackoverflow.com)

*Description:*
Search for results from a particular website.

---

#### Related Sites Search (related):

The related: operator is used to find sites related to a given domain. It helps identify websites that share similarities or are associated with a specified domain.

*Syntax:* `related:`

*Example:* [related:docs.python.org](https://www.google.com/search?q=related:docs.python.org)

*Description:*
Find sites related to a given domain.

---

#### URL Search (inurl):

The inurl: operator is used to search for pages with a particular word in the URL. It helps find pages where the specified term is part of the web address.

*Syntax:* `inurl:`

*Example:* [inurl:github](https://www.google.com/search?q=inurl:github)

*Description:*
Search for pages with a particular word in the URL.

---

#### All-in-URL Search (allinurl):

The allinurl: operator is used to search for pages with multiple words in the URL. It helps refine your search to pages where all specified terms are part of the web address.

*Syntax:* `allinurl:`

*Example:* [allinurl:AWS tutorial](https://www.google.com/search?q=allinurl:AWS+tutorial)

*Description:*
Search for pages with multiple words in the URL.

---

#### Webpage Cache Search (cache):

The cache: operator is used to find the most recent cache of a webpage. It helps access a snapshot of a page as stored by Google.

*Syntax:* `cache:`

*Example:* [cache:nginx.org](https://www.google.com/search?q=cache:nginx.org)

*Description:*
Find the most recent cache of a webpage. If not working, try [Wayback Machine](https://archive.org/web/).


</details>

<details open>
<summary>
  
  ## Specific Operators
</summary>

#### Unit Conversion (in:):

The in: operator is used to convert one unit to another. It is handy when you need to convert measurements or currencies.

*Syntax:* `in`

*Example:* [$500 in GBP](https://www.google.com/search?q=%24500+in+GBP)

*Description:*
Convert one unit to another.

---

#### Word or Phrase Definition (define:):

The define: operator is used to search for the definition of a word or phrase. It helps provide quick access to the meaning of specific terms.

*Syntax:* `define:`

*Example:* [define:SQL](https://www.google.com/search?q=define:SQL)

*Description:*
Search for the definition of a word or phrase.

---

#### Weather Search (weather:):

The weather: operator is used to search for the weather in a particular location. It provides current weather conditions for the specified area.

*Syntax:* `weather:`

*Example:* [weather:Seattle](https://www.google.com/search?q=weather:Seattle)

*Description:*
Search for the weather in a location.

---

#### Stock Information Search (stocks:):

The stocks: operator is used to search for stock information for a specific ticker symbol. It provides stock market details for the specified company.

*Syntax:* `stocks:`

*Example:* [stocks:GOOGL](https://www.google.com/search?q=stocks:GOOGL)

*Description:*
Search for stock information for a ticker.

---

#### Map Search (map:):

The map: operator is used to force Google to show map results for a specified location or event.

*Syntax:* `map:`

*Example:* [map:server conference](https://www.google.com/search?q=map:server+conference)

*Description:*
Force Google to show map results.

---

#### Movie Information Search (movie:):

The movie: operator is used to search for information about a movie. It provides details about the specified film.

*Syntax:* `movie:`

*Example:* [movie:"The Matrix"](https://www.google.com/search?q=movie:%22The+Matrix%22)

*Description:*
Search for information about a movie.

---

#### News Source Search (source:):

The source: operator is used to search for results from a particular source in Google News. It helps filter news articles from a specified news outlet.

*Syntax:* `source:`

*Example:* [Python source:realpython.com](https://www.google.com/search?q=Python+source:realpython.com)

*Description:*
Search for results from a particular source in Google News.

---

#### Date-Based Search (before: and after:):

The before: and after: operators are used to search for results from before or after a particular date. They help filter search results based on temporal criteria.

*Syntax:* `before:` and `after:`

*Example:* [Java before:2022-01-01](https://www.google.com/search?q=Java+before:2022-01-01)

*Description:*
Search for results from before or after a particular date.

---

#### Location-Based News Search (location:):

The location: operator is used to find news from a certain location in Google News. It helps filter news articles based on a specified geographical location.

*Syntax:* `location:`

*Example:* [location:"Silicon Valley" cloud technology](https://www.google.com/search?q=location:%22Silicon+Valley%22+cloud+technology)

*Description:*
Find news from a certain location in Google News.

---

#### Date Range Search (daterange:):

The daterange: operator is used to search for results from a particular date range. It helps filter search results based on a specified time interval.

*Syntax:* `daterange:`

*Example:* [Node.js daterange:11278-13278](https://www.google.com/search?q=Node.js+daterange:11278-13278)

*Description:*
Search for results from a particular date range.

</details>

---

## Summary

This documentation provides a comprehensive list of Google Search Operators, along with their syntax, examples, and descriptions.

Thanks for reading!

[Back to top](#google-search-operators)

## Resources

Thanks to the following resources for providing information and inspiration for this documentation:
* [AHREFS](https://ahrefs.com/blog/google-advanced-search-operators/)
* [Search Engine Land](https://searchengineland.com/advanced-google-search-operators-388355)
* [Google](https://support.google.com/websearch/answer/2466433?hl=en)
