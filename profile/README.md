# CSCI 3155 GitHub Classroom

We're implementing GitHub Classroom for this semester, which allows students to get some experience with using Git and remote version control tools. It will also expose students to automation pipelines with the autograder.

## How to see your grade

After pushing your commit, you can check your grade for the assignment by doing the followinG:

1. When looking at your repository, click on the `Actions` button to look at GitHub Actions.
   
  ![](https://raw.githubusercontent.com/csci3155-sp24/.github/main/profile/Step_1.png)

  - On this page, you will see all the automated workflows that have been integrated for your repository.

2. Click on the `GitHub Classroom Workflow` button on the left to specifically view the workflows that are for grading the assignment.

  ![](https://raw.githubusercontent.com/csci3155-sp24/.github/main/profile/Step_2.png)

3. Every tile is a workflow from a commit. Notice that there could be 3 different statuses for a workflow. A cross means you failed a test case, a check means you passed all test cases, and a grayed out slash means there wasn't a grading workflow ran.

  ![](https://raw.githubusercontent.com/csci3155-sp24/.github/main/profile/Step_3.png)

4. Clicking on a tile will give you more information regarding that workflow. To view specific details regarding the output from the workflow, click the `Autograding` button

  ![](https://raw.githubusercontent.com/csci3155-sp24/.github/main/profile/Step_4.png)

5. The tabs shown are the different tasks that were ran as a part of this workflow. Clicking on `Run education/autogradig@v1` will reveal the output of the autograding task.

  ![](https://raw.githubusercontent.com/csci3155-sp24/.github/main/profile/Step_5.png)

6. Scrolling to the bottom of the bottom will show the total points from the output. The test cases that were passed and missed are also shown.

  ![](https://raw.githubusercontent.com/csci3155-sp24/.github/main/profile/Step_6.png)