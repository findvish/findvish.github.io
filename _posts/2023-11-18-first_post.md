# DL for Coders with fastai \& PyTorch Part I (Ch1-3) Notes
In this series of posts, I intend to highlight the important parts that I came across in Jeremy Howards ML book. He wrote the book to accompany the online course 'Practical Deep Learning for Coders' that is posted on [course.fast.ai](https://course.fast.ai) page.

My posts will not address every aspect of what is covered in the book but will rather aim to highlight those that I think are either interesting or worth paying close attention to.


## Chapter 3 - Data Ethics
General premise - A powerful tool like deep learning can be used for so many things and it behooves the developer to carefully consider the choices that are made during design/developement - recognize right and wrong actions and understand the connection between **actions** and **consequences**.

Spotting ethical issues as part of a collaborative team effort helps incorporate different perspectives thus strengthening the intended outcome.

### Feedback Loops
Feedback loops can occur when your model is controlling the next round of data you get. The data that is returned quickly becomes flawed by the software itself. Recommendation systems are predicting what content people will like, but they also have a lot of power in determining what content people even see.

Question - Should recommendation systems even exist? Makes business sense but has no ethical grounding when one considers the harm it could inflict on users by, say, making them addicted to viewing more content. A society that is addicted to content consumption is neither leading a healthy individual life nor making life better for its citizens. 

### Bias
Here is an example of bias. Historically Black names received advertisements suggesting that the person had a criminal record, whereas traditionally white names had more neutral advertisements. It can make a big difference to people’s lives—for instance, if a job applicant is Googled, it may appear that they have a criminal record when they do not.

### Why does this matter?
Everybody who is training models *absolutely* needs to consider how their models will be used, and consider how to best ensure that they are used as positively as possible. There are things you can do. And if you don’t do them, things can go pretty badly.
**Means** should be never more important than the ends. So don't be a blind technocrat blinded by the invigorating nature of technical accomplishments or the profits to be made. Give thought to whether goals are being achieved at the expense of the society at large.