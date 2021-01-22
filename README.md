The New York Times has this great interactive piece on the Hudson Yards' architecture. 
https://www.nytimes.com/interactive/2019/03/14/arts/design/hudson-yards-nyc.html

One of the main features throughout the piece is that they programmed a video to play that's synced with the user's scrolling. Then they superimpose text on top that corresponds with the segment of video that's playing. This is also a feature used often by the New York Times. 

I wanted to replicate that feature, so I looked up a tutorial on HTML5 scroll syncing. 
https://www.youtube.com/watch?v=HiegEfkenXA&ab_channel=DesignCourse

In this course, the instructor showed me how to sync the scrolling.

Essentially, we fix the video in place, and then superimpose text, which we individually contain and then write code concerning each "segment" of text. The height of the page is then determined by the length of the video. Then, whenever a certain amount of pixels scrolls by, a new event happens (the new event being another text segment comes up on top of the fixed video). The number of pixels needs to be manually set through trial and error so that the text will appear whenever it makes sense. Since there was no story that I was trying to tell, there's no real rhyme or reason to the placement of my text boxes. 

For future consideration:
- Make the video expand to the entire top and bottom of the screen, adapting to the browser window size.
- Add a storyline, create and add an original video. 
- Make the video sync up exactly with the final segment of text. 
