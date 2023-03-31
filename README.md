# Theory of Algorithms 
This is my Github Repository to the assessment that I must complete for the 2023 Theory of Algorithms module. My name is Faustas Tamulis (G00373028@atu.ie). I am a final year full-time student at ATU(Atlantic Technological University). In this assignment we will be talking about the topic of The Polynomial Time
Complexity Class (P).

## Part 1: Description of Polynomial Time Complexity Class (P)
According to computational complexity theory, the Polynomial Time Complexity Class, abbreviated as P, is the collection of decision problems that can be resolved in polynomial time by a deterministic Turing machine, meaning that the algorithm's execution time is constrained by a polynomial function of the input size.The class P includes many important problems such as sorting, searching, and graph algorithms.
<img src="https://www.baeldung.com/wp-content/uploads/sites/4/2020/03/P-NP-NP_Hard-NP-Complete-1-1-1024x783.png"  width="600" height="400">

## Part 2: Problems with P
The issue is that some significant issues that emerge in practice, such optimization problems and decision problems in number theory, have been demonstrated to be NP-hard, which means that they are at least as challenging as the hardest problems in NP. These issues are impossible to resolve for huge input sizes because they take exponentially long to solve on a deterministic system.
<img src="https://miro.medium.com/v2/resize:fit:686/0*bupWMNHe1-j2_5BY.png"  width="600" height="400">


## Part 3: Relationship with NP
The connection between the difficulty classes P and NP is a crucial open issue in computer science and mathematics. If you want to put it simply, the question is whether every issue that can be verified in polynomial time (NP) can likewise be resolved in polynomial time (P). Due to the fact that P is a subset of NP, all of its problems also exist in NP. Considering that any issue that can be resolved in polynomial time may also be resolved in polynomial time, this is true. Whether P is a strict subset of NP or if it is the same as NP is unknown, though.
<img src="https://news.mit.edu/sites/default/files/styles/news_article__image_gallery/public/images/200910/20100816151036-0_0.jpg?itok=-2VghZ3g"  width="600" height="400">

## Part 4: Differences between P and NP
Time complexity, Verification vs. solution, Certifications, Complexity hierarchy, and Practical consequences are the primary distinctions between the complexity classes P and NP. We will be taking a look at what each of these refer to when we talk about the difference between P and NP.
<img src="https://images.slideplayer.com/5/1517754/slides/slide_4.jpg"  width="600" height="400">

## References:
[1] https://www.geeksforgeeks.org/types-of-complexity-classes-p-np-conp-np-hard-and-np-complete/

[2] https://people.engr.tamu.edu/andreas-klappenecker/csce411-s19/csce411-complexity1.pdf

[3] https://www.tutorialspoint.com/design_and_analysis_of_algorithms/design_and_analysis_of_algorithms_p_np_class.htm#

[4] https://en.wikipedia.org/wiki/Cobham%27s_thesis

[5] https://en.wikipedia.org/wiki/P_(complexity)

[6] https://news.mit.edu/2009/explainer-pnp#:~:text=Roughly%20speaking%2C%20P%20is%20a,actually%20have%20relatively%20easy%20solutions.

[7] https://www.youtube.com/watch?v=EHp4FPyajKQ

[8] https://dl.acm.org/doi/abs/10.5555/1074100.1074233

[9] https://www.baeldung.com/cs/p-np-np-complete-np-hard

[10] https://www.scottaaronson.com/papers/pnp.pdf
