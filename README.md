# School-courses

* I created this simple program for a CPP course project where the user can add/remove courses from a list.
  * I used bootstrap cards to display the courses.
    * Each card consists of a course number, course title, and an 'add' button to add the course to the list.
    * Upon clicking the 'add' button, I use jQuery to add the the clicked course to a list of registered courses using sessionStorage.
    * When the user clicks the add button, it disappears from the card, and a green check icon appears indicating the class is added to registered courses list.
  * The registered courses are displayed on a separate html file.
    * I used the bootstrap table to display the courses.
    * I also added a remove button where the user can remove a course from the list.
