# Objective Functions v.s. Life Purposes - How are we motivated to do life-long self-training?

Each time I attempt to see intelligence in machine learning models, there would be a doubt rising in my head - how could intelligence, characterized by high-level abstraction capability, be acquired simply by a gradient descent process reaching convergence? I would rather believe the journey for pursuing intelligence is a back-and-forth, twist-and-turns, and chaotic-and-conscious process with loops, eventually jumping out of loops and reaching some enlightment point. Therefore, it cannot be attached only with one single objective formulated by one specific optimizatoin problem.

If you begin to question that, you might find the root of the problem lies in our research motivation for studying AI. Many people would think the subject of AI research should be a concrete application-oriented problem, but I would rather believe the intelligence itself should be laid at the core of the subject we should study. If we wish to solve almost everything using intelligence, how could it be possible for us to achieve that goal bypassing intelligence. Even if we cannot be sure of what proper properties artificial intelligence should apprear, at least we shoule be able to find clues from ourselves - human intelligence.

From this perspective, I drew inspiration from children learning to propose a life-long self-training framework hypothesis - the continuous process alternating between finding a puzzle and solving a puzzle. As we were children, we explore the world mainly out of curiosity, which can be decomposed into three general questions:
- Is it easy to find or construct a puzzle question for a child or an agent?
- Is this question likely to be solved by the child or the agent?
- How much sense of achievement could be gained by the child or the agent?

I take a specific scenario that children love watching cartoons more than movies. It is obvious that cartoons always have non-realistic scene, such as [bright colors with high contrast](https://sciencing.com/do-bright-colors-appeal-kids-5476948.html) and talking animals 

Bright colors catch young children's eyes because they help kids to distiguish objects from one another in their field of vision.
Talking animals appeal to children because children may find it easier to understand anthropomorphic characters by animal appearance than to understand human psychology and behavior.

chile love cartoon more than movies,
cartoon always have non-authentic scene, 
which color used always pure, 
much difference to the reality, like a talking dog, a jumping lamp,
don't obey physical laws, 
that do not affect children's cognition at all,
on the other hand, children are attracted and motivated. Why?
Cognition might be achieved separately without motivation, and it is the motivation that drive self-training throught our life, implictly or explicitly.

According to the assumptions as made above, we put the ordinary case that children are more likely to obssess themselves into watching cartoon rather than other things into the find-solve framework.

We would find that the authentity of a scene might not be important. The point is that - would it be easy to form a puzzle in children's head, creating a cognitive surprising event and drawing children's attention. Chidren would prefer reading pictures to reading texts, and furtherly, chidren would prefer reading cartoon pictures to reading real-world images.

After forming a puzzle, we will assess whether the puzzle is easy to solve and might try several times to solve it, harder each time. If we solve it, the degree of being able to acquire new knowledge will contribute to the reward. Little acquired knowledge made us feel boring, whereas much knowledge cause us to feel excited. If we cannot solve it after several attempts, we might give up without any reward but being exhaust. Or we would first evaluate whether it is woth solving based on previous experience, including evalute whether we solved it in the past and whether it bring a lot of reward.

For children, it might be easier to find a puzzle in cartoon than in real-world videos, such as a simple dump falling-down movement, a strange branna-like head. By wathcing cartoon, a small environment model will be developed in children's head, and a narrative story line will be made up from the children perspective, along with a series of why questions seeking explanations. Although adults would see as having obvious answers and meaningless to ask, for children such questions constitute the initial puzzle in their life time to help develop their common knowledge. At that time, children's sense of reward might mainly driven by satisfying their curiosity and making a small acheivement. As they grow up, answering these simple questions cannot bring them new knowledge, so that we will not get reward any more. Or they already know or they think they have already know the answers, so that they do not want to be bothered to ask the questions. They need to find new puzzles and solve them.

The process of finding, evaluating, tring to solve, failed or succeed, being rewarded or not, re-evluating, exectures so quickly that we might not be aware of how we are motivated in everyday life. 

when we became adults, reward expectation system becomes complex, and curiosity & achievement are no only the unique factor govening the inccentive that drive us. As the environment model becomes strong, we might be able to do long-term plan and motivate ourself by some ultimate goal we call the life purpose.

This is a big topic beyond our technique pursuing for AI, but we can still apply this thinking to some algorithmic models such as GANs. For the adversary training framework, the two opponentant roles can be simultaneously hosted in our brain, one for purposing a puzzle, one for solving it. The puzzle is proposed by the discriminator, and is left for the generator to solve. To find the most rewarding puzzle, the discriminator has to play in an adversarial style, that is, to pick the most weakness in the generator with a large margin to gain. Some troubles in GANs can be also explained using this framework, which is the generator that fail to solve the puzzle given by the discriminator would be stuck in a poor finding-solving process, losing the opportunity of being upgraded.


