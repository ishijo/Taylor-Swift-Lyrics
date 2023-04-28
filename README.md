# Taylor Swift All Lyrics (42 Albums)

This dataset contains almost all (if not all) of **Taylor Swift** Albums' songs' lyrics (42 Albums currently). The format for the lyrics is completely textual (.txt format) to provide complete flexibility to the user 😊.

Each album has a different directory for itself.

Also a list of Albums csv file and one for all albums individually in the 'Tabular' directory provided.

#### Check the notebook to see how the data was extracted using the lyricsgenius python library here - 

# Albums:
42 Albums from Taylor Swift's discography, including 10 **studio** albums, and various **deluxe**, **live**, **re-recorded**, **language** editions and **remix** albums among many others.

1. Speak Now	
2. Taylor Swift	
3. Fearless	
4. Speak Now: World Tour Live	
5. Red	
6. 1989	
7. Fearless (Platinum Edition)	
8. Reputation	
9. Lover	
10. Speak Now (Deluxe)	
11. Folklore	
12. Evermore	
13. evermore (deluxe version)	
14. evermore: the dropped your hand while dancing chapter	
15. evermore (Japanese Edition)	
16. evermore: the “forever is the sweetest con” chapter	
17. the “ladies lunching” chapter	
18. Fearless (Taylor’s Version)	
19. Red (Taylor’s Version)	
20. Fearless (Taylor’s Version): The Halfway Out the Door Chapter	
21. Fearless (Taylor’s Version): The Kissing In The Rain Chapter	
22. Fearless (Taylor’s Version): The I Remember What You Said Last Night Chapter	
23. Fearless (Taylor’s Version): The From the Vault Chapter	
24. evermore (digitally autographed fan edition)	
25. Red (Taylor’s Version): Could You Be The One Chapter	
26. Red (Taylor’s Version): She Wrote A Song About Me Chapter	
27. Message In A Bottle (Fat Max G Remix) (Taylor’s Version) 	
28. Red (Taylor’s Version): The Slow Motion Chapter 	
29. Red (Taylor’s Version): From The Vault Chapter 	
30. the lakes - 7" Single (Record Store Day Exclusive)	
31. All Too Well (10 Minute Version) [The Short Film] - EP	
32. Carolina (From The Motion Picture “Where The Crawdads Sing”)	
33. Midnights	
34. Midnights (Target Exclusive)	
35. Midnights (Apple Music Exclusive) 	
36. Midnights (3am Edition)	
37. Anti-Hero (Remixes) 	
38. Lavender Haze (Remixes)	
39. The More Lover Chapter	
40. The More Fearless (Taylor’s Version) Chapter	
41. The More Red (Taylor’s Version) Chapter	
42. folklore: the long pond studio sessions (Record Store Day Exclusive)	

## Note:
### *(For reference regarding directory and file names)*

To convert the album names into the file name format, the following was used:

```python
album_dirname = re.sub('[^a-zA-Z0-9_]','_',''.join(album.split()))

```
```python
track_filename = re.sub('[^a-zA-Z0-9_]','_',''.join(track_name.split())) + '.txt'

```
# Inspiration:

 You can use the data to -
- Conduct a sentiment analysis of Taylor's songs
- Use as a data source for a creative project
- Make a word cloud 
- Analyse patterns in Taylor's lyrics

Hope this helped, have fun!

## Acknowledgements:
 This data has been collected frmo Genius through its API
