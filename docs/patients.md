# Patients

The patient version is very similar to that of the clinician's version in functionalities apart from some features such as add patients, but it mainly focuses on browsing the patient's himself dashboard and information rather than checking other patients or changing important treatment plans.

## Register

Similar to the clinician's version, the register page also needs basic information. However, this page requires more information including gender, date of birth to calculate age, diagnostic conclusion provided by clinicians, initial treatment plan information.

Please pay attention to fill in these fields according to common sense, for example, weight must be greater than 0 and should not be a string.

![Patients register](img/patients/register.png)

Click the `Submit`, and then login as a patient.

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

Our web app dashboard supports two types of data type: `Volume Over Time` and `Energy Intake Over Time`, the default setting is `Volume Over Time`, change the selection to the second one to check the patient's energy intake over time.

#### Volume Over Time

![Patients Patient Dashboard Volume Over Time](img/patients/volume_over_time.png)

#### Energy Intake Over Time

![Patients Patient Dashboard Energy Intake Over Time](img/patients/energy_intake_over_time.png)

### Show Weight

If tick the checkbox `Show Weight`, the dashboard will display the change of patient's body weight changes over time in a blue line.

![Patients Patient Dashboard Show Weight](img/patients/show_weight.png)

### Patient Feedback

Just hover on the point of the graph to see the percentage difference of received and target feed and click on it to give the clinician timely feedback at the specific time. In the future, the feedbacks are significant evidence to make new treatments plans.

![Patients Patient Dashboard Hover](img/patients/hover.png)

![Patients Patient Dashboard Patient Feedback](img/patients/feedback.png)