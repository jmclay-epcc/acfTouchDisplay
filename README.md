This is an interactive replacement for the museum display at the ACF.  The scope currently is simple:-
- Create a timeline of all the systems that the ACF has had (just port over the current display basically)
- Make is so that you can click them and they show you a little information

This is just going to be a HTML page.  I don't see any point in making it more complicated than that right now.  I think ideally I'd like to structure is to that there is a directory with both the system info and images:-

>systems
  >archer2
    >archer2.txt
    >archer2.png

Were archer2.txt would look like:-

+----------------------+
|name: Archer 2        |
|year: whatever        |
|                      |
|stat1: wow!           |
|stat2: wee!           |
|stat3: gosh!          |
|stat4: big numbers!   |
+----------------------+

The HTML page then checks that directory and populates the webpage itself on startup.  That way you can add or remove systems without needing to change the HTML or page styling itself.  
