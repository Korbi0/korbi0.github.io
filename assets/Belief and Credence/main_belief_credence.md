---
title: The Normative Pull of Prediction Markets on Our Beliefs and Credences
author: Korbinian Friedl
bibliography: ../../Zotero_library.bib
mainfont: "Century Schoolbook"
linestretch: 1.5
format:
  pdf:
    documentclass: article
    geometry: margin=1in
    number-sections: true
  html:
    css: | 
      body { 
      	line-height: 1.6;
      }
---
# Introduction 

The market price of a bet on "Zohran Mamdani will win the New York City mayoral election" on Polymarket [@2025NewYork] is currently (July 7 2025) 69¢ --- nice.

What should this mean for our doxastic and credal attitudes towards the proposition that Mamdani will win? Is the market price being what it is a reason to believe it? Would it be a reason to believe it if it were higher? Is it a reason to believe a proposition like "The chance of Mamdani winning is 69%"? To set your credence to 69% (or to any other specific or unspecific value)?

These are the questions I will be addressing in this paper; or, more precisely, I will be discussing the general question(s):
Let a bet on a proposition $q$ be an asset $b_q$ that pays \$1 if $q$ and \$0 if $\neg q$; and let $p_q$ be the price of such a bet in dollars.
What---if anything---is wrong with me if my credence in $q$ is different from $p_q$?
Is there a threshold such that there is something wrong with me if I fail to believe $q$ despite the price of a bet on $q$ being above that threshold?

I will sketch a way of thinking about beliefs and credences---inspired by and building upon @macfarlane2025BeliefWhat---and use it to argue for the following answers:

Sometimes, it can be wrong for one's credence in $q$ to deviate from the market price of $b_q$. One such case is an agent who believes in one form or another of the efficient market hypothesis (and believes that the available prediction markets for $q$ are such that it applies), and also believes that they do not possess exclusive information of the relevant kind (where the relevant kind depends on the specific form of the EMH the agent believes).

Clearly, if the threshold view or the Lockean thesis [@jackson2020RelationshipBelief, p. 2-4] about the relationship between belief and credence is true, this will directly entail that market prices of bets likewise exert a normative pull on an agent's beliefs. But the view I will be using does not have this feature. On the contrary, I will use it to argue that it is almost never be the case that the market price of a bet on $q$ is a decisive reason in favour of believing (or disbelieving) $q$ (or $\neg q$).

Before I give a brief summary of the arguments I will be making, a brief note on terminology:
A lot of the argument of this paper turns on the distinction between two normativities, the normativity governing moves in the language game of giving and asking for reasons, and the normativity governing actions properly guided by decision theory (which, I will assume, are exactly those actions for which both doing them, and refraining from doing them, is permitted). I will call the first by the name of "reasonableness", and the second by the name of "rationality\*". I hesitate to call it "rationality", because rationality may have more expansive requirements, or may apply also to other realms of human activity. Hence, it will be "rationality*" in this paper[^2].

My first argument is in support of the positive conclusion that credences sometimes need to track market prices of bets:

### Argument 1
1. An agent's credences are irrational* if they decision-theoretically recommend irrational* actions.
2. Sometimes, betting against the market is irrational*.
3. $\therefore$ Sometimes, an agent's credences need to be such as to not recommend betting against the market.
4. Credences which differ from the market price of a bet on $q$ recommend a bet against the market.
5. $\therefore$ Sometimes, an agent's credence in $q$ needs to be identical to the market price of a bet on $q$.

For the negative conclusion that it is almost never the case that the market price of a bet on $q$ is a decisive reason to think that there is something wrong with either believing or disbelieving $q$, I offer two arguments.

The first one, from belief's relationship with truth:

### Argument 2
1. An agent's beliefs need to answer to the requirements of the social practice of reasoning.
2. One of these requirements is that one should not believe $p$ unless one is aware of a non-defeated reason which speaks in favour of the truth of $p$.
3. The market price for a bet on $q$ can plausibly come about through mechanisms unconnected to the truth of $q$.
4. $\therefore$ M

Another, from being a suitable basis for reactive attitudes:

### Argument 3
1. Belief that $q$ is a suitable basis for reactive attitudes like praising and blaming.
2. If a certain act of praising or blaming is wrong if the price for a bet on $q$ is $p_q$, then it is also wrong if the price for a bet on $q$ is $p_q ± \epsilon$ for any $\epsilon$.
3. If one ought to believe $p$, and $p$ would be a suitable basis for reactive attitude $R$ then it is not wrong to hold $R$ even which it would be wrong to hold if one didn't believe $p$, then it is not wrong to hold $R$.



The core of these arguments is based on the aforementioned view on the relationship between belief and credence based on @macfarlane2025BeliefWhat. It will be developed in section [[#A MacFarlane-Inspired Belief-Credence Dualism]], which will also make clear why and how it motivates premises 1 and 4 in the first argument and premises 1 and 3 in the second as well as premise 1 in the third. 
The remaining premise (premise 2) of argument 1 will be discussed in section [[#A (Rough) Argument for Credences Should (Sometimes) Mirror Market Prices of Bets]].
Premise 2 of argument 2 will not be argued for in (this version of) this paper.



<!-- 
XXX

What---if anything---is wrong with me if my credences don't track the market prices of bets?

I will sketch a specific way of thinking about beliefs and credences and use it to argue for the following answer:

If you *believe* in a specific form of the efficient market hypothesis (and believe that it applies to the prediction market in question), and you believe that you do not possess exclusive information of the relevant kind (determined by the specific form of EMH you believe), then your credence must track the market price of the bet.


What---if anything---is wrong with me if my beliefs don't track (a function of) the market prices of bets? (Where the function in question could be something like a threshold)

I argue that based on my way of thinking about beliefs and credences: Usually nothing.


XXX
This paper argues that we should sometimes set our credences to the market price of a bet, but that our beliefs need not be affected by them.

The argument relies on a specific account of what belief and credence are, whose development will take up the larger part of it. 

1. An agent‘s credences are irrational if they decision-theoretically recommend irrational* actions
2. Sometimes, betting against the market is irrational*
3. ->Sometimes, an agents credences need to be such as to not recommend a bet against the market.

4. An agent‘s beliefs need to answer to the requirements of the practice of reasoning
5. One should not believe $p$ unless one is aware of a non-defeated reason which speaks in favour of the truth of $p$
6. Market prices need not be connected to the truth of $p$
7. -> Market prices need not give one a reason to believe $p$


8. Belief that $p$ is a suitable basis for reactive attitudes like praising or blaming
9. If it would be wrong to hold a reactive attitude which it would not be wrong to hold if one believed $p$; and it is the case that one ought believe $p$; then it is not wrong to hold that attitude. \[as phrases, questionable tbh\]
10. Prediction market prices never make it right to hold a reactive attitude if what is required for it to be allowed to hold that attitude is belief in the proposition being traded
11. -> Prediction market prices 

XXX -->


This paper will develop an account of belief and credence on which the answer to the last question is "sometimes", but to the other ones "no". That is, the market price of a bet on $p$ does not usually give us a reason for or against believing that $p$, or even believing that the chance of $p$ is any specific value; but it does sometimes give us a reason to set our credence in $p$ equal to the implied credence of the market.

This account is inspired by, and can be seen as a version of, the approach to belief and credence sketched in @macfarlane2025BeliefWhat. 


# Belief and Credence

I will be thinking about the concepts of "belief" and "credence" in a methodologically behaviourist way here. That is, I will approach these concepts as theoretical terms, as part of the vocabulary of our psychological theories which need to earn their keep by helping us make sense of, explain and predict the behaviour of human beings. The question to ask, then (along the lines of @macfarlane2025BeliefWhat who this analysis is based on), is: What talents do these concepts bring to the table, and what job should they be given in our psychological theories?

I will start in section [[#The Power of Credence]] by showcasing the utility of the concept of "credence" in describing and explaining human behaviour. I will then move on to describe the two distinctive talents which the concept of "belief" has above and beyond what "credence" can do, and introducing the specific job which MacFarlane has in mind for it in within our theorising of the human being and it's actions in section [[July 2025 Draft for Liam#Belief's Distinctive Talent]]. The result will be a form of belief-credence dualism, whose explanatory power, as well as perhaps counter-intuitive consequences will be showcased in applying it to the "Sleeping Beauty" problem in section [[#Application Sleeping Beauty]].

Section [[#In Search of A Pineal Gland]] will raise the question of whether perhaps this dualism has pulled belief and credence so far apart as to make unintelligible how they interact. It will answer this question by turning to the practice of betting as a bridge between the two attitudes.

## The Power of Credence

Why do we even need credence in our theoretical vocabulary? Isn't belief enough? 

The following example from @macfarlane2025BeliefWhat shows the limitations of belief in explaining human action:

> Sam is walking on a narrow board that spans a shallow ditch. Why is he doing that? Because his lunch is on the other side of the ditch, and he believes that by walking across the board, he will get there. His action is rational in light of his goals and beliefs, and thus we explain it. But now let's consider a similar case, but let the board cross a chasm one hundred meters deep. Now Sam does not cross. Why not? He still wants to get to the other side, and he still believes that by walking across the board, he will get there. Yet, if we make the gap deep enough, it ceases to be rational for him to cross. [@macfarlane2025BeliefWhat, p. 848]

In simple cases, it looks like beliefs and desires do explain (individual) behaviour; but as the example shows, the (binary) concept of belief is lacking in the quantitative structure needed to account for some of the relevant differences in the modified situation. Credence-based decision theory, on the other hand, is able to capture these excellently:

"Suppose Sam's utilities for the various possible outcomes are as follows:

| Outcome                             | Utility |
| ----------------------------------- | ------- |
| Crosses successfully and gets lunch | 1       |
| Stays put and skips lunch           | -1      |
| Falls into shallow ditch            | -1      |
| Falls into deep chasm               | -1000   |
Then, if Sam's credence that he will get across the board without falling is 0.99, the expected utility of crossing is 0.98 in 'Shallow' and -9.01 in 'Deep', while the expected utility of not crossing is -1 in both cases." [@macfarlane2025BeliefWhat, p. 848]

Consequently, what the role of credence in or psychological theorising should be, is the following: We describe an agent as having a certain set of credences iff those credences in fact decision-theoretically rationalise and explain their actions: Credences are those internal states which disposes one to make the decision which maximises the utility one expects based them.

I add that we should judge a set of credences "irrational*" if it disposes one to irrational* actions---where the paradigm case of an irrational* action is to knowingly enter into a Dutch Book. 

## Belief's Distinctive Talent

So the concept of "credence" proves its worth in rationalising and explaining those actions which are properly seen as governed by decision theory. Do we additionally need a concept of "belief"? Or can credence do everything we need in cognitive psychology?

Perhaps saying "A believes $p$" is simply an imprecise way of saying that A has a high credence in $p$? If this were so, it would explain why "belief" continues to be used in everyday language. But it wouldn't vindicate it as a scientific term. As MacFarlane writes, "just as we don't do physics with vague concepts like *tall*, we won't do psychology with *belief*" [@macfarlane2025BeliefWhat, p. 849].

Similarly unsatisfying are accounts on which belief serves to simplify cognition and thereby make it computationally tractable (such as @staffel2019HowBeliefs, @ross2014BeliefCredence). If, as @ross2014BeliefCredence write, belief in a set of propositions is "a *defeasible* or *default* disposition to treat them as true in our reasoning" [@ross2014BeliefCredence, p. 267], we would face the question of what MacFarlane calls "dual control": Whether the defaults are in charge or are to be departed from would depend on the risks and stakes of the situation, as captured by credences and utilities. But then it seems like credence-based cognition has to constantly supervise the simplified reasoning. The required computations would not be reduced, but rather increased, if the two are thought to run in parallel in this way [@macfarlane2025BeliefWhat, p. 851].

What these two have in common is that they inevitably lead to "belief" and "credence" competing for the same theoretical task---and for a task at which "credence" would inevitably be simply better. If credence reductionism is to be resisted, then, belief needs to find a job "in a different line of work altogether" [@macfarlane2025BeliefWhat, p. 851]; one which makes use of belief's distinctive skill set.

What is this distinctive skill set? MacFarlane identifies two qualifications in particular which "belief" brings to the table and which "credence" cannot match:

First, belief has *truth* as its correctness condition. If $p$ turns out not to be true, then belief that $p$ was wrong. Whereas even arbitrarily high credence in $p$ may not be proven wrong by $p$ being shown not to obtain---even credence 1 does not, strictly speaking, rule out $\neg p$. As @williamson2020knowledge points out with the example of a (countably) infinite series of coin tosses: we certainly should have credence $1$ in the proposition that at least one of them will come up tails[^6]; and this credence will not have shown to have been wrong if---which is possible---not a single toss does come up tails.[^5]

Second, belief---unlike credence---can serve as the basis for certain reactive attitudes, as described by @buchak2014BeliefCredence : I cannot resent you for stealing my phone unless I believe you did. Credence, even an arbitrarily high one, is not enough.

With these talents, belief shouldn't try to compete with credence in explaining why individuals choose one permitted action over another. They qualify it for a different job: ascribing beliefs to individuals is crucial for the description of another realm of human activity, namely the social practice of reasoning [@macfarlane2025BeliefWhat, p. 855].

We ascribe to an agent the belief that $p$ if $p$ is for them a candidate reason---if, under suitable circumstances, they would assert $p$ in the language game of giving and asking for reason and thereby assume responsibility for its truth, in the sense of: having reasons for thinking the sentence is true and being willing to provide these reasons upon request.

Believing is crucially intersubjective, and bound up with reasoning about the world in language, in a way in which having a credence is not. I want to illustrate this point from two directions:
first, in the way MacFarlane does, who provides broadly cog-sci arguments as to why intersubjective communication requires a coarser grained attitude (compared with an individual's internal credal state).
And then, in a more speculative philosophical way, drawing on Donald Davidson, who writes about the connection between participating in a practice of linguistic communication about what is true and the very availability of the concept of objectivity.

First, the MacFarlanian point: the norms of credence, which for him are just the synchronic and diachronic Bayesian requirements of probabilism and conditionalization, "demand an equilibrium of a very large number of mental states". He theorises that "[p]resumably we can attain this, at least approximately, in our own thought, because we have subpersonal mechanisms that are sensitive to irrationality" [@macfarlane2025BeliefWhat, p. 858]. But in coordinating with others, in settling on a shared picture of the world and a shared sense of what there are and aren't reasons for, "everything has to be under personal-level control" (ibid.). He says to "think of belief and reasons as *digital*, in contrast to the *analog* distinctions involved in credence and rationality" (ibid.). The digital version of an analog signal loses some detail, but what it gains is the ability to be communicated efficiently and reliably---"a digital signal can be copied exactly, whereas an analog signal cannot". In line with this picture, on which the purpose of reasoning is to, in some sense, do a slightly worse version of what an individual's brain does sub-personally, MacFarlane views solitary reasoning as derivative of the more primordial practice of social reasoning: He cites @mercier2017EnigmaReason, who write about their experimental results as confirming that people reasoning on their own do so "anticipating a dialogical context, and mostly to find arguments that support their opinion" [@mercier2017EnigmaReason, p. 61].

In a certain sense, MacFarlane *does* here end up saying that belief simplifies in a suitable way, just like @staffel2019HowBeliefs or @ross2014BeliefCredence, whose views he rejected earlier; but while e.g. @staffel2019HowBeliefs points to some complexity-theoretic results like @cooper1990ComputationalComplexity's[^4] to argue that the individual's brain cannot be expected to perform the computations required for updating the individual's credences, MacFarlane's argument seems to rather point in the direction of information-theoretic results like the noisy channel theorem, and the fact that, with in a conversation, the number of premises that can be considered and whose reason-relation on a question under consideration can be taken into account is strictly limited in a way that an individual brain's holistic updating procedure need not be.

Donald @davidson1982RationalAnimals, in a much-hated paper which I, however, love, even though it is, objectively, a little bit of a mess, writes on language being required for the having of beliefs. Core to the concept of belief, he argues, is that it is a state of an entity that can be true or false, correct or incorrect (it differs, I might add, from credence in that way). Essential to the concept of belief is the contrast between what is subjective and what is objective (or, which to Davidson is the same, intersubjective). Any being engaged in linguistic communication has this command of the subjective-intersubjective contrast (and therefore of the concept of truth): for having a conversation with another person entails having a concept of a shared world which both conversation partners are talking about. To understand the other person's utterances, I must think of her world being the same as my world. Communication requires that my sentences and the sentences of my interlocutor have the same subject matter; and disagreement is only possible against a backdrop of many shared beliefs about that subject matter. Having a concept of such a shared world is the same as having a concept of truth and falsity of the internal states that correspond to one's linguistic utterances, since a belief that $p$ is true iff $p$ (iff $p$ is the case in the world).
To illustrate the situation of a being which does not participate in such an activity Davidson paints the following picture:
imagine you are fixed in place and unable to move. It is thus impossible for you to determine the distance of many objects. You know on which line through yourself they are, but not at what distance---it would be impossible to distinguish between certain small objects which are close by and large objects which are far away.
Not being fixed in place, you are able to triangulate. From the difference in the way an object appears to you when you move a bit to the left or the right, you can infer how far it is from you.
Now, he suggests that our sense of objectivity is itself an effect of an ability to triangulate; not triangulating a spatial object qua spatial object by moving in space, but triangulating an object qua object by accessing another subject's perspective on it by talking about it with them. The very distinction of thing-for-me and thing-for-everyone (i.e. object in the proper sense) is only opened up by interacting with another subject in a particular way: communicating with them about the object in language. [@davidson1982RationalAnimals, p. 105]

It is this activity, the activity which human beings engage in with each other to construct a shared objective world about which true and false things can be said, that makes the addition of the concept of "belief" to our psychological vocabulary necessary: while the behaviour of human beings as utility maximizers can be described and explained using credence alone, the behaviour of human beings as social reasoners can not. The making of an assertion is an assumption of responsibility for the truth of the asserted content (where this responsibility includes having reasons for thinking the sentence is true and being willing to provide and discuss them); and we use the concept of "belief" to describe and explain what kind of assertions someone is disposed to make.

Based on this account of belief, we can also explain why belief, unlike credence can serve as the basis for reactive attitudes: What certain reactive attitudes (like resentment, blame, pride or shame) require is precisely a *reason*. Unlike some other moods (like sadness), for these attitudes it always makes sense to ask (a version of): "Why do you feel proud?" / "Why do you blame Jones?"---and it would be incoherent to reply something along the lines of: "No reason, I'm just feeling proud" [@macfarlane2025BeliefWhat, p. 856].


## The Respective Normativities of Belief and Credence

The above is an outline of when we should ascribe beliefs and credences to an agent; it doesn't yet say anything about what beliefs or credences an agent should have, or, conversely, under which circumstances an agent can be criticised as *unreasonable* for the beliefs she holds or as *irrational\** for her credences.

In line with our basic methodological behaviourism, we have defined these terms with reference to the kinds of behaviours which are their characteristic expression; action guided by decision theory for credence, and moves in the language game of giving and asking for reasons for belief. For each of these areas of human activity, there is a pre-existing normativity governing them. I will argue that the internal states of belief and credence inherit the normative status of the actions which are their characteristic expression: Since credence just is that internal state which makes one choose certain actions in certain situations, we will call it irrational* if the actions it makes the agent choose are irrational*. Likewise for belief: Since to believe $q$ is to treat $q$ as a candidate reason in conversation, believing $q$ is irrational if it unreasonable to treat $q$ as a candidate reason.

The paradigm example of an irrational* action I will consider to be: Entering into a set of bets which the agent recognises to jointly guarantee a loss of utility. It can never be rational* to give away utility for nothing, if keeping it is also permitted. Consequently, a set of credences is in any case irrational* if it makes one susceptible to a Dutch Book.

The language game of giving and asking for reasons includes a number of norms; for the application of the framework I am about to discuss, one is particularly relevant:
 I assume that the language game of giving and asking for reasons includes some norm like "If you asserted $p$ yesterday, and had good reasons for it, and have not become aware of any new reasons bearing on the truth of $p$; then you are still committed to $p$."
## Application: Sleeping Beauty

\[Write the whole sleeping beauty thing here\]
## In Search of A Pineal Gland

MacFarlane, in summarising the division of labour he has in mind between the concepts of "belief" and "credence", emphasises the relative independence between rationality and reasoning:

> *Reasoning* is the process of producing, assessing, and criticizing reasons. So understood, reasoning has only a tenuous relation to rationality. *Rationality*, as I understand it, is a matter of the internal coherence of one's attitudes, both synchronically and diachronically. This is what Bayesian epistemology and decision theory attempt to give an account of. One can be rational without ever reasoning, and without ever regarding anything as a reason. Conversely, reasoning---even good reasoning---does not necessarily make one rational. [@macfarlane2025BeliefWhat, p. 855]

Putting it this way, we are of course presented with the question---what is reasoning good for? MacFarlane's answer: "Coordinating with others" [@macfarlane2025BeliefWhat, p. 863] which, as discussed above, requires suitable coarse-graining.

But part of the story is missing: How does the coordinating affect the individual's actions? MacFarlane seems to be in a precarious position here:
to the extent that the result of the communication is the formation, in the individual, of new beliefs, these beliefs should never feature in an explanation of that individual's actions---that is credence's job! And belief should not interfere with it, since it's talents do not qualify it for this job.
But a story of how beliefs affect credences is lacking---and in fact the above quote seems to suggest that, in general, they do not.

Well, somehow they have to. There needs to be a pineal gland which connects the realm of credence and the realm of belief, on pain of casting the whole practice of reasoning as an epiphenomenon.

In this section, I want to suggest such a "pineal gland", a point where belief and credence do meet; I want to suggest that they do in the practice of betting. The result will be a view where reasoning is in a sense primary: certain choices of an agent will be seen as a reason to call that agent irrational*, and irrational* is something one *should not be*; thus reducing the normativity governing credences to the power of belief-based reasoning to determine what one should and shouldn't be or do.

A natural point to start when looking for a point where beliefs affect credences is conditionalisation, which may be framed as saying: If you have the belief that $p$, set your credence in $q$ to $Cr(q \mid p)$.
A drawback of just running with this is that it would seem to entail that one ought to have credence 1 or 0 in anything which one has a belief about (since probabilism requires $Cr(p\mid p)=1$)---a view which is widely rejected, and, I think, for good reasons. It seems perfectly fine to assert something without thereby committing oneself to betting on it *at any odds*.

\[...some kind of transition...\]

Successful execution of a bet between to people from start to finish involves and connects both decision theory and reasoning, both credence and belief (I take general latent awareness of this fact to be the reason why Dutch Book arguments are often used to convince people of Bayesianism, and, as I will expand on later, are in fact the only correct justification of it). An individual's action within such a process is guided, at times, both by decision theory and by the normative requirements to which one is subject as a reasoner (and thus, believer). The way these are connected through a (real or imagined) bet will impose indirect epistemic requirements on credence, even if the only direct normative requirements on credence are pragmatic.

Any agreement which we might want to call a bet on $p$ is a bet on $p$ iff the parties share an understanding that the pot should be awarded to the person who bet on $p$ iff $p$. By entering into a bet on $p$, I commit myself to the this proposition. When it is time to settle the bet, what is required is for the parties to reach agreement on a belief about $p$.

Based on this understanding of a bet, I want to propose what I call the *Betting Norm*, which I take to be more fundamental than the "Dutch Book" norm (and, in fact, explaining it)
> *Betting Norm*: If you are invited to enter into a (set of) bet(s); if you believe that $\phi$ will be the only reasonable thing to believe at the time the bet is to be settled (by which I mean: it will not be a tenable position to deny $\phi$ at that time); and if $\phi$ being true implies that the payout on the (set of) bet(s) you are being offered should be such that you lose money: Then it is irrational* to enter into these bets, which means you should not do it.


\[...spell out how Dutch Books are of the form "if $\top$, you lose money", so that even though you do not know which contingent proposition will be the only reasonable one to believe, you do know that it will be untenable to deny $\top$, so that the Betting Norm explains why you should not enter into Dutch books...\]


\[... spell out how this motivates conditionalisation without committing one to the above view that credences in believed propositions have to be 1; this will work via the distinction between "I believe that $p$" and "I believe that $p$ will be the only reasonable thing to believe" (i hope)...\]

- One way in which beliefs affect credences is conditionalization: Coming to believe that $q$ should have the effect of your credence in $p$ changing to what used to be $Cr(p \mid q)$.
	- Does this imply that I should have Credence 1 or 0 in every proposition about which I have a belief? Because rationality* requires that $Cr(p \mid p)=1$ and $Cr(p \mid \neg p)=0$.
	- Getting a bit ahead of myself, but relatedly: Does my approach commit me to saying I should bet at arbitrary odds on any proposition which I do believe?
	- It seems that where MacFarlane pulled belief and credence too far apart, my "fix" is tying them too closely together
	- I guess a solution would be to require withholding belief about future contingents.
	- But what about bets about past events (but which happen to be unknown to both me and my betting partner).
	- Perhaps the distinction between "I believe $p$" and "I believe that $p$ will be the only reasonable thing to believe once \[time $t$ arrives\] or \[we look at the decisive evidence\]" is relevant here. I do believe the non-contingent fact about the future that either $r$ or $\neg r$ will come to pass; and I believe that in each scenario, it will be either $q$ or $\neg q$ which will be the only reasonable thing to believe; though I do not yet know which one it will be.
- I want to say that the way beliefs affect credences in conditionalization is derivative of the way the two attitudes intersect in the practice of betting.
- Successful execution of a bet from start to finish involves and connects both decision theory and reasoning, and thus credence and belief. An individual's action within such a process is guided by both forms of normativity, and in a way which makes clear how what we (anticipate to) believe will impose indirect epistemic requirements on credence even if the only direct normative requirements on credence are pragmatic. If my description of the practice of betting is right, then what I will call the "betting norm", can be seen as even more fundamentally constraining our credences than the "Dutch Book" norm which I have thus far been working with, and in fact explaining it: If you believe that $\phi$ will be the only reasonable thing to believe at the time when the bet is to be settled (where by this I mean: it will not be a tenable position to deny $\phi$), and if $\phi$ being true implies that the payout on the bets you consider entering into should be such that you lose money: Then do not enter into these bets. 


- The betting norm says: 
- Bets with nature

# Prediction Markets

## A (Rough) Argument for: Credences Should (Sometimes) Mirror Market Prices of Bets

The different forms of the efficient market hypothesis provide reasons not to expect to be able to "beat" the market, i.e. not to expect to know better than the market what the value of an asset is --- with the weak form implying that you shouldn't expect to be able to beat the market if all the information you have access to is historical information about the asset's price; the semi-strong form suggesting that unless you have access to non-public information, you should expect to lose money if you bet against the market and the strong form suggesting that you should always expect this. 

Now assume you find yourself in a situation like this, where you do not expect yourself to be able to win a bet against the market, and where the asset in question is a bet on $p$.
If your credence in $p$ was anything other than the market price of the bet on $p$, on the above framework you would be committed to entering into a bet against the market. So, by modus tollens, you do not want your credence to be anything other than the market price of a bet on $p$.


<!-- XXX
I need an additional principle to the betting norm for this.
Something that also explains a) why I sometimes have reason not to want to bet against an expert and b) if this is the case I need to set my credence to theirs.
I am sure there is something in the literature on this?

It needs to be a principle like: \[under circumstances to be specified\] you cannot both reject a bet against someone and deny that their credence is more rational* than yours....

I mean on the account, it is either the case that bot accepting and rejecting the bet is permitted, or it is the case that one of the two is obligatory.

If both accepting and rejecting is permitted, then an acceptance or rejection of a certain bet just is the best kind of evidence we can get about the agent's credences. If they reject a bet on Mamdani winning at 69c, and if they simultaneously reject a bet against it, then the only explanation is that their credence and utility function are such that their credence is close enough to 69% and their utility function concave enough that they would just rather keep their save asset than exchange it for an uncertain one.
If, in another context in their life, they act in a way that would suggest a different credence, then they are
- what exactly? it's not like they are susceptible to a dutch book, right?
	- Or are they? are they committed to both buy a bet at 69 and sell a bet at (e.g.) 60?
	- probably that is the way to go, to frame it like that
	- make sure my account is such that it comes out like this
	- the way to do this is via the account of how bets with nature relate to bets with people
	- \[probably there is also literature on this, on the irrationality of accepting and rejecting the same bet based on presentation?\]
So rejecting to bet against the prediction market commits you to, in other contexts of your life, also act as if your credence is sufficiently close to the market's credence



XXX -->

## (Rough) Argument(s) for: Belief Should Not Usually be Affected by Market Prices of Bets

On the other hand, does the fact that the market price of a bet on $p$ is $c$ have any normative pull on your doxastic state regarding $p$ (i.e. on the question of whether to believe or disbelieve $p$)?

A special case is of course a proposition $p$ which itself talks about, or stands in any logical relationship to, the market price of a bet on it[^1]; in which case the answer is yes. But these seem so weird as to in general be irrelevant.

Here are some arguments for "no, the market price has no normative pull on my believing or disbelieving $p$", based on the two main features of belief [[@macfarlane2025BeliefWhat]] (and I) have been emphasising:
- *Correctness Condition*: The market price comes about by individual's decisions to purchase bets. These are entirely based on these individuals' credences, which, as shown above, do not necessarily have anything to do with the proposition's truth. For example, the market price of a bet on $HEADS$ among participants of the "Sleeping Beauty" experiment would be 1/3; but we agreed that the correct belief about the chance of $HEADS$ cannot be 1/3.
- *Role in Reactive Attitudes*: It doesn't seem to be the case that an arbitrarily high market price of a bet can ever justify a reactive attitude like resentment. Again, considering a hypothetical market whose participants are in the relevant kind of scenario---if, in a large room, everyone has a rationally (arbitrarily) high credence in "Jake stole the phone", without anyone believing that Jake did it, because there are no appropriate reasons available for believing this; and if a prediction market was run in this room on "Did Jake steal the phone?", then the market price would be equal to the median credence, which, by stipulation, is arbitrarily high. Yet if anyone formed a belief that Jake did it on the basis of this price, they would do so without any reason known to anyone that would be suitable to justify such a belief.
- Overall, the market price is problematically inert in reasoning: It does not talk or justify, does not participate in the social practice of reasoning. Where it may be justified to form a belief on expert testimony if one interprets such testimony as a kind of promissory note for reasons available upon request (and expert status as reason to expect these reasons to be good), no such reasons could be requested from the market---because, as the two above scenarios show, it is possible that no such reasons even exist or are known to anyone.

<!-- # Ideas still to be incorporated
- A practical reasoning first approach, which has the following structure: Decision theory says whether an action is rational or irrational. It being rational is a reason for doing it. It being irrational is a reason against doing it. These reasons are usually decisive; but if it is the case that eg $A$ is deontically required, this reason undercuts the „rationality“ reason.

 -->



[^1]: Such a $p$ could be a proposition like "The market price of a bet on this proposition at time $t$ will be $c$." or "There is a market for bets on this proposition." But such self-referential markets would be strange enough as to wonder whether, with regard to the rationality of their price, all bets are off anyway.

[^2]: As MacFarlane, who I am following here, writes—though he sticks with using the word „rationality“ even in the face of such considerations: " I am rejecting a long philosophical tradition of thinking of rationality as the faculty for apprehending and responding to reasons. I'm even going against etymology, which derives 'rational' from *ratio*, reason. But one kind of philosophical progress is the recognition that there are two distinct things which we confused before" [@macfarlane2025BeliefWhat, p. 857].

[^3]: In his paper, Easwaran offers a purely belief-based solution to said paradox, which retains the structure of the Bayesian solution and can in fact be expressed in Bayesian terms---assuming an epistemic agent to value a true belief at value "R" and to disvalue a false belief at value "W", he shows that a set of beliefs is "strongly coherent" iff there is some set of credences that would decision-theoretically rationalise choosing to believe each of the beliefs over choosing not to believe it; that is, if there is a probability distribution $P$ such that for each proposition under consideration $q$, $P(q) > \frac{W}{W+R}$ (where a set of beliefs is defined to be "strongly coherent" iff there is no other set of beliefs that weakly dominates it in the sense of yielding at least as high value in every possible situation). His results thus show that, when confronted with a preface paradox situation, any doxastic state that can be modelled as arising from a credence distribution plus a threshold rule with threshold $\frac{W}{W+R}$ is strongly coherent.

[^4]: Which she reports as "probabilistic inference, including conditionalization, is NP-hard". What @cooper1990ComputationalComplexity in fact shows is that general probabilistic inference is NP hard *if the probability distribution is represented in the form of a Bayesian network*. She does not cite any evidence to the effect that the human brain does in fact represent its credence distribution in this particular way.


# References

[^5]: Or consider selecting at random (sampling from a uniform distribution) a real number in the interval $[0,1]$, and the event "the selected number is rational". There are rational numbers in this interval; in this sense the event is possible. But the set of rational numbers in $[0,1]$ has measure zero; the probability of picking one is therefore 0.

[^6]: Assuming that for each coin toss, we have credence 1/2 that it comes up "heads" and 1/2 that it comes up "tails", and that the coin tosses are independent, probabilism commits us to assigning credence $\frac{1}{2}^n$ to the event "the first $n$ coin tosses all come up 'heads'". As $n$ approaches infinity, this credence will therefore approach 0 and the credence that at least one of the first $n$ tosses was "tails" 1.
