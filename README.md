timeline
========

a timeline project for collaborative use in courses

PROJECT NOTES:
A summary thus far:
1) I created a timeline with a free account at dipity.com, and my students have been inputting entries. The timeline is located at http://www.dipity.com/ebb8/Early-American-Literature/

2) I want to export this timeline so students can keep adding to it in future years. Dipity's free account only permits a limited number of entries, and it would be better if we could host the the timeline on a university server rather than rely on this .com which seems to have limited available tech support.

3) Getting the data from dipity.com isn't exactly easy. I've got passcode access to the developer API, but I'm not confident I can retrieve the complete entry data of my timeline this way based on dipity's developer documentation: http://www.dipity.com/developer/docs/rest

I need to investigate this further, because:

4) Accessing the timeline's RSS feed does not actually provide all the information the students input, but *does* include geodata we've entered that coordinates with Google Maps.

5) I can access the dates and my students' text entries from the source-code of the entry-by-entry view on the timeline. However, I don't appear to be able to access the links or video URL's this way. 

Solutions: I think I need to get into the developer API view and many need some help accessing the base file from command-line or via wget or curl. (The developer server isn't accessible via browser.)
OR if this fails, I may have to extract the info entry by entry from the site and store it in a data file.

Questions: What new timeline format is viable for future use? Figuring this out may dictate the format in which to store the entries: If XML, how coded? 

Possible open-source packages to adapt: 
Simile-Widgets: https://github.com/simile-widgets/timeline
Note: This may not provide as much multimedia integration or integration with Google Maps (?) as we've had with dipity.com

TimelineJS (NuKnightLab): https://github.com/NUKnightLab/TimelineJS
Multimedia integration looks better here...also takes input data from a handy Google Chart. 





