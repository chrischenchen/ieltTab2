## IeltTab2
When l apply my master programs, l need to memorize IELTS vocabulary. But l don't like this process, it is very boring. To pass the IELTs examination,
l need to build this new habits. l am curious about how to build habits more easily, so l read the books [Atomic Habits](https://jamesclear.com/atomic-habits) written by james clear. In this books, he mentioned Habit stacking method which was created by [Bj Fogg](https://www.bjfogg.com/). “Habit stacking is a special form of an implementation intention. Rather than pairing your new habit with a particular time and location, you pair it with a current habit. ” 

l also read the paper [A Behavior Model for Persuasive Design](https://dl.acm.org/doi/10.1145/1541948.1541999) written by Bj Fogg. In this paper, he proposes the Foggy Behavior Model(FBM). “The FBM has three principal factors that I refer to as motivation, ability, and triggers. In brief, the model asserts that for a target behavior to happen, a person must have sufficient motivation, sufficient ability, and an effective trigger. All three factors must be present at the same instant for the behavior to occur(Fogg, 2009).” 

Inspired by the Habit stacking and FBM, l want to build a Chrome extension which can help me build the habits of memorizing IELTS vocabulary everyday. Because opening web browser is my current habit which l do it multiple times everyday, so l want to pair it with memorizing IELTS vocabulary. When l designed the chrome extensions, l used 2 elements in FBM:ability(simplicity) and triggers. To reduce the resistance people face when memorizing vocabulary, when people open a new tab in web browser, it will only show 5 ielts words. "A trigger is something that tells people to perform a behavior now (Fogg, 2009)." In this chrome extension, the trigger is the each time people open a new tab, because the page will show 5 new ielts words when opening a new tab.

The chrome extension l built was called ieltTab. l collaborate with my teammates:Chatgpt to build this application.

Key features of ieltTab

- Show 5 ielts words when user opens a new tab
- Click the more button to learn more ielts words
- user can decide whether to show or hide the Chinese of ielts words

![pic1](https://github.com/chrischenchen/ieltTab2/assets/19976775/cc8cd510-77e3-443f-aad7-a693258db475)
![pic2](https://github.com/chrischenchen/ieltTab2/assets/19976775/d89369b7-05d5-40eb-8252-0d623b674c18)

## Built With
- [Javascript](https://www.javascript.com/)
- [Node.js](https://nodejs.org/en/)
- [Render](https://render.com/)

## Installation
1.Local Install

2.Download the zip file from Github releases

3.Unzip the file
In Chrome/Edge go to the extensions page (chrome://extensions or edge://extensions).

4.Enable Developer Mode.

5.Drag the unzipped folder anywhere on the page to import it (do not delete the folder afterwards).

## License
This project is licensed under the MIT license. Feel free to edit and distribute this this as you like.

See [LICENSE](LICENSE) for more information.

## Acknowledgements
Awesome resources which help this projects.
- [How to Deploy Your Node.js Application for Free with Render](https://www.freecodecamp.org/news/how-to-deploy-nodejs-application-with-render/)
- [Amazing-github-template](https://github.com/dec0dOS/amazing-github-template/tree/main#license)
- [Atomic Habits](https://jamesclear.com/atomic-habits)

## Reference
Fogg, B. J. (2009). A behavior model for persuasive design. Persuasive ’09: Proceedings of the 4th International Conference on Persuasive Technology. https://doi.org/10.1145/1541948.1541999
