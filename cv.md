# Elena Surilova
## Contact information
- tel. +38-066-189-02-85
- email: elen21surilova@gmail.com, oblap-lena@yandex.ru 
- Skype: oblap17lena

---

## About me
My current objective is to change the job and deepen into the area of WEB-development, as my current occupation has awoken this interest. I have been leading and editing the website of the National University "Odessa Law Academy" since 2017 applying HTML and CSS. The website, however, was designed and administered by Joomla CMS (Content Management System), this fact entails certain limitations, as i did not have an opportunity to participate in the initial development. Besides, my current tasks and job functions are monotonous, and consequently there is no chance to gain new knowledge and skills in the sphere. In this regard, i have decided to acquire new competencies in order to become a professional. I hope to succeed because i am: goal-oriented and self-motivated; diligent and hard-working; concentrated and have analytical thinking; can perform as a team-player or solo; quick learner and strive to new vocational knowledge. Because, as the Chinese say, 
> **a journey of a thousand miles begins with a single step.**

---

## My skills
* webpage layout skill; 
* knowledge of Sass preprocessor; 
* basic knowledge of Javascript; 
* knowledge Git version control system;

---

## Profession experience
I have no on-job experience in web development.  

However, as mentioned above, in my current efforts I maintain and fill in the university website on the Joomla engine. To deepen my knowledge, in 2018 I took the online course "Software Testing" on the QATestLab platform, got a general idea of ​​the testing industry, but my search went on. Then there was scattered reading of the articles on web development, concerning HTML/ CSS, then simulators and marathons on the htmlacademy website, and last year I finally decided to deepen my knowledge in the area and entered the Front-End Basic course (layout) from Hillel IT-school in Odessa. The course was completed in December 2020.  

The final project within the Front-End basic course is [the Hofmann website](https://helen25sur.github.io/hofmann/), in which i implemented tab switching and displaying different project cards in the section "Our Projects" using CSS only.


```
input[name="type-design"] {
	display: none;
}

#product-design-trigger:not(:checked)~.product-design-section,
.graphic-design-section,
.interior-design-section,
.web-design-section,
.app-design-section {
	display: none;
}

#product-design-trigger:checked~.product-design-section,
#graphic-design-trigger:checked~.graphic-design-section,
#interior-design-trigger:checked~.interior-design-section,
#web-design-trigger:checked~.web-design-section,
#app-design-trigger:checked~.app-design-section {
	display: block;
}

#product-design-trigger:checked~.list-theme-project .product,
#graphic-design-trigger:checked~.list-theme-project .graphic,
#interior-design-trigger:checked~.list-theme-project .interior,
#web-design-trigger:checked~.list-theme-project .web,
#app-design-trigger:checked~.list-theme-project .app {
	font-weight: bold;
}
```

Now I am learning javascript and within the Front-End Pro course at the same school. I also study algorithms and develop logical thinking. I have started the book "Grocking Algorithms" and rewrite the code proposed into javascript, such as a binary search algorithm:  
```
function binarySearch(list, item) {
	let low = 0;
	let high = list.length - 1;

	while (low <= high) {
		let mid = Math.floor((low + high) / 2);
		let guess = list[mid];
		if (guess === item) {
			return mid;
		}
		if (guess > item) {
			high = mid - 1;
		} else {
			low = mid + 1;
		}
	}
	return null;
}

const myList = [1, 3, 5, 7, 9, 11, 13, 15, 17, 19, 21];

console.log(binarySearch(myList, 11));
```
---

## Education
* 2016-2020 Bachelor in Law at the National University "Odessa Law Academy"; 
* February 2018 - online course "Software Testing" on the QATestLab platform; 
* October 2020 - December 2020 - Front-End Basic course (layout), Hillel IT-school,  Odessa;  
* February 2021 to present - Front-End Pro Course (javascript), Hillel IT-school,  Odessa.

---

## My English knowledge
The level of English is approximately A2, but I have no certificates to confirm the that

