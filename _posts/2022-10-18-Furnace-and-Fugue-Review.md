# Digital Humanities Review: Furnace and Fugue

#### **Project: [Furnace and Fugue: A Digital Edition of Michael Maier's _Atalanta fugiens_ (1618) with Scholarly Commentary](https://furnaceandfugue.org/)**

#### **Project Directors: Tara Nummedal and Donna Bilak (editors)**

#### **Project URL: [https://furnaceandfugue.org/](https://furnaceandfugue.org/)**

![The home page of _Furnace and Fugue_.](https://PRSengl350.github.io/PRS-ENGL-350/images/FF_Home.png)

*The home page of* Furnace and Fugue.

#### **Overview**

_Furnace and Fugue: A Digital Edition of Michael Maier's_ Atalanta fugiens _(1618) with Scholarly Commentary_ is a multimedia digitization of a 17th-century German alchemical text and the short fugues, or musical pieces, contained within. The digital edition also features a contemporaneous English translation that has been lightly edited for modern spellings. _Atalanta fugiens_ features fifty sections, called emblems, that each have an image, a fugue, a short poem, and a discourse on some alchemical aspect, usually related in terms of Greek and Roman mythology. The reader can create their own collections of these emblems using the tool found in the site’s footer, “Emblem Collections”. The website contains the full digital edition, some background information, and eight interactive digital essays on the book, along with a performance edition of all the fugues. _Furnace and Fugue_ makes Maier’s alchemical text more accessible to readers  as it fully digitizes the original multimedia book in an interactive format, making scholarship easier than manually searching for translations and tracking down performerers or recordings of the fugues.

![The first emblem of _Furnace and Fugue_.](https://PRSengl350.github.io/PRS-ENGL-350/images/FF_Emblem.png)

*The first emblem of* Furnace and Fugue.

#### **Data and Technology**

According to the “About the Project” page, _Furnace and Fugue’s_ data comes from the 1618 version of Maier’s _Atalanta fugiens_, found at Brown University, and a contemporaneous English translation, found at Yale University. The project uses TEI language to upload and display the texts and translations used in the site in XML, which was then converted to HTML using a custom Python-based language. The music was transcribed into the notation software Sibelius and converted to MEI, a musical equivalent of TEI. _Furnace and Fugue_’s web functions are primarily powered through JavaScript plugins. The site provides a link to the project’s GitHub page, which encompasses all its source code and files. _Furnace and Fugue's_ technology was explained very clearly so that someone without a technical background could understand the basics of how this site was created.

![_Furnace and Fugue’s_ GitHub Page.](https://PRSengl350.github.io/PRS-ENGL-350/images/FF_GitHub_2.png)

Furnace and Fugue's _GitHub page._

#### **Design and Usabilty**

_Furnace and Fugue’s_ default layout shows the original text as a high-resolution image alongside the digitized translation. The user can switch from this layout to viewing either the original or the digital version separately. The digital text is available in five languages, with the default being English with modernized spellings. The fugues in the digital version are laid out in the original Latin using modern music notation practices. The reader can play recordings of the music with the option to toggle each voice on or off; there is an option to view the music in piano roll format as well.

For the most part, _Furnace and Fugue_ is easy to use. The options to change views and languages, for example, are labeled in plain language. However, there is a learning curve to understanding site navigation. It is unclear at first how to move between different emblems. The user cannot switch between pages as they would in a normal book unless they are only viewing the original; otherwise, they must select the “Emblem” tab and click on the section that they wish to access. These problems can be very frustrating, as it takes a few minutes to figure out how to get around the site. A way to fix this would be implementing a “next emblem” or “previous emblem” link at the bottom of each page so that the way forward is more obvious and intuitive. 

![The current way to switch between emblems.](https://PRSengl350.github.io/PRS-ENGL-350/images/FF_Scrolling.png)

*The current way to switch between emblems.*

In addition, changing to a different emblem currently resets the site back to the default view and language; a possible solution for this would be to create a way for the site to remember what views the user selected when changing between documents, perhaps through using browser cookies to store preferences. 

Necessary background information on the text is hard to find on the site. While the “About the Project” page explains both the text and the code, it is not obviously displayed. On the home page of the project, the link to this page is underneath a block quote, not underlined or set apart from the normal text. If the reader looks for the “About” page in the “Contents” tab, then they need to scroll almost all the way to the bottom. There is a link to the page in the website’s footer, but this again requires scrolling down to the bottom. This project would benefit by making this page easier to find; it could be part of the site’s header, higher up in the “Contents” tab, or given a spot next to the other options on the home screen. The “About the Project” page gives essential explanations regarding the languages, vocal characters, and editing practices used in this site, and reading it greatly improves the user’s knowledge and experience. It should be one of the first links that the viewer sees, even before the digital edition itself.

![The "About the Project" link on the front page. It is hard to distinguish from normal text.](https://PRSengl350.github.io/PRS-ENGL-350/images/FF_About.png)

*The "About the Project" link on the front page (at bottom of block quote). Note how hard it is to distinguish from normal text.*

The musical scores, while clearly notated and easy to follow, have some issues as well. _Furnace and Fugue_’s fugues feature three voices, all on their own lines of music, which can be toggled on or off. When the user selects the “Play Voices” button, each note playing turns red to make it easier to follow what is happening in the score. This is a useful feature, but the page auto-scrolls with the music to follow this animation. If one tries to move the page up or down to read a different part of the text, the page will automatically scroll itself back up to the current location of the animation in the score. As the music’s translation is beneath the score, this makes it nearly impossible to read about what is playing while listening to the text. Eliminating the auto-scroll feature or making it optional would make it much easier to use the site while the music is playing. 

In addition, there is no way to rewind or jump forward in the music; once started, the voices can only be paused, and the page must be reloaded to hear the fugue again. It would be easier to study the music if the user could choose where they want the music to start.

![The musical animation in action.](https://PRSengl350.github.io/PRS-ENGL-350/images/FF_Music.png)

*The musical animation in progress, as seen via the red notes.*

_Furnace and Fugue_ also offers a piano roll view of the score; this can be confusing to follow, however, as one of the voices is colored the same red as used to highlight the notes currently playing. Sometimes, the piano roll shows gaps in voices that are currently playing, creating the illusion that that voice is resting. Changing the color used to animate and coloring a note with multiple shades to show overlap would make this view easier to navigate.

![The piano roll view for Emblem VII. This one has the lower green voice appear to drop out, even though it is still singing, and the animation is the same color red as the middle vocie, making it hard to follow.](https://PRSengl350.github.io/PRS-ENGL-350/images/FF_Piano.png)

*The piano roll view for Emblem VII. The lower voice is still playing, although it appears to drop out. The animation line is hard to see, as it matches the red of the middle voice.*

Despite these design issues, _Furnace and Fugue_ is a beautiful and easy-to-use multimedia digital edition. Although it takes a slight learning curve, the site's clear labels and animations make the material simple to interact with and use in scholarship.

#### **Conclusion**

_Furnace and Fugue's_ unique interactive book relates to a variety of disciplines: musicians can study the historical style and word-painting of the fugues, artists can examine the images and their symbolism, and historians can examine the alchemical and scientific beliefs of that time. The site's layout makes it easy to switch between views and to hear the music, all in a normalized English translation.

I find this project to be very inspirational for my own. I am creating a scholarly digital edition of the song cycle _Winterreise_, and the layout and animation of the music is similar to what I want to do. I had not heard of the MEI coding language before viewing this site, but I now know this is what I want to use. My project differs from _Furnace and Fugue_ in that theirs focuses on music accompanying a text, whereas mine focuses on how the music enhances a poetry text. I hope to accomplish the same ease of usability in as _Furnace and Fugue_.

Overall, _Furnace and Fugue_ advances scholarship by turning the multimedia Alalanta fugiens into a fully realized project, with the reader able to hear the music and read the text in translation in a manner that is truly accessible.

