# Midterm Markdown Project
## Page Directory
- [Home](./README.md)
- [About Me](./ABOUTME.md)
- [My Friends](./FRIENDS.md)
- [Theory of Systematic Relativity](./THEORY.md)
- [Favorite Video Games](./VIDEOGAMES.md)
- [Favorite Composers](./COMPOSERS.md)

---
## Theory of Systematic Relativity
### To save some time, I am going to massively tl;dr this explanation, or else I would not be done for the next 2 months. The theory poses the idea that emotion in music is a product of the distance between notes in their respective context.  Harmonic Relativity is the process of making chord progressions based on the *relationship* between each of them.  For example, if a composer wanted a theme to sound heroic yet also bitter sweet, they could use the corrosponding chord relationships in tandum to create such sound.  However, this way of writing music is undoubtedly too simplistic and lacks nuance.  You might achieve new found chord progression with this system, but they will often times sound out of context and lack a central key due to their nature.  To combat this, I have been developing a system that encorporates harmonic relativity with a more structured approach, such as classical tonal theory. 
--- 

## Problems Encountered
### Much like any abstract theorhetical system, they can often lose the original goal set for its creation, purely for the sake of complexity.  I hope to keep the system relatively simple yet effective, because, in my opinion, music is meant to evoke emotions and communicate in a way which language cannot.  Traditional Tonal Theory often times feels too rigid for the mere sake of rigidity and tending to keeping traditions.  However, this means that it leaves much sonic ground to be encountered and explored.
---

## Goal
### The goal of this system is to aid the composer in creating unique and potent chord progression, giving them a wider pallet of colors to choose from.  In reality, it is not much of a a theory, but very much a system.  The reason I refer to it as a theory at the moment is due to the fact that there is no evidence that it will work.  I plan on researching an taking aspects from negative harmony, harmonic relativity, multipolor tonality and Neo-Riemannian theory.  I want to stich these concepts together like a well made quilt or use them as a cohesive machine, one that is well oiled and efficient.

---

## Circle of Fifths
![Circle of Fifths](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.lE0REgWmW7h6QQPno-ThCgHaHA%26pid%3DApi&f=1&ipt=48f0735ad412b420221cc93fa26bbe3a6c30e4a683521e2ba018859af2e9f149&ipo=images)
### This seemingly simple looking circle is a very useful tool in mapping out synchronicities found in music. If you add 5 more rings and rotate each one by a single letter counterclocking, you will get each scale and their corrosponding [modes](https://en.wikipedia.org/wiki/Mode_(music)).  This is a useful visiual aid in showing the nearby tones from every source, rather than just major and minor scales.  It is very helpful in understanding the functions of the same 7 chords found in the key from 7 different perspecitives, allowing you to create unique progressions that resolve in special ways without lacking the necessary intelligibility.

# Coding
```
mode_dictionary = {
    'c':'ionian',
    'd':'dorian',
    'e':'phrygian',
    'f':'lydian',
    'g':'mixolydian',
    'a':'aeolian',
    'b':'locrian'
}


print("When there are no sharps or flats:")
for i in mode_dictionary:
    print(f"{i} is the root of the {mode_dictionary[i]} mode")
```
### This code displays the corresponding root note for the modes with zero sharps and flats.