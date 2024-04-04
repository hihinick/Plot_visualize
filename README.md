# Plot_visualize
Self-developing visualization library using Plotly library created by Nick Cheng.

When I need to quickly review the data, I need to call out every column in dataset and find the program syntax of each visualization library.

So I decided to self-develop my library, including sort value, filter index, set the visualization image, etc., which are extremely high frequently used functions.


Default parameter setting : plotly_plot(data, choose=False, From=None, To=None, sort=False, By=None, x_name=None, y_name=None, Save=False, fig_name='test'):

Parameters:

          data : name of the dataset
        choose : if filter the index or not (True or False)
          From : when choose=True, put the index you want to visualize from (integer type)
            To : when choose=True, put the index you want to stop visualize (integer type)
          sort : if sort the value or not (True or False)
            By : when sort=True, put the column you want to sort by
        x_name : x-axis name (string type)
        y_name : y-axis name (string type)
          Save : save file or not (True or False), if True, automatically build a folder named "images" to store the image, and save in png format
      fig_name : put file name (string type)

Let's start at plotly!

[1] Import required library

[2] Read CSV file

[3] Set the image title, filter a part of the data, and set the names of the x/y axis.

![image](https://github.com/hihinick/Plotly_visualize/assets/86997964/4fa17260-c0be-4ed7-b536-79da4cdcdeb5)



[4] Visualize through Plotly library
![image](https://github.com/hihinick/Plotly_visualize/assets/86997964/6d4cb30b-9142-4591-99df-4b8afcec9029)

One of the pros that I love is that Plotly can zoom in/ zoom out or choose a part of the dataset, which is convenient to quickly observe the dataset.

![image](https://github.com/hihinick/Plotly_visualize/assets/86997964/f4ddc863-4835-416d-9e8a-fc7daabb816b)

[5] Visualize through Matplotlib library
![image](https://github.com/hihinick/Plotly_visualize/assets/86997964/ff5da182-bc4f-4940-9239-1146a9dadf85)

If there are any questions, please fill free to contact me by email: nick87812916@gmail.com.

Welcome any suggestions! Thank you :)


