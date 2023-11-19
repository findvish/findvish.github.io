# DL for Coders with fastai and PyTorch Part I (Ch1-3) Notes
In this series of posts, I intend to highlight the important parts that I came across in Jeremy Howards ML book - Deep Learning for Coders with fastai and PyTorch. He wrote the book to accompany the online course 'Practical Deep Learning for Coders' that is posted on [course.fast.ai](https://course.fast.ai) page.

My posts will not address every aspect of what is covered in the book but will rather aim to highlight those parts that I think are either interesting or worth paying close attention to.


## Chapter 3 - Data Ethics
General premise - A powerful tool like deep learning can be used for so many things and it behooves the developer to carefully consider the choices that are made during design/developement - recognize right and wrong actions and understand the connection between **actions** and **consequences**.

Spotting ethical issues as part of a collaborative team effort helps incorporate different perspectives thus strengthening positive outcomes.

### Feedback Loops
"Feedback loops can occur when your model is controlling the next round of data you get. The data that is returned quickly becomes flawed by the software itself. Recommendation systems are predicting what content people will like, but they also have a lot of power in determining what content people even see."

Question - Should recommendation systems even exist? Makes business sense but has no ethical grounding when one considers the harm it inflicts on users by, say, making them addicted to viewing more content. A society that is addicted to content consumption is neither leading a healthy individual life nor making a postive impact at the collective level. 

Anticipate feedback loops or take positive action to break it when you see the first signs of it in your project. But in order to be in a position to take actions, we first need to put mechanism in place to measure the impact of what has been deployed.

### Bias
Here is an example of bias. "Historically Black names received advertisements suggesting that the person had a criminal record, whereas traditionally white names had more neutral advertisements. It can make a big difference to people’s lives—for instance, if a job applicant is Googled, it may appear that they have a criminal record when they do not."

Ask yourself 'how representative is my dataset'? Consequently, are you making the effort to test your algorithm on as diverse a dataset as you possibly can. "Failing to make an ethical and inclusive AI risks losing gains made in civil rights and gender equality under the guise of machine neutrality."

### Why does this matter?
"Everybody who is training models *absolutely* needs to consider how their models will be used, and how best to ensure that they are used as positively as possible. There are things you can do. And if you don’t do them, things can go pretty badly." As ML practitioners we need to understand how our algorithms will be implemented/deployed in practice.

"**Means** should be never more important than the ends." So don't be a blind technocrat lured in by the invigorating nature of technical accomplishments or the profits to be made. Give a thought to whether goals are being achieved at the expense of the society at large. Inform colleagues/management of the capabilities, constraints, and details of your work so that it can be used in the right way. Get involved in the process of the development pipeline all the way from data collection, model/algorithm selection, to the point at which the work will be used in decision making. Researchers need to work closely with the kinds of people who will end up using their research.

### Fairness, Accountability, and Transparency
"In philosophy, and especially philosophy of ethics, this is one of the most effective tools: first, come up with a process, definition, set of questions, etc., which is designed to resolve a problem. Then try to come up with an example in which that apparent solution results in a proposal that no one would consider acceptable. This can then lead to a further refinement of the solution."

### Conclusion
"Coming from a background of working with binary logic, the lack of clear answers in ethics can be frustrating at first. Yet, the implications of how our work impacts the world, including unintended consequences and the work becoming weaponized by bad actors, are some of the most important questions we can (and should!) consider. Even though there aren’t any easy answers, there are definite pitfalls to avoid and practices to follow to move toward more ethical behavior."

"One of our reviewers for this book, Fred Monroe, used to work in hedge fund trading. He told us, after reading this chapter, that many of the issues discussed here (distribution of data being dramatically different from what a model was trained on, the impact of feedback loops on a model once deployed and at scale, and so forth) were also key issues for building profitable trading models. The kinds of things you need to do to consider societal consequences are going to have a lot of overlap with things you need to do to consider organizational, market, and customer consequences—so thinking carefully about ethics can also help you think carefully about how to make your data product successful more generally!"