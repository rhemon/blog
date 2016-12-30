---
layout: post-page
title: Bugs and Features for SUSI Android App
category: gci
image: SusiLogo1.png
meta: This article is about the problems I found in SUSI Android app and the features I am suggesting for it.
---

<div style="text-align: center;">
<img src="{{site.baseurl}}/img/{{page.image}}" width="120px" height="120px" />
</div>
<br>

I claimed a [task](https://codein.withgoogle.com/tasks/6212307231178752/?sp-is_beginner=False) where I am told to explore the susi android app and write
a blog post suggesting improvements, and thats what this article is about.

Everything written here are my personal opinion, and note, I am just a beginner
so changes suggested might not be appropriate, but I will try to keep it
as sane as possible.

## Too many "I don't know"
---
<div class="row">
<div class="col-lg-6 col-md-6 col-sm-6" style="text-align: center;">
<img src="{{site.baseurl}}/img/susi/websearch.png" height="400px" width="250px">
</div>
<div class="col-lg-6 col-md-6 col-sm-6" style="font-size: 16px">
I tried various types of random fact questions, but I ended up receiving: <br><br>
<code>
I don't know how to answer this. <br>
Here is web search result: <br>
</code><br>
And not, there is no search result. This is probably a bug and needs a fix. Now,
the question asked according to me is a fact that can be found search. If presently it
is not part of the program, then it would be cool if susi could do a quick search
and gives us a result following that.
</div>
</div>
<br>

## Can't susi get information from loklak?
---
<div class="row">
<div class="col-lg-6 col-md-6 col-sm-6" style="text-align: center;">
<img src="{{site.baseurl}}/img/susi/twitter.png" height="400px" width="250px">
</div>
<div class="col-lg-6 col-md-6 col-sm-6" style="font-size: 16px">
I tried asking for tweets with #fossasia but didnt get a result. Not sure why,
but I expected susi would be somehow connected with loklak, using it to
collect twitter messages. <br><br>

I personally think it is an amazing feature to have. If it is added, then there
must be a bug, if not I would recommend to add it to susi. <br><br>

If I am not wrong, there is an API with which twitter messages can be collected
from loklak and so it would be nice if we add that to susi so that it can give
twitter posts to user if asked. <br><br>

It will also be nice if it could perform some analysis on request, a simple
example would be - going through some particular list and give the most retweeted.
And more complex example would be - going through a list of tweets and figure what
kind of posts are more liked by people.
</div>
</div>
<br>

## I know it's not a calculator, but still...
---
<div class="row">
<div class="col-lg-6 col-md-6 col-sm-6" style="text-align: center;">
<img src="{{site.baseurl}}/img/susi/maths.png" height="400px" width="250px">
</div>
<div class="col-lg-6 col-md-6 col-sm-6" style="font-size: 16px">
Maybe the results for math was directed to some kind of joke, but my personal
opinion is that, rather then sending something random, it would be much easier
and simple to do the math problem. <br><br>

Now, it might be argued that doing maths like that there is a calculator, well
yes, so would it possible if we make it able to more complicated maths. For
example: solving equations, doing simultaneous equations, using functions to find
values, do graph maths, etc. <br><br>

I believe making it capable of doing all these types of math will make it
really popular, among students speciality, after all they will receive
homework buddy. :P
</div>
</div>
<br>

## Offline mode of susi
---
<div class="row">
<div class="col-lg-6 col-md-6 col-sm-6" style="text-align: center;">
<img src="{{site.baseurl}}/img/susi/no-internet.png" height="400px" width="250px">
</div>
<div class="col-lg-6 col-md-6 col-sm-6" style="font-size: 16px">
I tried chatting with susi, while having wifi turned off and there was no result.
So its probably using the susi api from web and that is fine. But thinking of situations
where we usually take time to chat with a bot is either because we are bored or want
to know something particular. <br><br>
Taking the situation of being bored, as a citizen of Bangladesh, where internet
connection is not available all the moment, I think at moments like users might
want to kill time talking with susi. At a time like this, offline support would
be great. <br><br>
However adding susi locally will probably make the app really large, so we
could get only part of it? Maybe it will response to some common messages
while anything out of the place or something that requires internet will reply
saying, "you need to have internet connection".
</div>
</div>

## Map access
---
<div class="row">
<div class="col-lg-6 col-md-6 col-sm-6" style="text-align: center;">
<img src="{{site.baseurl}}/img/susi/where.png" height="400px" width="250px">
</div>
<div class="col-lg-6 col-md-6 col-sm-6" style="font-size: 16px">
Adding the feature of allowing susi use google maps will be really amazing and
also helpful. <br><br>
It can simply return the address using Google Maps and location, however
it might also be better if it could share part of google map in the chat,
and on click it will take to Google Maps app. <br><br>
It will be even better, if it could give direction guides. For example, from one
place I tell susi "Show me the way to Road 7/A", and then it will give its step
by step instruction using my location. e.g. "Go straight and take the first right.",
"Then turn right", etc.
</div>
</div>

## Sometime it takes too long to reply
---
<div class="row">
<div class="col-lg-6 col-md-6 col-sm-6" style="text-align: center;">
<img src="{{site.baseurl}}/img/susi/list.png" height="400px" width="250px">
</div>
<div class="col-lg-6 col-md-6 col-sm-6" style="font-size: 16px">
It might not have been the best thing to ask, but when I did it took 10 minute
to get the reply "Why don't you list them for me?". <br><br>
I am not exactly sure where it was the problem. If it was just slow in computing
then it probably needs fixes in the code. If it is something that susi cant handle
and caused it to fall in some kind of problem, then maybe some kind of handler could
be added to susi. <br><br>
The handler should be something that just doesn't say "I don't the answer..." rather.
For this case reply that I receive isn't bad it self, but maybe it could have listed one
or two things and then just say, "There's too many, why not just try out what you want to do?".
</div>
</div>
<br>

## Make sign up and sign in easier
---
<div class="row">
<div class="col-lg-6 col-md-6 col-sm-6" style="text-align: center;">
<img src="{{site.baseurl}}/img/susi/sign-up.png" height="400px" width="250px">
</div>
<div class="col-lg-6 col-md-6 col-sm-6" style="font-size: 16px">
It will be a lot easier and more user friendly to add Sign up with Google and
Sign in with Google. I myself find it really tiring, typing down my email address
and giving a password. It will also remove the need of verifying email separately,
making it more easier for users.
</div>
</div>
<br>

## Intenet Connectivity Probelms
---
<div class="row">
<div class="col-lg-6 col-md-6 col-sm-6" style="text-align: center;">
<img src="{{site.baseurl}}/img/susi/twitter.png" height="400px" width="250px">
</div>
<div class="col-lg-6 col-md-6 col-sm-6" style="font-size: 16px">
Not sure why, but at times I was receiving "Internet Connectivity Problem" but
I checked every time, and there didn't seem to be any kind of problem. Now I am not
completely sure whether its a problem in susi, or was it actually a problem in
my internet and by the time I tried confirming it, it got fixed.
</div>
</div>

<br><br><br>
Well thats about what I found exploring and chatting with susi. There are still
few more things that I want to suggest, but don't have any screenshots to
supported it with.
<br>

### Sharing Option
First is adding a feature to share. There must be moments of chat that a user
will want to share with friends, and so it will be nice if there is a share
option added to susi.
<br>

### Group chat
Maybe not the best idea, but it would be cool if susi could handle talking with
multiple people as a group chat.
<br>

### Remember what it was told
This is a common problem I see everywhere that, it forgets what it was talking
about and then sends a random reply. It is probably difficult to handle but if it
can be fixed, it will be one step closer to human. Much better if it can refer
back to something that was discussed earlier.

For example, first I talk about
football with susi, then talking about cricket, some other things and then
comeback to the discussion of football.
<br>

### Logo Improvement
I am not confident about this suggestion, but personally don't find the present
icon suitable to the app. It would be nice if we can replace with something more
eye catching while it is also simple and meaningful that relates to the app.
<br>

### Language Support
It would be able to increase its user a lot more if it can support more users with
their native language. To be able to handle a chat in a different language will
be really amazing and will probably be quite different as well.
<br>

### Starts a chat on its own
Since what we have here is an android app, it can have the ability to start
a chat with the user on its own, maybe with something like "How's life going?",
"What are you doing?", "Its been a while", etc. It could be set that, if user does
not open and chat for 2 days, try starting a chat.
<br><br>

For now thats all I have thought of for susi. It would be really nice to see some of the changes actually taking place in the app. Thanks for staying with me till the end.
<br><br>
