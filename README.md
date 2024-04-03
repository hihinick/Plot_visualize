# Plot_visualize
Self-developing visualization library using Plotly library created by Nick Cheng.

When I need to quickly review the data, I need to call out every column in dataset and find the program syntax of each visualization library.

So I decided to self-develop my library, including sort value, filter index, set the visualization image, etc., which are extremely high frequently used.

Default parameter setting : plotly_plot(data,choose=False,From=None,To=None,sort=False,By=None,x_name=None,y_name=None,Save=False,fig_name='test'):
Parameters:

          data : name of data set
        choose : if filter the index or not (True or False)
          From : when choose=True, put the index you want to visualize from (integer type)
            To : when choose=True, put the index you want to stop visualize (integer type)
          sort : if sort the value or not (True or False)
            By : when sort=True, put the column you want to sort by
        x_name : x axis name (string type)
        y_name : y axis name (string type)
          Save : save file or not (True or False), if True, automatically build a folder named "images" to store the image, save as png format
      fig_name : put file name (strong type)

Let's try it!
[1] import required library
[2] read csv file
[3] visualize
![image](https://github.com/hihinick/Plotly_visualize/assets/86997964/0cc8ad5f-c5ae-4122-9f57-455471875888)


