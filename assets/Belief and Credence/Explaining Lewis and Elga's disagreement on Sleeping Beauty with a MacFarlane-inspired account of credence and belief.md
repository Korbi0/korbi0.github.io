
It is Sunday and SB is about to be put to sleep. They will be woken up on Monday, briefly interviewed, and put back to sleep. A fair coin will be flipped: If it comes up $TAILS$, a memory loss potion will be administered, which will make SB forget Monday's events, and SB will be woken up again on Tuesday, and interviewed again. SB is told all this.

Upon being woken up, what should SB's stance be on the probability of the coin flip coming up $HEADS$?

Two paradigmatic positions on SB are due to David Lewis and Adam Elga, respectively:

Lewis argues based on what he dubs his premise (L1), which says that only relevant evidence produces a change in credence; and that SB receives no such evidence regarding $HEADS$ by being woken up; that, therefore, their credence in $HEADS$ ought to remain what it was on Sunday: 1/2.

Elga's argument (in Lewis' reconstruction) rests on premise (E1), that SB's credence in $HEADS$ would have to be 1/2 if they were told that it is Monday (and, therefore, that the coin flip is still in the future).
Reasoning backward from this, Elga argues that the evidence of being told it is Monday can only lead to credence 1/2 if prior to having this information, SB's credence in $HEADS$ was 1/3.


This paper wants to propose a new perspective on the dispute, one inspired by, and based on a modification of, John MacFarlane's recent paper "Belief: What is it good for?", and focussing on the respective normativities governing credence and belief.

MacFarlane argues for a new division of theoretical labour between the concepts of "belief" and "credence", giving the latter the job of rationalising and explaining action (insofar as it is guided by decision theory), and the former the job of keeping track of potential reasons as part of a social practice of communication. I will describe the MacFarlaneian framework in section \ref{sec:macfarlane} and then modify and extend it somewhat in section \ref{sec:extendingMacFarane}. Based on the extended framework, I will give a new assessment of SB: It will side with Elga in saying that SB's credence certainly should be 1/3, and claim that Lewis' disagreement with Elga is to be explained by his mixing up the norms governing credence and those governing belief. 

Lewis' own explanation of the disagreement is that Elga misapplies the principal principle (PP), which says that credences should conform to known chances unless one has access to what Lewis calls "inadmissible" evidence (e.g. a prophet's testimony on the outcome of a future chance event). Elga gets this premise (E1) from an application of the principal principle. But, says Lewis, PP is inapplicable here because being told that it is Monday constitutes inadmissible evidence from the future for SB---"namely that she is not now in it"(Lewis, 175).
On the picture I will paint, however, there is a principle more fundamental than the principal principle governing our credences: The principle of avoiding sure losses / dutch books (DB). It stems from the close connection between credence and decision theory, and the idea that it is irrational to give away one's money for nothing. It is to this principle that the principal principle must answer, and to which it must defer if there are any disagreements---and if (DB) already nails our credence down to a unique value, (PP) need not be consulted at all.
(In fact, disagreements between DB and PP should be taken as evidence that PP does not, in fact, capture all there is to say about chance, though this paper will not be able to pursue the implications for PP's status as an explication of chance).
Lewis may or may not be right that SB receives information from the future when they are told that is Monday; and therefore Elga may or may not be wrong to use PP to get (E1). But I claim that he *shouldn't* appeal to PP for this premise, because a more fundamental principle also supports it.

If I agree with Elga's conclusion (even if not his way of getting there), I should give my own explanation for what Lewis gets wrong. I will do so in section \ref{sec:Lewis}


# MacFarlane on Belief and Credence \label{sec:macfarlane}

Before I dive into MacFarlane's account of belief and credence, a brief remark: Though I don't think MacFarlane takes an explicit stance on this, I will develop a methodologically behaviourist reading of his paper. His emphasis on, and approach to the topic from the vantage point of, the *theoretical* usefulness of the concept of belief at least suggest such a reading. On this reading, then, we will accept a psychological concept if it is a part of our best psychological theory, where the latter is to be judged by its usefulness in explaining observable human behavior. 


Does our best theory of human psychology have need for both the concepts of "credence" and "belief"? MacFarlane begins his paper by showcasing the superior capabilities of "credence" to rationalize and explain action, compared to belief. He does this using the following example:

"Sam is walking on a narrow board that spans a shallow ditch. Why is he doing that? Because his lunch is on the other side of the ditch, and he believes that by walking across the board, he will get there. His action is rational in light of his goals and beliefs, and thus we explain it. But now let's consider a similar case, but let the board cross a chasm one hundred meters deep. Now Sam does not cross. Why not? He still wants to get to the other side, and he still believes that by walking across the board, he will get there. Yet, if we make the gap deep enough, it ceases to be rational for him to cross." (MacFarlane, 2023)

In simple cases, it might look like beliefs and desires do explain (individual) behaviour; but as the example shows, the (binary) concept of belief is lacking in the quantitative structure needed to account for some of the relevant differences in the modified situation. Credence-based decision theory, on the other hand, is able to capture these excellently:

"Suppose Sam's utilities for the various possible outcomes are as follows
$$
\begin{table}[H]
\centering
\begin{tabular}{lr}
\toprule
Outcome & Utility \\
\midrule
Crosses successfully and gets lunch & 1 \\
Stays put and skips lunch & $-1$ \\
Falls into shallow ditch & $-1$ \\
Falls into deep chasm & $-1000$ \\
\bottomrule
\end{tabular}
\end{table}
$$
Then, if Sam's credence that he will get across the board without falling is $0.99$, the expected utility of crossing is $0.98$ in *Shallow* and $-9.01$ in *Deep*, while the expected utility of not crossing is $-1$ in both cases."

I take the implied role of credence, then, in our best psychological theory, to be the following: We describe agents as having a certain set of credences *iff* those credences in fact, decision-theoretically, rationalize and explain their actions. Credence is the internal state that disposes one to make certain decisions as specified by decision theory.

I will add that we should judge a set of credences to be *irrational* if it disposes an agent to irrational actions, with the latter being the more primitive concept. I will not give much of a substantive account of what makes an action irrational; what I will say, though, is that entering into a Dutch Book is a paradigmatic example. Therefore, though there may be others, the chief principle of rationality I will assume in this paper is "don't be susceptible to a Dutch Book".

Going back to the question of which concepts we need for our best psychology: Based on the superior ability of credences to explain and rationalize behavior, we are definitely going to want to have "credence" in our theoretical vocabulary. But do we, additionally, need "belief"?

Some reasons for keeping "belief" with "credence" already available, which MacFarlane rejects, are:
- "To say of someone that they 'believe' $p$ is just an imprecise way of attributing a high credence to them" (Macfarlane, 2023, 3). Though this would explain why the concept is useful in everyday language ("nobody would claim that we have to throw away the concept of *tall* once we learn *centimeter*" (ibid.)), it would not be of theoretical use: "just as we don't do physics with vague concepts like *tall*, we won't do psychology with *belief*" (ibid.)
- Human minds form beliefs about propositions they are uncertain about to achieve computational tractability, where belief that $p$ is "a *defeasible* or *default* disposition to treat them as true in our reasoning" (Ross and Schroeder, 2014, 267, as cited in MacFarlane, 2023). But how does the mind determine when these defaults are to be departed from? It seems that that would have to depend, again, on the risks and stakes of the situation, as captured by credences and utilities, so credence-based cognition would constantly have to supervise the "simplified" belief-based one---it is unclear how such a "dual control" setup could constitute a real simplification (MacFarlane, 2023, 5)

What these have in common is that they would inevitably lead to belief and credence competing for the same task. And on all of the above accounts, that task is one that credence would simply be better at. If credence-first reductionsim is to be resisted, belief needs to find a job "in a different line of work altogether" as MacFarlane keeps saying. And he has such a job lined up, and one which fits "belief"'s distinctive skill set (which for MacFarlane consists in particular in being indispensable for certain reactive attitudes and having *truth* as its correctness condition).

Instead, he centers the social practice of *reasoning* as the one we cannot properly make sense of without ascribing beliefs to individuals, which he defines as "the process of producing, assessing, and criticizing reasons" (MacFarlane, 2023, 9).

Reasoning and rationality are not the same, or even necessarily connected: "One can be rational without ever reasoning, and without ever regarding anything as a reason. Conversely, reasoning---even good reasoning---does not necessarily make one rational" (MacFarlane, 2023, 9)

To be a candidate reason for something, $p$ must be a fact. Thus, MacFarlane defines his concept of belief: "To take something to be a candidate reason is to take it to be a fact. Taking something to be a fact is believing it. Indeed, factuality is the basic correctness condition for beliefs: if $p$ turns out to be false, then however probable it was and however well supported by the evidence, a belief that $p$ was incorrect."

# Extending and modifying MacFarlane \label{sec:extendingMacFarane}


I think that MacFarlane's account of belief tells a very compelling story about the social practice of theoretical reasoning, taking place in communicating with one another by asserting and suitably revising beliefs.

Where it gets murky is when we think about the status of practical reasoning.

In a first pass, we might be lead to believe that practical reasoning has no place at all in MacFarlane's framework. After all, what practical reasoning does is explain and rationalize actions by giving reasons for them. But explaining and rationalizing actions, that is credence's job!

What, then, *are* we doing when we say that Sam is crossing the chasm on a narrow board because his lunch is on the other side and he believes he can reach it by walking across the board?

The only answer I see is that we are just not, strictly speaking, telling the truth (according to our best psychology). Strictly speaking, Sam *did not* cross the chasm because he believed he could reach his lunch that way. He did because his credences and utilities were such that that was an action with positive expected utility. (MacFarlane, at certain points, seems to suggests that practical reasoning would be an alternative way of deciding on actions, just a less effective one (see his PayPal example / footnote 17). But it seems that if we want to commit to the view that it is always credences which explain actions, and belief should take care not to interfere with another theoretical term's line of work; and commit, as methodological behaviorists about internal states, to ascribing to the agent whichever credences in fact explain their behavior, this path seems blocked.)

So while it is not clear to me whether MacFarlane does, I would be inclined to double down on denying the reality of practical reasoning (at least not as part of the descriptive vocabulary of our best psychology).

Likewise, I would double down on giving behaviourist subjective Bayesianism free reign in the realm of credences: You have whatever credences explain your action, and the only reason for calling your credences irrational is if they commit you to irrational actions.

And on the explication of what irrational action is, I want to say that the primary irrational action is accepting a Dutch Book.

%%Another question MacFarlane leaves me with is: What exactly does the social practice of reasoning look like qua *social* practice? What exactly are the individual motions social reasoners go through when they are reasoning socially, and how exactly do beliefs explain these?
I can only imagine that it is interaction through language and speech acts that we are supposed to have in mind here, in particular assertion. On the only level at which reasoning is genuinely social, when it is done in conversation, people exchange reasons by asserting them. Perhaps simplifying a bit, I would thus say that we should ascribe belief that $p$ to a social reasoner if they would, under suitable circumstances, be disposed to assert $p$ while reasoning socially. Like for credences, I would say that belief inherits the normative status of the act to which it disposes the holder: If it would be unreasonable to assert $p$, then it is unreasonable to believe $p$.%%

On the other side, what determines whether a certain belief is (for lack of a better word) *reasonable* to hold? Regarding the normativity of believing, MacFarlane tells us only that if $p$ turns out to be false, a belief that $p$ was incorrect. But a richer normativity of believing seems to build on that, as inherited from the normativity of the social practice of reasoning. If I take $p$ as a candidate reason, I cannot also so take $\neg p$. If I am on the record as believing $p$ and $p \rightarrow q$ to be candidate reasons, then I must also go where the reasoning leads and accept $q$ as a candidate reason. In general, I take it that "belief" is connected to judgment, i.e. the assuming of a certain responsibility for the truth of the proposition which one judges to be true, whereas in this regard it is "anything goes" for credence. One is not subject to criticism for having had an arbitrarily high credence in a proposition that turned out false (even a credence of 1, as MacFarlane, following Williamson, emphasizes, does not exclude 's being false). It is not appropriate to resent someone, or exclude them from conversation, for having a high credence in  even in the face of strong evidence against (you can take all their money by betting against them, but you cannot hold an epistemic grudge). But it is appropriate to resent someone and exclude them from conversation if they don't give up on their belief in $p$ in face of a proof that $\neg p$.

# Application to SB

How should we think about Sleeping Beauty on the above framework? Well, seeing as it represents a strong form of belief-credence dualism, we should ask two questions separately: What should SB believe? And what should SB's credence be? The answers to these two questions will be guided by the respective norms governing credence and belief, i.e. credence's decision-theoretic implications on the one hand, and belief's embeddedness in a web of reasons on the other.

## SB's credence has to be 1/3
Whatever else may be required of rationality, I take violation of the norm "don't be dutch-bookable" (DB) to be sufficient for irrationality.


Therefore, I take the Dutch Book (due to Hitchcock, 2004) against any SB whose credence, upon being woken up, is 1/3, to prove that SB cannot avoid being called irrational unless their credence is 1/3. Hitchcock gives the fully general formulation (against any SB with credence different from 1/3); but for simplicity's sake, I will here just recount the DB against SB with credence 1/2:

On Sunday: Bookie offers SB a bet on $TAILS$ which pays 30 for the price of 15. This will be considered fair by SB since their credence is 1/2 (bet #1)

Any time SB and bookie are woken up: Bookie offers SB a bet on $HEADS$ which pays 20 for the price of 10. This will be considered fair by SB since their credence is still 1/2. On the guaranteed waking on Monday, this will result in a bet being made (bet #2); if the coin lands $HEADS$, it will happen a second time on Tuesday (bet #3).

xxxPayoutTablexxx

N.B.: Bradley and Leitgeb (2006) argue that Hitchcock's argument rather shows that credences and betting odds come apart. This is a route fundamentally unavailable on the framework I have been sketching (because decision theory is credence's core and only job). But contrasting the picture I have been painting with theirs is illuminating: Where for them, it is the epistemic interpretation of credence that is non-negotiable, and they would rather give up on the link between credence and betting, I think that for MacFarlane, it ought to be the other way round: Since the job he has assigned to credence is decision theory, it should never be interfered with in that realm (on pain of a kind of reverse dual-control problem). But another one of Bradley and Leitgeb's examples shows how drastic the implications for the epistemic interpretation of credence can be if we follow through on MacFarlane's strong separation of reasoning and rationality (with *truth* only operating as a correctness condition in the realm of the former but not the latter):
*Forgery*: A fair coin is about to be flipped. If it lands Heads, a third party will replace both your and bookie's money with fake money. If it lands Tails, you both get to keep your real money. Bookie will offer to sell you a bet on the outcome of the coin flip (which will be revealed to both of you once the deal is struck or refused): The bookie would take 10 of the pounds currently in your wallet for the bet, and would pay you 20 of the pounds currently in theirs if the outcome was Heads. Clearly, you should not accept the bet: The only scenario in which any real money is at stake is the one where you are sure to lose it. Yet, this should not change your belief that the probability of Heads is 1/2 one iota. (Bradley & Leiteb, 2006, 123)

Carrying their reasoning over to SB, they write "the fact that the agent only avoids a Dutch book by betting *as if* her credence in Heads is 1/3 gives her no reason to actually *believe* that the probability of Heads is 1/3". I completely agree. But what should "having credence 1/3 in Heads" have to do with "*believing* that the probability of Heads is 1/3"? Bradley and Leitgeb show that we need to give up either on the link between credence and betting, or on the link between credence and believing. As MacFarlanians, I think it is clear which option we must choose.


## What Lewis gets wrong \label{sec:Lewis}

Lewis argues that SB's credence upon being woken up should be 1/2, because credences are only allowed to change upon receiving relevant evidence---and SB has not received any such evidence between going to sleep on Sunday and being woken up.

Now I argue that a move open to a MacFarlanian is to say: You have it exactly the wrong way around. Changing my credences however I see fit does not make me irrational, as long as the change does not expose me to a dutch book; and in fact, if only a change saves me from a dutch book, rationality requires me to change them in such a way as to avoid that dutch book. Usually, changing my credences in any way that predictably under- or overshoots what would be required by conditionalisation would expose me to a dutch book. But in this scenario, it happens to be the other way around: The only way to avoid a dutch book is to set my credence to 1/3 upon being woken up. So that is what a rational SB must do.

The internal state that really *isn't* allowed to change without good reason, however, is *belief*. Only emergence of relevant new *reasons* should lead to a change in belief. And SB has not received any such reasons between going to sleep on Sunday and being woken up. Therefore, SB should steadfastly hold on to their belief that the chance of the coin flip coming up $HEADS$ is/was 1/2 (I think, in the realm of belief, the "double halfer" position is correct: The chance of $HEADS$ is 1/2). And while such a belief might often give a good reason to set the 



%%If the principal principle applies in SB, the scenario would prove to be a particularly drastic example of the kind of possibility MacFarlane hints at when he talks about the strong independence of reasoning and rationality: SB would be a scenario in which it is literally impossible to simultaneously avoid being aptly described "irrational" or "unreasonable". It would seem, though, that we should rather side with Lewis in the sense of taking this to show that the principal principle doesn't apply in SB. Whether an apt analysis for why this is the case is that telling SB it is Monday is akin to a transmission of information from the future, is questionable. But %%

---------------------
 
Claim: It is the practice of *betting* that builds a bridge between belief and credence. The practice has its own norms, and one of the essential ones is: The party who bet on $p$ should receive the stake iff $p$ turned out to be true.


# Thinking about Sleeping Beauty on the Above Framework



## Why SB's credence in $HEAD$ should not be anything other than 1/3




## Why Elga's premise (E1) must be true, regardless of the principal principle



Note: All these DBs presuppose that on Sunday, SB's credence in $HEADS$ is 1/2. I have not given a good reason for why that should be the case, but also, it is not disputed by anyone involved in the debate.


But isn't there a dutch book against anyone who doesn't update their credences via conditionalaization? (Lewis, 1999) Conditionalising on the evidence SB actually has would (if Lewis is right) require their credence to 1/2. Can we construct a Dutch book against thirder-SB using the recipe Lewis (1999) gives us?

It would look like this:
On Sunday, SB's credence in "if we are woken up, the coin came up heads" is 1/2.

After being woken up, SB's credence in "the coin came up heads" is 1/3.

## Why SB should believe that the probability of $HEADS$ is 1/2

%%Lewis' premise holds for beliefs, not credences%%

## Concluding reflections: What is the status of the principal principle, the reflection principle, and conditionalisation, on this account?

In his paper "Credence and self-location", Peter Lewis writes: "All parties to the Sleeping Beauty debate agree that it shows that some cherished principle of rationality has to go. Thirders think that it is Conditionalization and Reflection that must be given up or modified, halfers think that it is the Principal Principle. I offer an analysis of the Sleeping Beauty puzzle that allows us to retain all three principles."

I have done the opposite: I have presented a view according to which the reflection principle, conditionalisation and the principal principle all fail in SB.


If we accept as strong an independence between belief and credence as MacFarlane suggests ("One can be rational without ever reasoning, and without ever regarding anything as a reason. Conversely, reasoning---even good reasoning---does not necessarily make one rational" (MacFarlane, 2023, 9)), it shouldn't much shock is when a hypothesised bridge principle between the two turns out to fail.

Lewis, on the other hand, takes the principal principle to have a kind of definitional status for what chance is---stating that its consequences "include all that we take ourselves to know about chance" (lewis, 280) and that no analysis of chance should be accepted unless it be compatible with the principal principle (Lewis, 274).

But the concept of chance is also a concept of ordinary language. As such, it already *has* a normativity governing its use. As Lewis himself says: "Like it or not, we have this concept. We think that a coin about to be tossed has a certain chance of falling heads, or that a radioactive atom has a certain chance of decaying within the year." (273)

Now, if the two were ever to come apart, what should take precedence for our beliefs about chance---the principal principle or the way the concept is used?

Following the above commitment to a close connection between belief and assertion, I maintain that while it may often be the case that what one ought to believe about the chance of an event happening will be in correspondence with the principal principle, it is the PP that has to answer to the ordinary use of the word "chance" rather than the other way round. One should believe $ch(A)=x$ iff it would be appropriate to assert "The chance of $A$ is $x$."

*Why* is it usually the case that under circumstances where it is appropriate to assert "The chance of $A$ is $x$" one should think that the fair betting odds on "A will happen" are $1:\frac{1-c}{c}$?
I don't have a good answer to this (((xxx but it might well be that in many cases a sentence like that was assertible iff the best systems... or if there was good reason to expect the long run frequency... )))

But in any case, we shouldn't expect there to be any neat formula or analysis of the word "chance" that captures all the norms governing its use. There also isn't, at least not right away and obviously, any reason that chance, if known, should be the best guide for our credences. We may be able to show that it in fact is. But it is certainly possible that it is not.

Usually, we know how to use the word. We know (or at least, our linguistic community knows) whether it would be appropriate to make a certain chance-assertion or not. This is what should govern what we believe about chances. And correspondingly, it shouldn't be cause for surprise if a certain attempt at capturing the use of the word (like the principal principle) happens to not apply in a specific circumstance. Lewis' recourse to information from the future therefore seems like an ad-hoc hypothesis to rescue his explication of chance (in particular that the principal principle exhausts its meaning).

\[No, I am contradicting myself here. My account seems to save the principal principle, not invalidated it.\]


A future toss of a fair coin is a paradigm example of something about which it is appropriate to assert that its chance is 1/2, and not appropriate to assert that its chance is anything other than 1/2.