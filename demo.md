---
title: Demo
layout: page
---

We used Cut to study some of the psychological and behavioral outcomes of participating in Ramadan rituals. Risk-taking, choices in resource dilemmas, cognitive control, and trust are examples of the variables we were interested in. A demo of the research instrument is shown below. Also available [here](https://lens.cut.social/#/mad2020a/en):

<div class="demo-container">
  <iframe src="https://lens.cut.social/#/mad2020a/en" frameborder="0" allowfullscreen=""></iframe>
</div>

Cut allowed us to create a responsive instrument tailored to our research needs. We created a template of different tasks or question formats. The instrument is a series of these templates that are attached to each other. Each template has a set of parameters that the researcher can modify based on their needs. For example, the code below shows the set of parameters for a simple Go-NoGo task: 

    {
	    "id": "Go/NoGo Demo",
	    "type":"gonogo",
	    "text":"gonogo.instruction",
	    "help":"Press one of the images in less than three seconds.",
	    "trials": {
		    "total": 24,
		    "go": 12,
		    "left": 12,
		    "leftGo": 6
		},
		"stimuliDuration": 2000,
		"fixationDuration": 1000,
		"feedbackDuration": 1000,
		"timeoutsBeforeReset": 2,
		"choices": {
			"go": "blue-star",
			"nogo": "star"
			}
		}

The researcher can set the total number of trials, the number of Go (and NoGo) rounds, or the number of times the stimuli is shown on the left hand and right hand sides. It is also possible to set the duration of the time in which the stimuli is shown, the fixation period between the rounds, the duration of the feedback messages (if any), how many times the participants can time out (not respond) before the task starts over again. Even the shapes used for Go and NoGo stimuli can be customized. 

A study intrument on Cut consists of a series of JSON elements similar to the one shown above. JSON is very popular data format that consists of keys and values. The response format is also a JSON file. This architecture makes it easier to add or extend new tasks. A developer can create their task in any language, then use a JSON element to interface and set the paramters, and store the data.   

Cut also makes it easier to create and run studies in multiple languages. All of the parameters that the researchers sets before data collection have specific tags. These tags retreive content based on the language selected at the beginning of the study. For example, the GO-NoGo task shown above can be run in Farsi or English or Arabic. When a user selects English, the code below is retrieved to present the task to the subject: 

    "gonogo.introduction": "Great. We're almost done.<br /><br />Next is Go-NoGo game. For this task, you need to use the right (&#8594;) or left (&#8592;) keys on your keyboard. You'll briefly see the shape of a blue or yellow star on the left or on the right side of the screen.<br /><br />If you see a blue star, you should press the key that matches the **same** side as the star. If you see a yellow star, you should press the key that points at the **opposite** side.<br /><br />You have 1 second to respond but faster and accurate responses will get you more bonus points. <br /><br />Let's start round 1 with feedback.",
    "gonogo.are_you_ready": "Place your fingers on the &#8594; and &#8592; keys. Press the space bar to begin.",
    "gonogo.too_many_timeouts": "You waited too long! Let's start over.",
    "gonogo.restart": "Restart",
    "gonogo.start": "Start",
    "gonogo.instruction": "Use &#8594; and &#8592; keys. Same side for blue star, opposite side for yellow star. Be quick!",
    "gonogo.main.introduction": "Ok, so let's begin round 2. You will not receive feedback. Press next to begin.",


But if the subject selects Farsi, the content below is retrieved. Note the tags such as `"gonogo.are_you_ready"` or `"gonogo.too_many_timeouts"`. They are identical in both the English and Farsi version. However, they are followed by content messages in specified langauges. 


    "gonogo.introduction": "خب، این اولین بخش آزمونه.<br /><br /> یک ستاره‌ی آبی یا زرد سمت راست یا چپ صفحه خواهید دید. اگر ستاره آبی بود، آن را لمس یا کلیک کنید.<br /><br />اگر ستاره زرد بود، باید سمت مخالف صفحه را کلیل یا لمس کنید. شما فقط ۳ ثانیه زمان دارید که انتخاب کنید. پاسخ‌های سریعتر و صحیح امتیاز بیشتری به شما می‌دهند. <br /><br /> با چند نوبت تمرینی شروع می‌کنیم (درست یا غلط بودن پاسخ شما مشخص می‌شود).",
    "gonogo.are_you_ready": "آماده هستید؟",
    "gonogo.too_many_timeouts": "خیلی معطل کردی. دوباره شروع می‌کنیم.",
    "gonogo.restart": "شروع دوباره",
    "gonogo.start": "شروع",
    "gonogo.instruction": "ستاره‌های آبی را کلیک/لمس کنید. برای ستاره‌های زرد سمت مخالف را لمس/کلیک کنید.",
    "gonogo.main.introduction": "خب، حالا یکبار هم بدون بازخورد از درستی پاسخ: ",

To create a version of a study in a different language, the researcher provides a list of the English *key:content* pairs to a translator. Once a different language content is available, a new option is added to the list of languages shown to subjects at the beginning of the study. Note that the Arabic version of the content is not available, so the English version is shown instead by default. 
 
