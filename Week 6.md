### Information on story so far:

From past weeks, I was leaning toward scroll animation, but have decided to instead use Twine as the coding medium for my story. 

ALL PROTOTYPES ARE LINKED IN THE PROTOTYPES FILE AT THE TOP OF THIS FOLIO!

Ok, so I am using Chapbook, which utilises different coding from others like Harlow or IceCube. 

First, I created the passages - I started with four and worked out how to link them. 

<img width="435" alt="Screen Shot 2025-05-13 at 12 43 36 pm" src="https://github.com/user-attachments/assets/44abf1fb-dd02-4d79-904a-96fc58a9fb77" />

So the coding for this part turned out pretty simple - as an example,  [[continue]] would allow the story to progress
[[Back]] would go back a page - if I wanted to go to the particular page, I could use [[continue->fleeing]]. 

<img width="273" alt="image" src="https://github.com/user-attachments/assets/aeae5290-0daa-4754-a253-c1263e9c8638" />

After that, I then attempted to embed an image with the code, but each time I'd press play, this would come up:

<img width="767" alt="Screen Shot 2025-05-13 at 12 48 38 pm" src="https://github.com/user-attachments/assets/09c667f9-6845-45c0-bddb-8105cf2961a7" />

{embed image: "https://img.freepik.com/premium-photo/nature-technology-harmony-generative-by-ai_893571-8408"}

Now, the issue I realised was that for the coding to recognise what I was trying to do, it needed to be a JPEG or PNG. 
So instead, I altered it to adhere to those rules: 

{embed image: "https://img.freepik.com/premium-photo/nature-technology-harmony-generative-by-ai_893571-8408.jpeg"}

<img width="308" alt="image" src="https://github.com/user-attachments/assets/51de17ea-81fa-464b-9bee-3119dc0b9bf3" />


### Miro image map

I find it easiest to plan it out into parts rather than just beginning, middle and end. I have linked the Miro page below for easy access.

https://miro.com/app/board/uXjVI2_zWUk=/?share_link_id=12724440297


#### Past student works


I did have a look at the students' work from past classes and have broken each of them into three parts to answer the questions:

House on a hill: 
I particularly enjoyed the mechanics, which used the space bar as the way to continue the story; the music was also a nice touch, which gave the whole piece an eerie feeling. The real beauty of the work, however, was the interactive gaming element which used the arrows as ways of not only moving around the room but stamping points to where you should go next. Such coding needed to complete this would have had to use javascript as well as sugarcube, I linked down below the type of coding I have been told would be used: 

$(document).on('keydown', function(event) {
    if (event.key === "ArrowUp") {
        // Player presses the up arrow
        State.variables.playerDirection = "up";
        // Trigger a passage change based on the direction
        Story.show("UpDirection");
    } else if (event.key === "ArrowDown") {
        // Player presses the down arrow
        State.variables.playerDirection = "down";
        Story.show("DownDirection");
    } else if (event.key === "ArrowLeft") {
        // Player presses the left arrow
        State.variables.playerDirection = "left";
        Story.show("LeftDirection");
    } else if (event.key === "ArrowRight") {
        // Player presses the right arrow
        State.variables.playerDirection = "right";
        Story.show("RightDirection");
    }
});

Again, I don't know if this would work or if it is right, but at least I have a visual of what she did in order to make her work.

One issue I found in Shade was how much of a guessing game it was to work out which word to type in which order. With House on a Hill, we know what to do, and yet there is still an element of mystery and intrigue that keeps us reading. I think the colour palette was smart as well, commonly sharper colours on games - icy blues or purples hold well in horror games, they can also show the emotional distress of characters without actually having to say anything. While the graphics are simple, the third-person view is something we commonly see in old pixelated video games and, more recently Resident Evil. It gives the feeling of truth whilst still sticking to that story element - it's like watching a show and having ultimate control over the characters, we know it's not us, but we feel responsible for the characters. 

Snow Season 
Poetically and structurally, I found the work incredibly appealing, I enjoyed the use of hypertext and image transitions throughout the piece. I think that while the interactive elements were small, it was the visual components that helped to include the viewer in the story. More so, the language in its formation - it wraps around the page - felt like the precipitation cycle, and since we are looking at snow, it made even more sense and was a nice sort of easter egg. 

Stay Strong
I liked how it was broken up into phases; not only does this show the emotional impact on both writer and reader, but adds context and trajectory for the story, ie beginning, middle, and end. The use of hypertext to show the difference between those speaking and personal thought was a nice touch, which helps to relate back to the overall point of the piece. I also liked the click features, which made us even more active participants in the story. The first page was also a nice add-on as it made the work more real and less story. While this is an interactive piece, it isn't a game like House on a Hill, as ther is only one ending, it feels like journal entries rather than just a story.



**How does this work make you reflect on your own ideas and what you might do for your own piece?** 

The main thing I took away from looking at these pieces was the importance of both narrative design and interactive elements. Since I want my story to use poetic prose I have to consider emotional points much more closely, to make sure there is continual engagement in the story as well as clear structural points that emphasises clarity and agency. It also made me more aware of what sort of story I wanted to tell and how – in regards to whether I wanted it more game or more story, below I have type out exactly what I want to include in my own work.


•  **Clear Choices:** Players should be able to have a good understanding of the work and the actions needed to complete the story. I will use clear visual and worded codes to compute this, like image changes or interactive elements.

•  **Immersive Atmosphere:** Have a strong emotional backdrop through color choices, use of music, and minimalistic or rather consistent graphics. Consider using contrast ie talk about forest while on a backdrop of an AI image.

•  **Innovative Structure:** Utilise hypertext and other interactive coding points like a drop down window, to make the structure feel dynamic. Have the text change, move, or transform based on what the player chooses to do.

•  **Interactivity and Agency:** Make it so the player to feel like they have control over the direction of the story, but have a twist with a multi ending. 






Jenny's Final Project: http://cordite.org.au/poetry/game/a-compendium-of-failed-relationships/


Read the contextual statements and consider how the form and function of each aspect of this piece feed into the themes of the work:

A: 
Each piece, while vastly different in style, all look at the same issue, which is abusive relationships in their many different forms. Whilst saddening, it is a reflective piece which, while interactive, doesn't feel like a game but rather journal entries to the emotional impact of abusive relationships. 



### Readings 

#### Riddles

A critical approach to interactive fiction, as literature and game.

An interactive fiction game: a form of storytelling which requires the input of the viewer to direct the course of the narrative.

Discussed the condition of IF - often text-based, allowing users to control a character and influence the environment through command. 

Below is a simple graph which highlights the diegesis in its simplest form and the corresponding motions attached to it.

![image](https://github.com/user-attachments/assets/98029471-67a6-483b-bf2b-dab670bbf62d)


Whilst there are considered to be many version of IF worlds - in the sense that they cannot all fall under one banner - I believe that is because of the sheer breadth of If stories out there as well as the need to refuse binary terms that could make it a definite term that could be compared to something else.

Player characters and non-player characters: The use of games as a way to create interactive fiction is most likely more well known then such things like twine and the general practice of electronic literature. For most interactive games allow for choice and decision making, but more than that they allow for character growth and connection that just a simple coded step by step game doesn’t allow. In simple terms it creates player agency and much like other interactive fiction brings a sense on ownership to the work/game. When we consider authorship, once more games are different from interactive written fiction however both form a bond between the participants action and the resulting outcome. While NPC's are both sperate and a part of the PC, the IF world is reliant on the actions of the PC to create a ripple effect and thus charter the actions of the NPC. The quarry a game made in 2022, does this quite well. There are at least six playable characters in the story whose actions can create certain responses from the surrounding NPCS, whether that’s a positive or negative one. For this story the quarry requires emotional choices made by the player to create minute changes in responses from the NPC, while this might not be considered important in the long run - doesn’t really alter the different endings of the games, it is reflective of human nature and how one ending might have been considerably better if other emotional choices had been made.


**The two riddles:** Poetry and computerisation have been held in long standing of one another. But the true ancestor of interactive fiction would have to be the riddle or so they say. I found this chapter particularly enlightening as I'd never thought to consider riddles as a truly interactive piece.

_Quote:_ 

The connection between poetry and the computer has been noted before (Novak 1991; Pinsky 1995, 1997); one London newspaper has even declared that “interactive fiction is computer gaming's best parallel with poetry: complex, subtle, and these days absolutely unsaleable”

_**Reference:**_ Montfort, Nick. Twisty Little Passages : An Approach to Interactive Fiction, MIT Press, 2003. ProQuest Ebook Central, http://ebookcentral.proquest.com/lib/rmit/detail.action?docID=5966542.


Poetry allows authors to convey emotional complexities and play with the modern issues of the time. Riddles require context which is hidden within the lines of language, often a times which is at opposition with one another, the example used: covered with eyes but it cannot see - a potato.

The reason behind the connection between the riddle and interactive fiction, would be the puzzle. The puzzle in laymen terms is what facilitates interactive fiction - to reach point A certain decision or points must be met by the reader/player/viewer. In a sense both riddles and interactive fiction require a solution, one that might not be given straight away or his hidden. 

_Quote:_ 

Literary riddles and interactive fiction are related in four important ways: Both have a systematic world, are something to be solved, present challenge and appropriate difficulty, and join the literary and the puzzling.




#### On Savoir-Faire: 

It is an interactive fiction which set in the mid 1700s where we follow a man called Pierre who coms under debt. Wanting to fix it he attempts to rely on a Lavori d'Aracne which is a system of magic to try and resolve his problem. 

It utilises the parameters of IF and is similar to the story Shade which forces the viewer to text different words and structure to move the story along. Interestingly enough, it almost reads like a text but has the components of a game. For the most part the story is progressive - you construct one light source and gain access to more complicated puzzles 

I rather enjoyed the use of magic the irony of it being all computer based. 

**Below I wrote down the key components of the game:**

• Linking Magic: The protagonist/player can "link" similar objects ie two mirrors - to create a corresponding action that performed on one has an affect on the other. This code is critical to how many of the gams problems are solved. 
• Puzzle-Focused:  The game known for its puzzle based challenges which require the viewers participation both creatively and laterally.

• Text Parser Interface: Consistent with interactive fiction, to progress the story typed commands are needed to interact with the magic world (e.g., "examine draw" or "link mirror to mirror").

While the commands are simple the responses may not be. Which makes the work unpredictable and thus enjoyable to play. 

I wonder if interactive fiction is becoming so popular because of this unpredictability that literature seems to have?


References

Montfort, N. (2004). _Riddles. In Nick Montfort, Twisty little passages : an approach to interactive fiction_ (pp. 37–63). MIT Press. https://ebookcentral.proquest.com/lib/rmit/reader.action?docID=5966542&ppg=54

Short, E. (2007). _On Savoir-Faire. In Pat Harrigan (Ed.), Second person : role playing and story in games and playable media_ (pp. 147–148). MIT Press. https://rmit.alma.exlibrisgroup.com/view/delivery/61RMIT_INST/12270521920001341


Assignment 2: 
