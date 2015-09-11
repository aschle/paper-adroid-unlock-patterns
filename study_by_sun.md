# Dissecting pattern unlock: The effect of pattern strength meter on pattern selection

* Limited pattern space, shoulder surfing, smudge attacks make it week in security.
* analyzed the charactersitsics of all valid patterns and proposed a way to quantitatively evaluate their strength.
* pattern strength metersindicating pattern strength
* user study with 81 participants

## related work
* first graphical passwords Blonder in 1996 (position in images in a specific order)
* Draw A Secret by Jermyn at al. om 1999, NxN grid, drawing one or more strokes
* Dungphy and Yan 2007 introduced a background image to the original DAS, called BDAS, users tend to draw more complex patterns
* Tao and Adams in 2008 Pass-Go user selects intersections instead of cell in 2D grid
* to add error tollerance they introduced sensitive round areas around intersections, very similar to Android Unlock Patterns
* Orozco et al. proposed checking of haptic parameters like velocity and pressure
* YAGP proposed by Gao et al. 2008

### Android Unlock Patterns
* Aviv - smudge attack
* Andriotis et al. 2013 also smudge attacks replicating Aviv, also pattern design is studies using heuristics
* De Luca et al.(2012) - also authenticat on how they perform the input
* Uellenbeck et al. (2013) investigate how users chose patterns

This paper wants to understand the underlying characteristics of the pattern

## analysis of pattern unlock
* with respect to shoulder surfing the follwing things are analyzed (increase complexity)
* Attneave (1957) studied the judged complexity problem of shapes, complexity is related to number of turns in the contour of a shape, symmetry of a shape, variability of angular change between successive turns
* Dunphy and Yan indicated number of strokes, and password length of DAS are important security metrics
* Andriotis et al. length and direction changes

### pattern characteristics
* size - number of dots
* lenght - physical length
* intersections - crosses
* overlaps - no crossing but touching

And they also looked at the distribution, differenciating on number of dots.

## Study
* on university campus, college students
* draw a pattern twice to confirm it
* then set up 7 patterns ( 2 for practice )
* people with meters more dots,longer length, more intersections
* input conviniece and memorability prevent people most from choosing strong patterns
* more complex pattern cause problems to memorize them (failour rate)


## Limitations
* memorability was not really tested (only to times but no recall after some time)
* what is the distribution of obtained patterns related to pattern length, intersections, overlaps, size and overall scoring????? did I miss this part???
* user get no feedback about what to change to make a more secure pattern, what the users thinks about pattern and what is a real secure pattern differs a lot
