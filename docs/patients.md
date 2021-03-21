# Patients

The patient version is very similar to that of the clinician's version in functionalities apart from some features such as add patients, but it mainly focuses on browsing the patient's himself dashboard and information rather than checking other patients or changing important treatment plans.

## Login

If you have already register an account, just fill in email and password to input.

![Patients Login](img/patients/login.png)

## Patient Dashboard

This is the overall view of the patient dashboard of the clinician version. It consists of several different components.

![Patients Patient Dashboard](img/patients/dashboard.png)

### Filter the Data

#### Filter by Specific Date Range

The first component on the top left of the dashboard is used to select the date range to filter. 

![Patients Patient Dashboard Date Selector](img/patients/date_range_selector.png)

![Patients Patient Dashboard Date Selector Insight 1](img/patients/insight(1).png)

![Patients Patient Dashboard Date Selector Insight 2](img/patients/insight(2).png)

After click on that and then select a range of time, the dashboard will filter the date the only remain the range of dates you selected.

![Patients Patient Dashboard Filter By Date Range](img/patients/dashboard_date_range.png)

#### Filter By Day, By Month or By Year

The default setting of filtering is `All Data`, change it to `By Day`, `By Month` or `By Year` to reset the dashboard.

![Patients Patient Dashboard Filter By Day](img/patients/filter_by_day.png)

![Patients Patient Dashboard Filter By Month](img/patients/filter_by_month.png)

![Patients Patient Dashboard Filter By Year](img/patients/filter_by_year.png)

### Data Type

Our web app dashboard supports two types of data type: `Fluid Intake Over Time` and `Energy Intake Over Time`, the default setting is `Fluid Intake Over Time`, change the selection to the second one to check the patient's energy intake over time.

#### Fluid Intake Over Time

![Patients Patient Dashboard Fluid Intake Over Time](img/patients/fluid_intake_over_time.png)

#### Energy Intake Over Time

![Patients Patient Dashboard Energy Intake Over Time](img/patients/energy_intake_over_time.png)

### Show Weight

If tick the checkbox `Show Weight`, the dashboard will display the change of patient's body weight changes over time in a blue line on a new graph.

![Patients Patient Dashboard Show Weight](img/patients/show_weight.png)

### Patient Feedback

Just hover on the point of the graph to see the percentage difference of received and target feed and click on it to give the clinician timely feedback at the specific time. In the future, the feedbacks are significant evidence to make new treatments plans.

![Patients Patient Dashboard Hover](img/patients/hover.png)

![Patients Patient Dashboard Patient Feedback](img/patients/feedback.png)

### Access to Patient Information

On the top left of the patient dashboard, there is a `My Information` link to go to the information page.

![Patients Patient Dashboard Info Link](img/patients/info_link.png)

## Patient Information

### Browse Information

This page displays all patients information including name, email, date of birth, age, gender, diagnostic conclusion, weight and treatment history.

Both clinicians and patients can check all treatment plans since the patient received medical care in the treatments history bit.

![Patients Patient Info Information](img/patients/info.png)

### Change Weight

On the `Patient Info` page, change weight is also allowed. Click on the `Change Weight` button, input a natural number, submit it.

![Patients Patient Info Changing Weight](img/patients/change_weight(1).png)

![Patients Patient Info Change Weight Result](img/patients/change_weight(2).png)