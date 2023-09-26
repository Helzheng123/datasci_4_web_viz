# datasci_4_web_viz
Explore web-based platforms for interactive data visualization, contrasting R's Shiny with Python's equivalents. Harness these tools to present data in interactive and user-friendly ways.

https://f5j0b9-helen0zheng.shinyapps.io/shiny_r_app/

### Challenges Encountered for each deployment:

#### 1. R's Shiny Visualization:
One challenge I faced was deploying the app with shinyapps.io. Following the [tutorial](https://docs.posit.co/shinyapps.io/getting-started.html#working-with-shiny-for-python), I ran into a problem in deploying a sample application. I created too many Shiny Web App since I ran into multiple errors deploying the application but the problem was publishing the application. I kept pressing **Run App** but it came out to be this:

<img width="507" alt="image" src="https://github.com/Helzheng123/datasci_4_web_viz/assets/123939070/6c5f4441-5808-43f7-81a9-68d2cbfbdb38">

Then I pressed **publish application** and realized there were multiple shiny web apps. So I deleted those and then published application on shinyappio and was able to deploy it. [Shiny App deployment](https://f5j0b9-helen0zheng.shinyapps.io/shiny_r_app/)

![image](https://github.com/Helzheng123/datasci_4_web_viz/assets/123939070/4dbc233a-bcaa-41b1-86a2-bd15d6cf6b70)

#### 2. Python's Shiny Visualization:
No complications here. I deployed it with ```shiny run cdc.py --reload``` in google shell cloud.

![image](https://github.com/Helzheng123/datasci_4_web_viz/assets/123939070/1523e1d7-87c5-4667-86af-a2940485cd84)

#### 3. Flask with Matplotlib Visualization:
No complications here. I deployed it with ```python app.py``` in google shell cloud.

![image](https://github.com/Helzheng123/datasci_4_web_viz/assets/123939070/f12e75f0-df30-4203-87b3-217077c31da4)
