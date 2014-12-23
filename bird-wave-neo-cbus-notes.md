# The story arc
- need to give better examples about why you picked clojure over other languages.  answer:  "why clojure?"  The decision factor wasn't really presented.
- how do lisps relate well to birdwave in particular?  Your examples should continually feed into how it helped birdwave development
  - "can i import a giganctic data file" was much better at doing this
- have a slide that shows the "immediate wins" of clojure, just like you did with clojurescript
- benefits of datomic ... talk about how each feature was used and important for birdwave
+ good job not going too deep into the intricacies of clojure or clojurescript
= be thinking about the "why?" of your presentation.  Is the goal to "explain how birdwave was created", to advocate the benefits of clojure or clojurescript, to get people excited about new languages, to compare javascript to clojurescript, to have people consider different ways of tackling difficult computing problems, or something else.  Make sure you stick to this goal and make it the common thread throughout your presentation.  I wasn't entirely sure what this thread was.
- I like how you included stuff about “why clojure” but look for ways to demonstrate your love/enthusiasm for it better. Audiences will be excited if you are excited.
- Make sure you think about what you want the audience to come away from this talk thinking.  Is it “I want to use clojurescript”? Is it “I have been given a taste of a complex app that uses 4 technologies that I need to go learn”? I think your last slide suggests it’s the former. If so, does the Om stuff really add to that? Pick a point of view and make sure everything in your talk supports that view and eliminate/reduce things that detract from that.

# Section transitions
✓ Agenda, recap between sections
✓ high five each other every time you transition between your parts of the presentation
   ✓ actually, I think your pacing of switching back and forth felt right to me.  It was just enough to break up any monotony
✓ nice examples on the bird field guide (what about playing actual bird sounds during this part? ... that would be cool)
✓ nice change of pace with "imagination land".  Breaks up the show and tell nicely.
   + uses a particular component from bird wave ... good choice to stay on topic
- Don’t put slides up until you are ready for them.  “Why Clojure, It’s a Lisp” was up for a long time before it was referred to. Consider getting a better transition slide for the handoff.

# App architecture
- perhaps discuss how data moves through birdwave ... what is requested, what is the payload, performance implications
   - perhaps give json payload example, rather than just verbally describing what is in the payload
? Are there any limitations you found with the technical decisions that were made?

# Examples of the size/quality of the data
- show example record from ebird data to illustrate just how complicated this data set can be
- show graph/image/chart or something to illustrate how you broke up the data (year/state/county/month)
- “Too much data to load at once” —> show them that it is true. How long would it take to load that in traditional means?
- Consider showing a snippet of geojson or topojson data if you think the JSON is visible. Maybe use Sandusky as your source since that’s where we’ll be.
- If you used topojson, is it important to compare it to geojson?  Seems ancillary and distracting from your point.

# Interact with the audience more
+ play "Free Bird" to pump up the audience
- ask the audience, "who knows about clojure?" to get a rough idea of experience level in the room.  and to engage the audience.
- One thing Jim Weirich always did that was effective is to engage the audience in a dialog.  You could do this too.  “Raise your hand if you are a birder”, “How big do you think the data set is”, “Who knows clojure”.  This kind of stuff (a) keeps the audience engaged and (b) lets you adjust in real time how much detail to go into (e.g. how much of the clojure basics to cover).

# Code examples
- Illustrate where the code examples were used
- add more sample code from birdwave to illustrate your points
- when you talk about the flickr clojurescript, remind the audience why you needed flickr for birdwave...the problem you were attempting to solve
+ good job showing why using clojurescript for flickr was a huge win for you
- definitely show how birdwave looks/behaves on mobile
+ perhaps having a laser pointer to point out things on the screen?
   - after seeing more slides, you guys really need one.  you need it to point to lines of code easily.
- perhaps an illustration / diagram to help audience visualize channels better (core.async slide)
- I think the core.async code was difficult to get and could benefit from some visuals before diving into the code.  These can be slides that highlight/dim relevant parts you are talking about, or diagrams that are mental models of channels and things coming down them.
+ nice job giving a useful, understandable core.async example
- don't assume that your audience knows what d3 is
+ I like the slides that shows both javascript and clojurescript.  On slides where it would be nearly impossible to write it in javascript, you should still show the javascript box, but then just insert a photo of a bowl of speghetti
- Consider showing a Pedestal code snippet. People at the conference will be used to web dev and so they’ll have a good shot at being able to read/follow it.
- In your “small example” you showed clojurescript versions and talked through what raw javascript would be required. Your point would be better made if you showed both of them. If I understand correctly, your whole point is to encourage people to consider using clojurescript instead of javascript in times. So show them the comparisons where the benefits of clojurescript are immediately obvious.  The core.async example is another one. You said that the plain javascript one would be harder, but unless I fully understood the core.async stuff (I didn’t) I had no way to know how true that was.
- Don’t apologize for clojurescript. There were a couple times when you said something that amounted to “it’s really not that bad”. I like how you showed how a JS version mapped to a clojurescript version (see above) but no need to defend clojurescript in cases when it offers no significant advantages.
- You mentioned that “Google Closure library” was a bit of a strange name. Seems like a good opportunity to talk about the differences between clojure and closure so people get it
- The part where you were describing how OM improved on React was a bit confusing to me. You were explaining a mental model.

# Go bigger!
✓ Fullscreen video
✓ use full screen browser mode
✓ birdwave demo video is too small to get full impact ... this is your big showing!  If they don't understand or aren't impressed that might not care about the implementation
✓ actually, having all the slides be larger would be nice
✓ The “birding: a brief introduction” thing is too small to read.  Memorize the quote or blow up the part that needs to be read (pop out of page)
✓ Can you make Gollum bigger?

✓ Links to birdwave, blog posts

# Investment Friday plug

✓ Get rid of tagline
✓ avoid using buzz words like "rich tools"
