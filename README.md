# GSoC 2020: Revamp CDLI tablet apps (Apple and Android)

This is an outline of the work done from June to August 2020 under the [Cuneiform Digital Library Initiative (CDLI)](https://cdli.ucla.edu/), funded as a Google Summer of Code project.

## Project Overview

CDLI tablet app offers a curated collection of images, text, and metadata of artifacts inscribed with the cuneiform script. Artifacts from the ancient Near East, which document three millennia of human activity, are made available to the users through this mobile application.

The **Revamp CDLI tablet apps (Apple and Android)** project aims to recreate the existing CDLI tablet app using Flutter, Google's open-source UI software development kit, and provide a web admin interface for the mobile app data entry and management inside the CDLI framework. Besides its existing components, the new mobile application offers additional features for a highly-customized UX.

### Team

**Student developer:** Anila Hoxha

**Mentor:** M. Willis Monroe

## Work Done 

### Milestones

- [x] Recreate the existing CDLI tablet app using Flutter. 
- [x] Implement additional app features for a highly-customized UX. 
- [x] Provide a web admin interface for the mobile app data entry and management. 
- [x] Display the entries in the web with the same functionalities as in the mobile app.

### Contributions

The code I've written for the revamped mobile apps: 

- [https://github.com/anila-a/cdli-tablet-app](https://github.com/anila-a/cdli-tablet-app) (Source Code) : [List of Commits](https://github.com/anila-a/cdli-tablet-app/commits/master)

My contributions to the CDLI framework repository:

- [https://gitlab.com/cdli/framework/-/merge_requests/154](https://gitlab.com/cdli/framework/-/merge_requests/154) (Merged) : [List of Commits](https://gitlab.com/cdli/framework/-/merge_requests/154/commits)
- [https://gitlab.com/cdli/framework/-/merge_requests/179](https://gitlab.com/cdli/framework/-/merge_requests/179) (Merged) : [List of Commits](https://gitlab.com/cdli/framework/-/merge_requests/179/commits)

**Tools and Technologies used:** Flutter, CakePHP, Docker, Bootstrap

### Results

#### Mobile app

To watch the CDLI tablet app demo video, click [here](https://drive.google.com/file/d/1Bq09m2OeLeuMyPTsHOtFYWRPYYAp6cK-/view?usp=sharing).

<p float="left">
  <img src="https://github.com/anila-a/gsoc-2020/blob/master/img/Screenshot_1.jpg" alt="Splash Screen" width="225" height="400">
  <img src="https://github.com/anila-a/gsoc-2020/blob/master/img/Screenshot_2.jpg" alt="Page Layout" width="225" height="400">
  <img src="https://github.com/anila-a/gsoc-2020/blob/master/img/Screenshot_3.jpg" alt="Sliding Up Panel" width="225" height="400">
  <img src="https://github.com/anila-a/gsoc-2020/blob/master/img/Screenshot_4.jpg" alt="Dashboard" width="225" height="400">
</p>

<p float="left">
  <img src="https://github.com/anila-a/gsoc-2020/blob/master/img/Screenshot_5.jpg" alt="Grid Layout" width="225" height="400">
  <img src="https://github.com/anila-a/gsoc-2020/blob/master/img/Screenshot_6.jpg" alt="List Layout" width="225" height="400">
  <img src="https://github.com/anila-a/gsoc-2020/blob/master/img/Screenshot_7.jpg" alt="Help & Feedback" width="225" height="400">
  <img src="https://github.com/anila-a/gsoc-2020/blob/master/img/Screenshot_8.jpg" alt="Search" width="225" height="400">
</p>

#### Web admin interface

To watch the admin interface demo video, click [here](https://drive.google.com/file/d/1KeBs4PmL-rrZJnEcRdPraN7KEjOPF609/view?usp=sharing).

### Weekly Reports

All reports written in the coding period:

| Month      | #1            | #2  | #3  | #4  | #eval  |
| :--------: |:-------------:| :-----: | :-----: | :-----: | :-----: |
| **June**   | [week 1](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/01_week1)  | [week 2](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/02_week2)  | [week 3](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/03_week3)  | [week 4](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/04_week4)  | [eval 1](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/05_eval1)  |
| **July**   | [week 5](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/06_week5)  | [week 6](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/07_week6)  | [week 7](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/08_week7)  | [week 8](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/09_week8)  | [eval 2](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/10_eval2)  |
| **August** | [week 9](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/11_week9)  | [week 10](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/12_week10)  | [week 11](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/13_week11)  | [week 12](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/14_week12)  | [eval 3](https://cdli-gh.github.io/blog/gsoc20/mobile_app/posts/15_eval3)  |

## Future Work

Points of possible improvement and resumed work in the project include:

- **Connect the app to the new API:** For now, the app is fetching the data from the existing API. When the framework is all set up and made available online, the feed url has to be replaced with the new one.

- **Edit multiple dates:** Implement an action which moves a group of entries to a range of dates as specified by the interface administrator.

- **Image display in the web interface:** The browser gets the entries' images from the existing CDLI web server and displays them in the view. The path to the images has to be changed to the new web server at a later time.

- **Additional features:** Add more functionalities to the web interface similar to the mobile app.

- **Frontend update:** Set up a Vue.js frontend to the admin interface.
