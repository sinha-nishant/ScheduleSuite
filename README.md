# Schedule Suite
See all possible combinations of your USC schedule based on the courses you want.

## Dependencies
* Branca - To customize format of popups on map
* Folium - To display interactive maps
* Requests - To query USC Schedule of Classes API
* See specific versions listed in [requirements.txt](requirements.txt)

## How to Use
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sinha-nishant/ScheduleSuite/blob/master/ScheduleSuite.ipynb)

Note: To run in Colab click 'Runtime' in the top toolbar then 'Run All'
1. Enter the course codes for all courses you want to have in your schedule for the semester.
2. If you have already registered for any sections, you should enter their section IDs. Without the section numbers, the program could only include open sections even though you could be already be enrolled in sections with no available spots.
3. Next, if you would like to exclude any professors from the results, you can enter their names.
4. If necessary, you may exclude quiz sections from consideration. This should only be used if a quiz section for one of your courses does not have a designated day or time.
5. You can set time periods (in 24 hour format) within which you would like to each day of classes to begin and end. For example, if you would like to keep your mornings and evenings clear, you could input 11:00,17:00.
6. Lastly, you can view interactive maps for each displayed schedule option. Note the menu in the top right of the map which allows you to view each schedule day-by-day. You can click on the pins to view classes you have in each building on a given day.
