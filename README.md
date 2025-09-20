# HNG Stage 0 – Profile Card  

## Author  
**Akinyemi Samuel Temidayo**

## Description  
This is my Stage 0 task for the HNG Internship. It is a responsive profile card built with plain HTML, CSS, and JavaScript.  
The card displays my name, bio, social media links, hobbies, dislikes, and the current time in milliseconds.  

## Features  
- Uses semantic HTML elements.  
- Shows the current time dynamically in milliseconds.  
- Responsive design for mobile, tablet, and desktop.  
- Includes all required `data-testid` attributes for testing.  

## Live Link  
[View Live Site](https://hng-stage-zero-profile-card.vercel.app)

## How to Run Locally  
1. Clone this repository:  
   ```bash```
   git clone https://github.com/temidayoakinyemi/HNG-Stage-Zero-Profile-Card

2. Navigate into the project folder:
   cd HNG-Stage-Zero-Profile-Card

3. Open the index.html file in your browser to view the project locally.   


## Tests / Notes

- All required `data-testid` attributes are included:
  - `test-profile-card`
  - `test-user-name`
  - `test-user-bio`
  - `test-user-time`
  - `test-user-avatar`
  - `test-user-social-links`
  - `test-user-hobbies`
  - `test-user-dislikes`

- The time updates dynamically using `Date.now()` every second.
- The layout is responsive and accessible on mobile, tablet, and desktop.
- All social links open in new tabs with `rel="noopener noreferrer"`.
