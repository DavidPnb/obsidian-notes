up:: [[+ Index for index notes]]
tags:: #x/index

# Index for Cards

``` dataview
TABLE tags FROM "Cards" and -#x/index and -"People" and -#x/readme
SORT file.name ASC

```

```dataview
TABLE dates
FROM "Cards" and -#index
GROUP BY file.folder

```