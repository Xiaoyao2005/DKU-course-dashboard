# DKU-course-dashboard
A dashboard (word cloud + radar chart) of comments of all professors in Duke and DKU. Data scraped from Rate My Professor site.
## word cloud
<img src="https://github.com/user-attachments/assets/65f9ee6d-31fb-4971-b17e-4eb4205061cd" height="300" alt="Word Cloud">

  A word cloud of a chosen course by the user. Like the radar plot, users can use three filters to locate a course. The size of each word indicates its frequency in student comments, while color (hue) reflects sentiment (negative, neutral, positive). Saturation shows the intensity of the sentiment. Hovering over a word displays comments containing that word in a box on the right, and the selected word would zoom in, indicating the selection.
  Users could understand the overall comment of the course by the overall color distribution. For example, words in Math105 are almost green, indicating the course is quite well-received by students. Specific word colors offer more nuanced insights of the term itself. For instance, a green “homework” in Math105 indicates manageable assignments, while an orange “homework” in Math308 suggests a heavier workload or more challenging tasks. Users can hover over words to explore detailed comments and gain deeper insights into the course experience.

## radar chart
<img src="https://github.com/user-attachments/assets/0801cf55-abac-4047-a831-1b294cfa0f57" height="400" alt="Radar Chart">

  A radar chart featuring the difficulty, quality, would-take-again rate, numbers of rating and average grade. Users can use the three interactive filters, namely department, subject and number to locate their target course and add them to the plot. At most five plots can be added for the sake of the hair-ball problem. Users can also conveniently switch between different views by hide/show the existing radar plot or delete them if they don’t want them any longer. They could also hover over data points for detailed data. Allow comparison between at most 5 course.
 This interactive radar chart allows users to compare multiple courses directly by selecting courses of interest and gain meaningful comparisons and insights. For example, in this figure, the user compares a series of mandatory math courses. Equivalent/Antirequisite courses like Math 101 and Math 105 show similar radar profiles, but Math 101 has fewer comments, reflecting its lower enrollment compared to Math 105. Math 105 also has a higher quality rating, which could inform course designers about the effectiveness of different teaching approaches.
