---
layout: post-learning
title: Learning From Data
---

**TL;DR** A time-intensive theoretical introduction to machine learning.

# What is this?

An introductory course to machine learning with a heavy emphasis on the
subject's theoretical underpinnings. Not many algorithms are covered-there's
the percepton, logistic regression, neural nets and support vector machines-but
unlike practically every other machine learning course, learning algorithms are
not the focus of the course. Instead the focus is on the big ideas in machine
learning, such as regularization, overfitting and validation.

# Should I take it?

If your a professional with a busy day job and just want to learn enough
machine learning so you can implement a recommender system for your app using
packages like sci-kit learn, this might not be the course for you. While there
are other courses that might be theoretical in the sense that they go in depth
to show why certain algorithms work, this course places a strong emphasis on
fundamentals ideas in machine learning irrespective of any particular
algorithm. It's an approach I really enjoyed but at times even I found it a bit
too mathy. Also the problem sets focus on writing the machine learning algorithms
from scratch instead testing our understanding of the proofs gone over in
class, so there was a bit of disconnect between the lecture material and the
problem sets. That's not to say the problem sets were easy, in fact they are
ridiculously time intensive, be prepared to spend between 16-20 hours a week on
this course. That's not only my experience but
[others](https://nlppeople.com/learning-from-data-review-of-the-edx-machine-learning-course/)
as well. In the end though you'll have a very strong grasp of the fundamentals
of machine learning and be very aware of how easy it is to contaminate your
data or overfit it for example.

Another artificial intelligence course I attempted was MIT's 6.034 course. The
lecturer for the course, Professor Patrick Henry Winston, was very
entertaining. However the syllabus of the course is erratic. It
basically goes over a different aspect of artificial intelligence research
every lecture. You start with expert systems and then move onto the basically
unrelated field of search algorithms, then flirt with the idea of visual
object recognition before moving on to genetic algorithms. It's a frankly
ridiculous way to structure the course, nothing you learn in one week will be
built on in the next week. On the other hand, if your interested any of the
topics Professor Patrick goes over in the course, you can watch it on youtube as
a self-contained presentation. The problem sets are pretty
demanding, after spending what felt like 20 minutes covering neural nets in the
lecture, your expected to implement it on your own on the problem set. I would say
they are demanding in a bad way, in the sense you need to put a lot of effort in
but won't gain much out of it, whereas Caltech's problem sets are demanding in
a good way. 

I've also audited Andrew Ng's machine learning course, but personally I dislike
webcam MOOC's. Overall I say go with Caltech's offering.

# Additional Resources/Tips

If your interested in the course, I've written a
[script](https://github.com/zhiyanfoo/caltech-machine-learning) to download all
the materials and organize them in a folder. The course's problem sets can be
done in any language, personally I picked python. I wouldn't do it in C++, it
took long enough to finish as it were. But in the final stages of the course,
you need to use a third-party library, the one recommended by the course is a
C++ library I believe. That's the only time my results started differing from
the courses slightly. It might be the package I was using or it could be just
mistakes on my part.

<br>

Here's the [course](http://work.caltech.edu/telecourse.html) page, with my
[code](https://github.com/zhiyanfoo/caltech-machine-learning) here.
