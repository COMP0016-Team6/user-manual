# Patients

A patient user will have most of the dashboard functionalities similar to a clinician. Patients will only be able to access their treatment data. 

## Login

Enter the credentials of your registered patient account. 

![Patients Login](img/patients/login.png)

## Patient Dashboard

This is the patient dashboard which consists of several different components. 

![Patients Patient Dashboard](img/patients/dashboard.png)

### Filter the Data

#### Filter by Specific Date Range

The component on the top left of the dashboard is used to select the date range to filter. 

![Patients Patient Dashboard Date Selector](img/patients/date_range_selector.png)

![Patients Patient Dashboard Date Selector Insight 1](img/patients/insight(1).png)

![Patients Patient Dashboard Date Selector Insight 2](img/patients/insight(2).png)

By selecting a start date and an end date, the dashboard will filter the data only within the date range you selected. 

![Patients Patient Dashboard Filter By Date Range](img/patients/dashboard_date_range.png)

#### Filter By Day, By Month or By Year

The default setting of filtering is `All Data`, change it to `By Day`, `By Month` or `By Year` according to your preference. 

![Patients Patient Dashboard Filter By Day](img/patients/filter_by_day.png)

![Patients Patient Dashboard Filter By Month](img/patients/filter_by_month.png)

![Patients Patient Dashboard Filter By Year](img/patients/filter_by_year.png)

### Data Type

Our web app dashboard supports two types of data type: `Fluid Intake Over Time` and `Energy Intake Over Time`. The default setting is `Fluid Intake Over Time`, you can change to the energy intake graph by using the dropdown.

#### Fluid Intake Over Time

![Patients Patient Dashboard Fluid Intake Over Time](img/patients/fluid_intake_over_time.png)

#### Energy Intake Over Time

![Patients Patient Dashboard Energy Intake Over Time](img/patients/energy_intake_over_time.png)

### Show Weight

To display the weight graph, tick the `Show Weight` box. A separate weight against time graph will be shown in the blue line below the original graph. 

![Patients Patient Dashboard Show Weight](img/patients/show_weight.png)

### Patient Feedback

Hover on the point of the graph to see the percentage difference of received and target feed and click on it to give the clinician feedback at the specific time. In the future, the feedbacks can be helpful to make better-suited treatment plans for patients. 

![Patients Patient Dashboard Hover](img/patients/hover.png)

![Patients Patient Dashboard Patient Feedback](img/patients/feedback.png)

### Access to Patient Information

On the top left of the patient dashboard, there is a `My Information` link to the patient info page.

![Patients Patient Dashboard Info Link](img/patients/info_link.png)

## Patient Information

### Browse Information

This page displays all patient’s information including name, email, date of birth, age, gender, diagnostic conclusion, weight and treatment history. These data will be accessible by both the clinician and the patient. 

![Patients Patient Info Information](img/patients/info.png)

### Change Weight

On the `Patient Info` page, you can also update the patient's weight by clicking on the `Change Weight` button. Submit a positive number to update the new weight of the patient. 

![Patients Patient Info Changing Weight](img/patients/change_weight(1).png)

![Patients Patient Info Change Weight Result](img/patients/change_weight(2).png)