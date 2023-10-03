# Office45 

<img src="https://amandlaomnotho.co.za/wp-content/uploads/ultimatemember/1/profile_photo-190x190.jpg?1696348136" align="right"
     alt="Office45 Logo" width="190" height="190">

Announcement Sharing App that is educational informative
Working with schools mostly in rural areas

* **Easy to use and install** and **24/7** support.
* **Revolutionalise the schooling system**, **Completely from the palm of your hand**
  or another CI system to know if a pull request adds a massive dependency.
* You can do your **Assignments, Notes, Quizes Etc** to fit different use cases: for your self development
* Can calculate **Average perfomance of your students for a particular task** 
* Realtime and easy to understand perfomance graphs included ****Office45 

<iframe width="560" height="315" src="https://www.youtube.com/embed/hKNj4aJ9F6s?si=FCfCUULUJp0GKpI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<p align="center">
<img src="http://amandlaomnotho.co.za/wp-content/uploads/2023/10/map.png"
  alt="Link to our file"
   height="386">
</p>


## Who Uses Office45

* [Schools](https://dbe.gov.za)
* [Teacher](https://dbe.gov.za)
* [Community](https://dbe.gov.za)
* [Tutors](https://dbe.gov.za) 
  [Student Suppoort](https://office45.co.za).
* [Learners](https://office45.co.za) 


## How It Works

1. A school is registered with its principal
2. Principal can edit school information and update
3. Principal add subjects the school offers including the teachers
4. Teachers add content, including note, past exams, activities, and books
5. Teacher, principal, registered learners can add Events on announcements page
6. Prospective learner can registered to schools available
7. Principal approves, rejects, requests documents or validates prospective learner's information
8. Application status is shown to the prospective learner, if approved, learner recieves a unique code to register to
   the school and add subject the school offers


## Usage

### How to use the app



<iframe width="560" height="315" src="https://www.youtube.com/embed/hKNj4aJ9F6s?si=FCfCUULUJp0GKpI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


## Reports

Size Limit has a [GitHub action] that comments and rejects pull requests based
on Size Limit output.

1. Install and configure Size Limit as shown above.
2. Add the following action inside `.github/workflows/size-limit.yml`

```yaml
name: "size"
on:
  pull_request:
    branches:
      - master
jobs:
  size:
    runs-on: ubuntu-latest
    env:
      CI_JOB_NUMBER: 1
    steps:
      - uses: actions/checkout@v1
      - uses: andresz1/size-limit-action@v1
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
```



