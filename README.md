joywave-heardle
A clone of Heardle, and K-Pop Heardle but for Joywave songs.

Each Joywave Heardle is randomly chosen from Joywave's discography.

code edited from: WJSN Heardle

HOW TO MAKE YOUR OWN HEARDLE (UDPATED on 4/13/22)

Remix this project to create your own copy of the code
Rename the project with the URL that you'd like to Heardle to live at
Open the index.html file & replace "Joywave" with the artist/genre of your heardle
In the index.html file, you can update the image that gets shared with your link by updating lines 23-33.
(Items 5-10 are all edits to the main.js file)

On line 2 of main.js file and update artist with the artist/genre of your heardle - This will update all the text boxes & titles where "Joywave" shows up
On line 3 of main.js file, update twitter with your own twitter or instagram handle - This will update the contact info and replace every instance of "joywavez"
On line 4 of main.js, update the startDate to the current date in the format YEAR-MONTH-DAY (YYYY-MM-DD) - This will start the counter for your Heardle
On line 5 of main.js, "const Cn" is initialized. Replace the text with a list of song titles that you want to show up as options in your Heardle. It should follow the format "Song - Artist". Make sure each song is in quotes and has a comma after it
On line 78 of main.js, "On" is initialized. Here you'll have to replace the links with links to your songs. Soundcloud links work best. Each link will have to follow the following format: { url: "<link>", answer: "Song - Artist" },
The order of the songs in "const Cn" should match the order in "On".
If you want your heardle link to show up whenever someone shares their results, on line 4831 remove the "//" and update the link with your own heardle link


At the moment, the order of the songs match the order that the Heardle's will appear, so if you dont want to ruin the surprise, have someone else upload the order of the songs and links for you!

Glitch auto saves your code, so your changes should be available as soon as the code is editted.

Heardle doesnt work in the "Open Preview Pane" option, so make sure to view it in the "Preview in new window" option


Feel free to tweet/dm me @joywavez on twitter if you have any issues/questions!
