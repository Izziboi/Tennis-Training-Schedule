<h1><p align="center">Tennis-Training-Schedule</p></h1>

## Introduction
<p align="justify">
One day, I went to nuy some food stuffs and briefly overhead a customer discussing about Excel with the shop operator. It cut my interest but not seriously at first. After my shopping, I decided to ask the shop operator what the fellow was talking about. He explained that he wanted an Excel sheet that could help him make some schedules. I later got in contact with the fellow and it turned out that he was a Lawn Tennis Coach. He actually needed an Excel platform he could use to take attendance of his students as well as keep record of their payments. After our discussion, I started working on it according to his specifications and result is what you have on this repository.
</p>

## About The Platform
<p align="justify">
The platform has the following sections:
  
- A section for brief trainee bio data<br>
  
![image](https://user-images.githubusercontent.com/44449730/159981060-038625b0-330c-4dd3-b8ef-fa875df171c2.png)

- A section for trainee's preferred training schedule and total fee<br>
  
![image](https://user-images.githubusercontent.com/44449730/159981931-896253ea-eba3-417c-827f-7308d2f571c0.png)

- A section for trainee's deposit(s) and attendance<br>
  
![image](https://user-images.githubusercontent.com/44449730/159982116-620acd6b-32a1-47d6-95e6-25bcc57042ad.png)

- A section for summary of trainee's activities<br>
  
![image](https://user-images.githubusercontent.com/44449730/159982227-353e5632-a016-4f99-8031-902bf5ccb5f4.png)

</p>

## How To Use The Platform
<p align="justify">
There are two ways to use the platform:
  
- Pay-as-you-go<br>
- Recurrent
  
- **Pay-as-you-go:** By this, a trainee does not bother to register with the academy. They only hop in, pay, train until their deposit expires and they leave. In this case, the portion of the platform sjown below is used for them.
  
![image](https://user-images.githubusercontent.com/44449730/159984671-326325ce-8d1d-4d3f-a142-5ec05f45485e.png)

At the end of the table, there is no summary. Only the total amount deposited is shown as well as the fee per hour (See below).
  
![image](https://user-images.githubusercontent.com/44449730/159985067-d3e31fae-b2d3-4feb-a0bd-826daf6665f7.png)

- **Recurrent:** This is where the beauty of the platform is appreciated. Here a trainee registers, pays deposit and begins to attend the training according to schedule. As they train, their deposit counts down until it is exhausted. At the end of the training term, the summary is checked to see the balance of the trainee's deposit. Below is how it goes.
  
![image](https://user-images.githubusercontent.com/44449730/160234180-78ef6144-3a2b-4f54-af6b-6c5a6150f6e8.png)

The user enters the following information:<br>
- Length of Training (weeks)<br>
- No. of Trainings Per Week<br>
- No. of Trainings During Weekdays
- Days of the Week for Training: Here, all the days should be entered in the row, column-by-column in the form, MONDAY/M (meaning Monday morning), TUESDAY/E (meaning Tuesday evening), WEDNESDAY/ME (Wednesday morning and evening). Morning trainigs last for 4 hours while evening trainings last for 5 hours.<br>
- Saturday Training: The user can enter YES or NO, depending on whether the trainee is interested in Saturday training or not. Saturday trainings last for 5 hours.<br>
- Fee Per Hour
  
The following are generated automatically by the system:<br>
- Total No. of Trainings<br>
- Weeks Trained<br>
- Remaining Trainings<br>
- Training Hours Per Week<br>
- Total Fee
  
Furthermore, the user enters the trainee's deposit, deposit date, attendance dates and attendance. The balance of the trainee's fee is generated automatically by the system. The attendace takes either p (for present) or a (for absent). Please see below.
  
![image](https://user-images.githubusercontent.com/44449730/160235240-55322899-29c0-4094-bfd9-d3c81453f75b.png)

The summary can be seen below.
  
![image](https://user-images.githubusercontent.com/44449730/160235340-2d57e729-6027-4e10-8315-db209ef89682.png)

In this case, the trainee is owing 160 Euros.
</p>
