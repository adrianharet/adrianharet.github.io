---
title: "Adventures in Democratic Decision Making"
date: 2024-10-14 00:00:00 +0000
categories: [Course]
tags: [social_choice]     # TAG names should always be lowercase
toc: true
---

Though often taken for granted, democratic institutions have been subject to change and tinkering since their early days. 
The aim of the course is to look under the bonnet of voting systems, juries and apportionment rules, 
and see how the rules of the game have been questioned and refined over time. 
We will focus on a series of notable moments in democratic decision making, 
starting in Ancient Greece and ending with present day efforts to find a perfectly proportional representation system. 
The course will is based on George Szpiro’s *Numbers Rule. The Vexing Mathematics of Democracy, from Plato to the Present*, 
and Ismar Volić's recent book *Making Democracy Count: How Mathematics Improves Voting, Electoral Maps, and Representation*.

The course is structured as a series of weekly discussions on each chapter in the book. 
There will also be additional material on recent developments and trends.


# Lectures

## Week 1. Voting: Aiming for Fairness, or Accuracy? 
<div style="text-align: right">
    October 14, 2024
</div>

We kick things off by introducing ourselves, 
followed by a breakdown of the logistics of the course. 
We then have our first glimpse of social choice theory,
and two ways of thinking about voting: 
as a procedure for finding society's opinion about an unknown ground truth (epistemic voting), 
versus as a procedure for aggregating preferences into an expression of what 
voters want (non-epistemic voting).

<i class="fa-solid fa-file-pdf"></i>
Adrian.
<a href = "/content/teaching/2024-ws-adventures/01-01-logistics.pdf">
    Logistics
</a>
<br>
<i class="fa-solid fa-file-pdf"></i>
Adrian.
<a href = "/content/teaching/2024-ws-adventures/01-02-voting-epistemic-nonepistemic.pdf">
    Epistemic vs non-epistemic voting
</a>





## Week 2. Athenian Democracy
<div style="text-align: right">
    October 21, 2024
</div>

We look at an early example of a functioning democracy: ancient Athens.
We see how Athenian democracy worked and hear from one of its main critics, 
a local thinker and would-be advisor to kings called Plato.

The readings are Chapter 3 of Lane (2014), for an overview of democratic Athens, 
and Chapter 1 from Szpiro (2010) for Plato's alternative.
As a bonus reading, have a look at Chapter 4 of Melissa Lane's book.

<i class="fas fa-tasks"></i>
Lane (2014), Chapter 3
<br>
<i class="fas fa-tasks"></i>
Szpiro (2010), Chapter 1
<br>
<i class="fas fa-tasks"></i>
Lane (2014), Chapter 4 (bonus reading)

<i class="fa-solid fa-file-pdf"></i>
Adrian. <a href = "/content/teaching/2024-ws-adventures/02-01-athenian-democracy.pdf">Athenian democracy</a>
<br>
<i class="fa-solid fa-file-pdf"></i>
Nestor. <a href = "/content/teaching/2024-ws-adventures/02-02-nestor-antidemocrat.pdf">Plato's critique</a>





## Week 3. Plurality and Its Discontents
<div style="text-align: right">
    October 28, 2024
</div>

We see an early example of trying to manipulate a collective decision: 
the trial of Afranius Dexter's purported killers, as reported by Pliny the Younger. 

The takeaway from this week is that the rule used to determine the outcome of such a collective decision
(plurality, or First-Past-the-Post) encourages tactical voting. Why? Because the outcome using this rule
often mis-represents the preferences of the voters. There is a real possibility that the winner is hated
by most of the voters, and the the upshot is that voters will be strategic about how they place their votes.

This is a broad phenomenon that afflicts many modern elections, not just trials in the Ancient world.
Over time, it can have the effect that candidates (e.g., parties) with very low chances of winning
drop out of the race. This is known as Duverger's law.

<i class="fas fa-tasks"></i>
Szpiro (2010), Chapter 2

<i class="fa-solid fa-file-pdf"></i>
Adrian.
<a href = "/content/teaching/2024-ws-adventures/03-02-plurality-and-its-discontents.pdf">Plurality and Its Discontents</a>
<br>
<i class="fa-solid fa-link"></i>
CGP Grey. 
<a href = "https://www.youtube.com/watch?v=s7tWHJfhiyo">Minority Rule: First Past the Post Voting</a>. YouTube
<br>
<span style='margin-left:16px;font-size:13px'>
    Nice illustration of Duverger's law.
</span>



## Week 4. The Copeland (Llull) Rule
<div style="text-align: right">
    November 4, 2024
</div>

We're introduced to the Catalan thinker Ramon Llull.
Trying to find the most perfect way of electing an abbess, 
Llull put forward, around 800 years ago, not one, but two (!) voting rules.
The first is based on counting the number of wins each candidate gets 
in pairwise contests with the other candidates,
and is more commonly known today as [Copeland's method](https://en.wikipedia.org/wiki/Copeland%27s_method).
There is one technicality, which is the possibility of ties, but Llull hand-waived it away. 
Another problem was that this way of finding a winner took up more resources than were available at the time,
since it involved running an election for every possible pair of candidates. 
For 9 candidates, which was the number Llull was dealing with in his example, this amounts to 36 rounds of voting.

Llull tried to circumvent this problem by introducing a variant in which the 
loser in the first election was eliminated and the winner pitted against a new candidate, and so on, tournament style. 
This rule is known nowadays, unsurprisingly, as 
the tournament, or [round-robin](https://en.wikipedia.org/wiki/Round-robin_voting) method of voting.
While faster (with 9 candidates it requires only rounds of voting), it is sensitive to the order in which candidates 
are lined up.

<i class="fas fa-tasks"></i>
Szpiro (2010), Chapter 3

<i class="fa-solid fa-file-pdf"></i>
Nicola.
<a href = "/content/teaching/2024-ws-adventures/04-01-nicola-the-mystic.pdf">The mystic</a>



## Week 5. Nicolaus Cusanus and Scoring Rules
<div style="text-align: right">
    November 11, 2024
</div>

We find out about Nicolaus Cusanus and his quest to find the best way to elect a pope.
Cusanus' idea involves ranking candidates, and assigning them points.
The winner is the candidate with the most overall points, an idea that will be rediscovered 
by Borda some years later (and which we will look at next week).

We see that there are many ways to assign points,
learn about the general idea of scoring rules, 
and see some concrete examples (e.g., Eurovision, or Formula 1).

<i class="fas fa-tasks"></i>
Szpiro (2010), Chapter 4

Lena is presenting.

## Week 6. The Borda Rule
<div style="text-align: right">
    November 18, 2024
</div>

We learn about Borda rule. The reading is Chapter 5 of Szpiro (2010).
We see that, even though intuitively appealing, Borda has several drawbacks:
it can select mediocre candidates, candidates whom a majority of the voters think 
are worse than some other candidate, and it is embarrassingly easy to manipulate.

<i class="fas fa-tasks"></i>
Szpiro (2010), Chapter 5

<i class="fa-solid fa-file-pdf"></i>
Federico.
<a href = "/content/teaching/2024-ws-adventures/06-01-federico-borda.pdf">Borda and his rule</a><br>
<i class="fa-solid fa-file-pdf"></i>
Adrian.
<a href = "/content/teaching/2024-ws-adventures/06-02-borda-rule.pdf">The Borda rule</a>

## Week 7. Condorcet Consistency
<div style="text-align: right">
    November 25, 2024
</div>

We formalize the idea that candidates deserving to win an election should 
be those candidates that win in head-to-head contests against other candidates,
an idea credited to Condorcet.
Condorcet winners are nice, but they have the disadvantage of not always existing.

<i class="fas fa-tasks"></i>
Szpiro (2010), Chapter 6

<i class="fa-solid fa-file-pdf"></i>
Adrian.
<a href = "/content/teaching/2024-ws-adventures/07-01-condorcet-consistency.pdf">Condorcet Consistency</a>


## Week 8. Approval Voting and Range Voting
<div style="text-align: right">
    December 2, 2024
</div>

Our quest for the perfect rule continues.
We meet two new voting rules: approval voting and range voting.
Both are based on the idea of distributing points liberally to preferred candidates. 

We see that, despite being intuitively appealing and very permissive, range voting 
can degenerate into a simpler manifestation by voters assigning extreme points 
in an attempt to manipulate the result.
Meanwhile, approval voting seems to be specialists' favorite rule, with plurality 
as the least favorite
(see Laslier (2012) for the result of a poll conducted among social choice theorists). 

<i class="fas fa-tasks"></i>
Volić (2024), Chapter 5

<i class="fa-solid fa-file-pdf"></i>
Victoria.
<a href = "/content/teaching/2024-ws-adventures/08-01-victoria-approval-range-voting.pdf">Approval Voting & Range Voting</a><br>
<i class="fa-solid fa-file-pdf"></i>
Laslier, J.-F. (2012). And the Loser Is... Plurality Voting. In D. S. Felsenthal & M. Machover (Eds.), Electoral Systems: Paradoxes, Assumptions, and Procedures (pp. 327–351). Springer.



## Week 9. Instant Runoff Voting
<div style="text-align: right">
    December 9, 2024
</div>

The lecture is about Instant-Runoff Voting, also known as Single Transferable Vote,
Ranked-Choice Voting, or, in the UK, Alternative Vote.
We hear about the good, the bad and the ugly aspects of trying to actually make it work in real life.

<i class="fas fa-tasks"></i>
Volić (2024), Chapter 3

<i class="fa-solid fa-file-pdf"></i>
Adrian.
<a href = "/content/teaching/2024-ws-adventures/09-01-stv.pdf">Instant Runoff Voting</a>

## Week 10. Arrow's Theorem
<div style="text-align: right">
    December 16, 2024
</div>

This week we find out, finally, why democracy is impossible.

We will see Arrow's theorem, together with the (non-trivial) proof.
Nestor is presenting.

<i class="fas fa-tasks"></i>
Szpiro (2010), Chapter 11
<br>
<i class="fas fa-tasks"></i>
Volić (2024), Chapter 4


## Week 11. Christmas!
<div style="text-align: right">
    December 23, 2024
</div>
Christmas break. No lecture today.

## Week 12. The Condorcet Jury Theorem
<div style="text-align: right">
    January 13, 2025
</div>

We see why the many are better than the few,
why groups are wise, and why democracy may work better if people talked
to each other less.

## Week 13. Apportionment I
<div style="text-align: right">
    January 20, 2025
</div>

The mathematics of apportionment for the US House of Representatives.

<i class="fas fa-tasks"></i>
Szpiro (2010), Chapter 9


## Week 14. Apportionment II
<div style="text-align: right">
    January 27, 2025
</div>

The mathematics of apportionment for the US House of Representatives.

<i class="fas fa-tasks"></i>
Szpiro (2010), Chapters 10 and 12


## Week 15. TBD
<div style="text-align: right">
    February 3, 2025
</div>


# Ideas for essays
1. We've seen some examples of Athenian democracy at work, taking decisions, some good and some bad. But we have not touched on one of the factors ancient figures saw as one of the main threats to a democracy: *demagogues*. What were these, and how did they influence decisions?
2. We've seen that Ancient Athens experimented with democracy. But how effective was democratic Athens? For an attempt to measure the performance of Athenian democracy, see Ober (2010), Chapter 2, and also Thorley (2004).
3. For more interesting historical examples of voting practices, see Ferente et al (2017).
4. Are there interesting voting examples from the history of papal elections?
5. In December, The Guardian released a [ranking](https://www.theguardian.com/football/ng-interactive/2024/dec/03/the-100-best-female-footballers-in-the-world-2024) of the best 100 female footballers in the world. The ranking was obtained by aggregating votes from football experts around the world. The votes are available [here](https://www.theguardian.com/football/2024/dec/07/see-how-every-judge-voted-in-the-100-best-female-footballers-for-2024). How was the ranking obtained? What voting rule did The Guardian use to aggregate the opinions of the voters? What are the pitfalls of this method? What can go wrong? Should they use a different rule?
6. How does IMDB (likely) aggregate votes from viewers to rank movies, e.g., for its Top 250 list? What would be the downsides of whatever method it uses? Is there a better way?
7. We have defined manipulation, or tactical voting, very loosely as altering one's vote in order to influence the outcome. But manipulation can take [many forms](https://en.wikipedia.org/wiki/Strategic_voting), from 'burying', to 'turkey-raising' or abstaining. What method works well for which voting rule? What are likely to be the effects?
8. For a series of case-studies of tactical voting around the world, see Aldrich et al (2018).
9. In the lecture we've seen how many votes a majority (Condorcet, in fact) winner needs in order to also be a guaranteed Borda winner. But what is the lowest Borda score a candidate can obtain, and still be a Condorcet winner? Can the Borda rule elect a [Condorcet loser](https://en.wikipedia.org/wiki/Condorcet_loser_criterion)? Why, or why not?
10. What is the probability of a profile containing a Condorcet cycle (under some assumptions on how preferences are formed)?
11. Many interesting voting phenomena can be illustrated in the [spatial model](https://en.wikipedia.org/wiki/Spatial_voting), particularly through simulations.
12. For a model of how polarization can occur in the spatial model, see Jones et al (2022).
13. What is Siegenfeld & Bar-Yam (2020) about?
14. Describe the argument that the Borda count would have avoided the US civil war, in Tabarrok & Spector (1999).
15. Instant Runoff Voting is claimed to have a moderating effect on politics. Did it do so in Fiji? See Fraenkel & Grofman (2006)
16. For a more theoretical approach to the moderating effect of Instant Runoff Voting, see Tomlinson et al (2024).
17. For an empirically driven approach to studying preferences among voting rules, see Hausladen et al (2024).

# Bibliography
1. Tabarrok, A., & Spector, L. (1999). Would the Borda count have avoided the civil war? Journal of Theoretical Politics, 11(2), 261–288.
2. Thorley, J. (2004). Athenian Democracy (2nd ed.). Routledge.
3. Fraenkel, J., & Grofman, B. (2006). Does the alternative vote foster moderation in ethnically divided societies?: The case of Fiji. Comparative Political Studies, 39(5), 623–651.
4. Szpiro, G. (2010). Numbers Rule. The Vexing Mathematics of Democracy, from Plato to the Present. Princeton University Press.
5. Ober, J. (2010). Democracy and knowledge: Innovation and learning in classical Athens. Princeton University Press.
6. Laslier, J.-F. (2012). And the Loser Is... Plurality Voting. In D. S. Felsenthal & M. Machover (Eds.), Electoral Systems: Paradoxes, Assumptions, and Procedures (pp. 327–351). Springer.
7. Lane, M. (2015). The Birth of Politics: Eight Greek and Roman Political Ideas and Why They Matter. Princeton University Press.
8. Ferente, S., Kuncevic, L., & Pattenden, M. (Eds.). (2017). Cultures of Voting in Pre-Modern Europe. Routledge.
9. Aldrich, J. H., Blais, A., & Stephenson, L. B. (2018). The Many Faces of Strategic Voting: Tactical Behavior in Electoral Systems Around the World. University of Michigan Press.
10. Siegenfeld, A. F., & Bar-Yam, Y. (2020). Negative representation and instability in democratic elections. Nature Physics, 16(2), 186–190.
11. Jones, M. I., Sirianni, A. D., & Fu, F. (2022). Polarization, abstention, and the median voter theorem. Humanities & Social Sciences Communications, 9(1), 1–12.
12. Volić, I. (2024). Making Democracy Count: How Mathematics Improves Voting, Electoral Maps, and Representation. Princeton University Press.
13. Tomlinson, K., Ugander, J., & Kleinberg, J. (2024). The moderating effect of instant runoff voting. AAAI 2024.
14. Hausladen, C. I., Hänggli Fricker, R., Helbing, D., Kunz, R., Wang, J., & Pournaras, E. (2024). How voting rules impact legitimacy. Humanities & Social Sciences Communications, 11(1), 1–10.

