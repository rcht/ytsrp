# rcht/ytsrp

YouTube Search Result Parser. Tool to get YouTube search results in the terminal without the need of a browser. 

# Dependencies

- BeautifulSoup(`bs4`) python library

# Examples

- Get the first link for the search term "cute dog video" on YouTube:

```
ytsrp -q "cute dog video"
```

- Get the first 23 video links for the search term "never gonna give you up":

```
ytsrp -q "never gonna give you up" -n 23
```

Currently, the value of the `-n` argument is limited to 29 because of the restriction that only a single page is parsed. 

- Get the first 4 links for the search term "world's shortest video" and print the title before every link:

```
ytsrp -q "world's shortest video" -n 4 --title
```
