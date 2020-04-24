# Creative Labs | Spring 2019

### Introduction
Last spring, my close friend Henry and I decided we wanted to lead a project for Creative Labs, an organization at UCLA that seeks to empower students and build community on campus through collaborative innovation. We submitted a proposal detailing our idea of developing an app to support digital bullet journaling, a former hobby of mine that I'd ceased due to a lack of time and money for stationary. We received an interview from the executive directors and passionately pitched our idea to them. 

They reached out to us a few days later and told us they'd love for us to lead a project! Unfortunately, they weren't big fans of our idea as several journal-related projects had already been done that year. So, they asked us to come up with something new despite pitch day happening in less than 48 hours.

Henry and I scrambled to come up with something. Some of our ideas, like a Pinterest-esque app focused solely on recipes, seemed great at first but ultimately seemed to have too large of a scope given the ~8 week timeline for most projects. As pitch day approached, an idea suddenly popped into my mind. 

One of our friend group's favorite games to play was a card game by the name of Tongits. A Filipino friend taught us the game a few months prior, and its fast-paced nature combined with the luck and strategy necessary to win made it pretty addictive. Though we all loved the game, we weren't always free to play with one another. So, I suggested that we digitize the game with a single player mode, and that we should incorporate culturally relevant graphics (since many of our friends were very involved in the Southeast Asian space at UCLA, and I personally had a passion for culture-related design work). Just like that, our project (Tongits) was born!

### Competitor Analysis
We began our project by researching existing Tongits games on the App Store. Our research revealed three key findings:
* Competitors have a clunky interface, which can cause confusion during gameplay
* Competitors have an outdated design, which makes gameplay feel less engaging
* Competitors have a standard design, which fails to highlight the Filipino origin of the game

| Tong-Itan | Social Tongits |
| :-------------:|:-------------:|
| ![TongItan](https://github.com/ashleyyph/Tongits/raw/master/TongItan.png) | ![SocialTongits](https://github.com/ashleyyph/Tongits/raw/master/SocialTongits.png) |

### Design and Development Process
After we identified key painpoints users might experience with existing Tongits games, we began the design process for our game. From an artistic standpoint, two major goals of ours were to create a more engaging design and to convey Filipino (and more generally, Southeast Asian) culture through the game. As a project lead, I worked closely with our illustrator to develop artistic inspiration and study eye-catching graphics, then integrate these into our design decisions.

| Southeast Asian Inspiration | Filipino Inspiration |
| :-------------:|:-------------:|
| ![SEA](https://github.com/ashleyyph/Tongits/raw/master/SEA.png) | ![PH](https://github.com/ashleyyph/Tongits/raw/master/Philippines.png) |

From a technical standpoint, one major goal of ours was to create an intuitive interface for players. Through weekly meetings involving extensive discussion of the interface design and many whiteboard sketches, we constructed an ideal setup interface for the game. After a few more discussions, we realized our design was also quite cluttered and decided that we should limit showing cards unnecessarily. 

| Interface V1 | Interface V2 |
| :-------------:|:-------------:|
| ![InterfaceV1](https://github.com/ashleyyph/Tongits/raw/master/Wireframe.png) | ![InterfaceV2](https://github.com/ashleyyph/Tongits/raw/master/Wireframe2.png) |

At this point, we felt that our design had reached an acceptable point for the software development of the game to begin without any major issues or changes during development. Using Android Studio, the developers on the team worked together to code interactive aspects of the game, like the process of drawing or discarding a card, in addition to some more boring stuff, like the settings page. 

A major challenge we ran into was the development of a computer for the player to play against. At first, we made a dummy AI to ensure that the interaction was functional at the very least. Once we established functionality, we began to write a logical list of considerations for the AI to make during each turn in order to optimize its chance of winning. We played a few games in real life to confirm that we weren't missing anything, and then we began to code the AI. It turned out surprisingly great at the game, likely because its memory (helpful for card counting?) and precision (no human error here). 

Around this time, we also received the almost complete card illustrations from our illustrator! As project leads, we were really happy because the project we had envisioned from the beginning seemed to finally be coming to fruition, and the visual representation of the cards only furthered our joy.

# Demo Day
As Demo Day (when all the project teams from the cycle come together to present their work) approached, we began to feel more pressure to tie all the loose ends that remained of our project and wrap it up. While Henry and our developrs worked frantically to fix bugs in the code, I worked with our UI/UX designer and illustrator to create materials marketing and documenting the progress of our project. We posted the following images on social media to increase anticipation for our project!

| Tongits! | Instructions |
| :-------------:|:-------------:|
| ![Tongits](https://github.com/ashleyyph/Tongits/raw/master/tongits.png) | ![Instructions](https://github.com/ashleyyph/Tongits/raw/master/instructions.png) |

We put the last touches on the card illustrations and began working on the artistic aspect of the actual user interface. Despite some minor disagreements over graphic elements and colors, we were able to find compromise and produce a finalized version of the interface spanning several frames in time for the developers to code before Demo Day.


