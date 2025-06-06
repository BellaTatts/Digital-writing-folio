
#### Practical assignment 1 completed - 

Looked at the Scroll animation for the speech and investigated whether or not I wanted to include it in my work.
Looked at the Vine and the Fish.

#### Background info on the Vine and the Fish: 
For some background context, Hook is a cartoonist and illustrator based in Stockholm, Sweden. Her work has appeared in The Believer, The New Yorker. Typically, Hook’s work seeks to represent emotional strains of everyday problems in the form of literary stories formatted as comic strips, like the Nest and Beijing bike. There is a reserved quality to her work that provides an interesting contrast to its inherent emotional content, which flows onto the colour palette. The vine and the fish is no different, but instead of the classic comic, it utilises a limited-animation down-scrolling comic that compares the "invasive species" like the kudzu vine and the Asian carp to xenophobia and generalised anti-immigration sentiment that was fanned during the Trump administration.

#### Problems with Scroll animation: 
This type of animation is linked to the scroll position of a scroll container. This means that when you scroll up or down, the linked animation scrubs forward or backward in direct response, thus moving between images and text. One of the issues I found in Hooks' work and a problem across most creators using this form of animation is linking the images and text with the scroll motion. I found it rather easy to miss images and text if I were to scroll too fast. I also found that the inclusion of images and sound created extra 'noise.' So, instead of just focusing on the message of the story, the animation was what had the most impact.

![Page-1-Panel-5](https://github.com/user-attachments/assets/8c75d68c-e0d9-43e8-acb4-b0b78897cdeb)


<img width="523" alt="Screen Shot 2025-05-13 at 10 02 54 am" src="https://github.com/user-attachments/assets/6eb3dc1b-a310-4307-a98e-f7a1c340aca1" />

#### Scroll animation

For a brief definition of scroll animation: "It is a common UX pattern on the web. These are animations that are linked to the scroll position of a scroll container. This means that as you scroll up or down, the linked animation scrubs forward or backward in direct response." 

I went through a lot of different videos to try and understand Scroll animation. What I ended up with was how websites worked, but not so much how I could include the animation, which was a separate thing.

<img width="323" alt="Screen Shot 2025-06-06 at 4 10 03 pm" src="https://github.com/user-attachments/assets/fbfa0ee3-37c2-4bf8-85cf-8d5a19d5826e" />

For most of it, the key points were put into the stylesheet. Including but not limited to a height of choice, a scale can be added in the coding to alter the width whilst keeping the height and the background colour. 

<img width="323" alt="Screen Shot 2025-06-06 at 4 10 03 pm" src="https://github.com/user-attachments/assets/378088ca-1bfb-406b-8768-b354bede8bdc" />

He also talked a lot about using an animation scroll watcher - in part, it is to control how the system runs - the person has control rather than a timer, which can make the work move too fast.

0 ket frames means you are at the top of the page, while 100 is at the bottom.
In the Index, he then included the image codes, which he can then use to code into the stylesheet. 

<img width="307" alt="Screen Shot 2025-06-06 at 4 53 14 pm" src="https://github.com/user-attachments/assets/bc134431-8163-414c-afed-7e09250dae8d" />

I have been struggling to find links on how I can add animation to the scroll animation. I assume I could probably use GIFs - or would I need to animate them myself?

YouTube link: https://www.youtube.com/watch?v=UmzFk68Bwdk

### Twine
I haven't had any issues with deploying the coding playground, however, I made a note to utilise Vercel in case of any issues.

My response to using twine - Upon trying my hand at scroll animation, I attempted to do it through big brand names such as Wix, but when I attempted the coding, it required further fees, which I will discuss below. But when I first started using Twine, I found the beginner form called chapbook, which is a step below Harlow.

Key terms in Twine - 
**CSS (Cascading Style Sheets):** is a programming language for describing the presentation of HTML elements (i.e. the colours, fonts, spacing, and general layout of a web page). When using Twine, additional CSS rules can be added through the Story Stylesheet screen. This CSS is inserted into the final story and provides an opportunity to override the colour and formatting choices expressed in the story format's own stylesheet.
For reference, the stylesheet is the final visual presentation of your story.

**There are three primary forms of selectors in CSS:**

### type: 
These select different elements like <p> or <div>. They are written using the form of p {} or div {}.

### class: 
These select elements based on their class attribute. They are written using the form className.

### id: 
These select elements based on their id attribute. They are written using the form #idName.

**JavaScript:** When using Twine, extra functionality can be added through the Story JavaScript screen. This is run before the Story is run and provides an opportunity to write specialised code or include external libraries and files. 

window.setup Example

window.setup = window.setup || {};

**HTML:** The HyperText Markup Language (HTML) is the standard for all documents designed for a web browser. It consists of a series of elements defining its structure and the layout of its content.

Each story format handles its own layout and HTML structure. While CSS can be used to style its elements, it is often recommended to use any existing macros for this purpose in a story format, if available.

Example:

<tw-storydata>
  <style
    role="stylesheet"
    id="twine-user-stylesheet"
    type="text/twine-css">
  </style>
  <script
    role="script"
    id="twine-user-script"
    type="text/twine-javascript">
  </script>
  <tw-tag
    name="tagName"
    color="orange">
  </tw-tag>
  <tw-passagedata
        pid="1"
        name="Start"
        tags="tag1 tag2"
        position="102,99"
        size="100,100">
    Some content
    </tw-passagedata>
</tw-storydata>

**Twee:** Twee is the source code of a Twine story. In Twine 1, stories could be exported into their source, changed, and imported again. Twine 2 has moved away from this functionality, but has been heavily influenced by having sections (passages in Twine 1) where the user can add CSS (Story Stylesheet) and JavaScript (Story JavaScript).

**Passages:** Passages can be thought of as divisions of time, space, or combinations of the two. They can also be thought of as blocks of dialogue, sections of code, or simply ways to break up a complicated project into more easily understood parts. In Twine, passages are at the core of any story.

**Hypertext:** Hypertext is a system for linking related text documents that allows the participation of multiple users. In a hypertext document, any word or phrase can be “hyperlinked” to information related to that word or phrase residing in the same document or in another document. When a hyperlink is activated, the hypertext system retrieves the related information. For example, by selecting a word in a sentence, the definition of that word is retrieved. (So basically it is a source that, once clicked it transports the viewer to a new screen.)



### Readings

**My Body by Shelly Jackson**

![eyebrow](https://github.com/user-attachments/assets/30de6d33-e33e-4737-82c3-3574c647e2f6)

![eyebrow](https://github.com/user-attachments/assets/9f5187d7-ef20-45d7-a5a2-f9abc8158967)

It was an interesting read that took the concept of identity and turned it into something much more than that. It was both vulgar and necessary as it delved into the psyche of how we view ourselves and our internal organs. Not just visually, but how we interact with and majorly overlook them.
I thought the use of hypertext was well done as it was succinct in moving between the different parts without having too much overlap. I thought it was also smart that she used images to make it clear which part you were at, particularly if you were just going through the hypertext links. For my work, I would like to make clear distinctions between certain parts, particularly the beginning and the ending. Since I am working on the vine and the fish, which is a scroll animation, I am considering using the same medium in my work.



#### Practical Assignment 2 planning

Idea/Concept: A Futuristic look into AI in a world without life. I am looking at ideas of how I could fit the scroll animation into my work. Since I am considering looking at The Vine and the Fish as my example for assignment 1, I have been researching how to work with it with CSS. I am not quite confident with the overall coding part, but I have been looking at videos like down below to help translate some of the language. Although twine does have many good elements too, that might fit better if I want the story to be more interactive.


