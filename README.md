# Quiz9
[![Andy Warhol, Campbell's Soup Cans, 1962 | Sharon Mollerus | Flickr](https://tse4.mm.bing.net/th/id/OIP.2hNJlGIyDfTptWSJf0EtYwHaEg?pid=Api)](https://www.flickr.com/photos/clairity/20722353368)

---

## GitHub Repository Link

**https://github.com/dwan0480/Quiz9.git**

---

# Part 1: Project Direction

Our team has chosen to **reinterpret an existing artwork**.

We will reinterpret **Andy Warhol’s *Campbell’s Soup Cans* (1962)**. The original work consists of **32 individual canvas panels**, each showing a different Campbell’s soup flavor, arranged in a repeated grid format. MoMA lists the work as acrylic with metallic enamel paint on canvas, with each panel measuring 20 × 16 inches. ([The Museum of Modern Art][1])

**Original artwork image source:** MoMA page for Andy Warhol, *Campbell’s Soup Cans*, 1962. ([The Museum of Modern Art][1])

### Vision statement 

Our project reinterprets Andy Warhol’s *Campbell’s Soup Cans* as an interactive Pop Art system where every can becomes part of a shared animated field. Instead of treating each can as a static consumer object, we will make the entire grid react to sound, time, randomness, and user input at the same time. Our inspiration comes from Warhol’s use of repetition, mass production, and bright commercial imagery in *Campbell’s Soup Cans*, as well as the bold graphic impact of Roy Lichtenstein’s *Whaam!* and its comic-book visual language. ([The Museum of Modern Art][1]) We are also inspired by Warhol’s celebrity silkscreen works, such as *Gold Marilyn Monroe*, which use flat color, repetition, and iconic imagery to turn popular culture into art. ([The Museum of Modern Art][2])

**Inspiration image sources:**

1. MoMA — Andy Warhol, *Campbell’s Soup Cans*, 1962. ([The Museum of Modern Art][1])
![example](photos/1.png)
2. Tate — Roy Lichtenstein, *Whaam!*, 1963. ([tate museum][3])
![example](photos/2.png)
3. MoMA — Andy Warhol, *Gold Marilyn Monroe*, 1962. ([The Museum of Modern Art][2])
![example](photos/3.png)

---

# Part 2: Mechanics

## Team Members and Mechanic Ownership

| Team member     | Mechanic                    |
| --------------- | --------------------------- |
| [Name 1]        | Audio                       |
| **[Martin Wong]** | **Time-based**              |
| [Name 3]        | Perlin noise and randomness |
| **[Ming Chen]** | **User Input**                |

---

## Time-based Mechanic — [Martin Wong]

My mechanic will use timers and timed events to create rhythmic changes across the entire grid of soup cans. Instead of assigning time effects to only one can, the timer system will affect all cans simultaneously, supporting the idea that the whole artwork behaves like one Pop Art machine. Every few seconds, an event will trigger a visual change such as a color palette shift, a label flash, a scale pulse, or a short frame-by-frame transformation. For example, the cans may briefly change from Warhol-inspired red and white into brighter artificial colors, then return to their original state. The user does not need to directly control this mechanic; it works as a repeating visual rhythm in the background. This connects to our project vision because Warhol’s original artwork is based on repetition and mass production, and the timer turns that repetition into movement. The cans become less like separate objects and more like synchronized products on a factory line, advertising display, or animated pop-culture screen.

**Sketch/reference idea:**
A grid of Campbell’s-style cans with arrows showing timed color changes every 3–5 seconds. Label the states as:
`Normal palette → Flash palette → Scale pulse → Label flicker → Return to normal`


## User input — [Ming Chen]

This connects to our project vision because Warhol’s original artwork uses repetition and mass-produced consumer imagery. By adding user input, the audience is no longer only looking at the repeated cans. They can interrupt, change, and interact with the grid. This turns the static Pop Art image into a responsive system, where the viewer becomes part of the artwork. By incorporating user input, viewers are no longer just watching those repetitive, static cans. They can interrupt, alter, and interact with the grid. This transforms the static pop art image into an interactive piece. The audience's interactions become part of the work.

**Sketch/reference idea:**
```
    A[User moves mouse on canvas] --> B[Detect nearby soup cans]
    B --> C[Cans enlarge, rotate, or change colour]

    D[User clicks a soup can] --> E[Selected can opens]
    E --> F[Liquid pours out as a short animation]

    G[User presses keyboard] --> H[Switch Pop Art colour mode]
    H --> I[Apply new colour palette to the full grid]
```
---

# Part 3: Putting It Together 

All four mechanics will affect the full soup-can grid at the same time, rather than assigning one mechanic to one can. The cans will share one canvas and remain visually unified through repeated layout, bold outlines, flat colors, and Pop Art-inspired typography. Audio will drive reactive movement or intensity, time-based events will create rhythmic changes, Perlin noise and randomness will introduce variation, and user input will allow direct interaction. Together, these systems will transform Warhol’s static repetition into a living Pop Art display.

[1]: https://www.moma.org/collection/works/79809 "Andy Warhol. Campbell's Soup Cans. 1962"
[2]: https://www.moma.org/collection/works/79737 "Andy Warhol. Gold Marilyn Monroe. 1962"
[3]: https://www.tate.org.uk/art/artworks/lichtenstein-whaam-t00897 "'Whaam!', Roy Lichtenstein, 1963"
