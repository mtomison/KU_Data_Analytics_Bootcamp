# Matplotlib Functions	Feature
- plt.figure(figsize=(w, h))	Change the size of the figure in pixels. Added on the first line of the script.
- plt.plot(x, y, label='line')	Add a label that will be added to the legend.
- plt.xlim(min, max)	Set the min and max range of the x-axis.
- plt.ylim(min, max)	Set the min and max range of the y-axis.
- plt.xlabel('x label')	Add a label to the x-axis.
- plt.ylabel('y label')	Add a label to the y-axis.
- plt.title("Title")	Add a title.
- plt.legend()	Add a legend.
- plt.grid()	Add a grid to the chart.
- plt.savefig("add a path and figure extension")	Save the figure with the given extension. Added at the end of the script.


### To declare the parameters for line color, width, and marker, we use color=, width=, and marker=, respectively, inside the plt.plot() function.


Ex: plt.plot(x_axis, y_axis, marker="*", color="blue", linewidth=2, label='Boston')



# Matplotlib Object-Oriented Functions	Feature
- fig, ax = plt.subplots(figsize=(w, h))	Change the size of the figure in pixels. Add this in the subplots() function.
- ax.plot(x, y, label='line')	Add a label that will be added to the legend.
- ax.set_ylim(min, max)	Sets the min and max range of the y-axis.
- ax.set_xlim(min, max)	Sets the min and max range of the x-axis.
- ax.set_xlabel('x label')	Add a label to the x-axis.
- ax.set_ylabel('y label')	Add a label to the y-axis.
- ax.set_title("Title")	Add a title.
- ax.legend()	Add a legend.
- ax.grid()	Add a grid to the chart.
*plt.savefig("add a path and figure extension")	Saves the figure with the given extension. Added at the end of your script.
