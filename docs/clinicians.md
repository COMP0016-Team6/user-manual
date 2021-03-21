# Clinicians

## Login

If you have already register an account, just fill in email and password to input.

![Clinicians Login](img/clinicians/login.png)

## Clinician Dashboard

### Add Patients

Since you just login, you haven't add any patients yet.

![Clinicians Dashboard Without Patients](img/clinicians/dashboard_without_patients.png)

So, for now, you shall click the Add Patients button add some patients to supervise.

Once you enter the add patients page, you will see all patients stored in the database. If you find no patients under the search bar, don't worry. You need to register some before you move to the next step.

![Clinicians Add Patients](img/clinicians/add_patients.png)

On both clinician dashboard page and add patients page, the form which is used to add patients contains only a component `SearchBar` and a button to submit the form.

#### Searching Patients

For the Searching bit, there is a search bar with text info `Search By Name`, after input the name of the patient, the system filter the lowercase of patients' names by the lowercase of input. If the name of the patient includes the input, this name will remain on the list.

![Clinicians Add Patients Searching Patients](img/clinicians/searching_patients(1).png)

#### Choosing Patients

And there are checkboxes for you to select the patients you want to add.

![Clinicians Add Patients Choosing Patients](img/clinicians/choosing_patients.png)

After submitting the form, you can click the `Back` button to return to the clinician dashboard page and you can access your patients' dashboards.

![Clinicians Dasboard With Patients](img/clinicians/dashboard_with_patients.png)

### Access to Patient Dashboard

The search bar is also available for the clinicians to search patients on the `Clinician Dashboard` page.

![Clinicians Dashboard Searching Patients](img/clinicians/searching_patients(2).png)

In addition, patients' names are in blue because each name links to their patient dashboard. 

## Patient Dashboard

This is the overall view of the patient dashboard of the clinician version. It consists of several different components.

![Clinicians Patient Dashboard](img/clinicians/patient_dashboard.png)

### Filter the Data

#### Filter by Specific Date Range

The first component on the top left of the dashboard is used to select the date range to filter. 

![Clinicians Patient Dashboard Date Selector](img/clinicians/date_range_selector.png)

![Clinicians Patient Dashboard Date Selector Insight 1](img/clinicians/insight(1).png)

![Clinicians Patient Dashboard Date Selector Insight 2](img/clinicians/insight(2).png)

After click on that and then select a range of time, the dashboard will filter the date the only remain the range of dates you selected.

![Clinicians Patient Dashboard Filter By Date Range](img/clinicians/dashboard_date_range.png)

#### Filter By Day, By Month or By Year

The default setting of filtering is `All Data`, change it to `By Day`, `By Month` or `By Year` to reset the dashboard.

![Clinicians Patient Dashboard Filter By Day](img/clinicians/filter_by_day.png)

![Clinicians Patient Dashboard Filter By Month](img/clinicians/filter_by_month.png)

![Clinicians Patient Dashboard Filter By Year](img/clinicians/filter_by_year.png)

### Data Type

Our web app dashboard supports two types of data type: `Fluid Intake Over Time` and `Energy Intake Over Time`, the default setting is `Fluid Intake Over Time`, change the selection to the second one to check the patient's energy intake over time.

#### Fluid Intake Over Time

![Clinicians Patient Dashboard Fluid Intake Over Time](img/clinicians/fluid_intake_over_time.png)

#### Energy Intake Over Time

![Clinicians Patient Dashboard Energy Intake Over Time](img/clinicians/energy_intake_over_time.png)

### Show Weight

If tick the checkbox `Show Weight`, the dashboard will display the change of patient's body weight changes over time in a blue line on a new graph.

![Clinicians Patient Dashboard Show Weight](img/clinicians/show_weight.png)

### Patient Feedback

Just hover on the point of the graph to see the percentage difference of received and target feed and click on it to give the clinician timely feedback at the specific time. In the future, the feedbacks are significant evidence to make new treatments plans.

![Clinicians Patient Dashboard Hover](img/clinicians/hover.png)

![Clinicians Patient Dashboard Patient Feedback](img/clinicians/feedback.png)

### Change Treatment Plan

At the bottom of the page, there is a button for the clinicians to change a new treatment for their patients.

![Clinicians Patient Dashboard Change Treatment Plan](img/clinicians/change_treatment_plan.png)

All three text fields must fill in. Besides, the Target Feed Volume and Target Energy Intake have to greater than 0. Otherwise, the input is invalid.

The new personalised treatment will be kept in the database and be able to review on the patient info page.

### Access to Patient Information

Similar to the counterpart of the clinician dashboard, the name in blue indicates that it links to a new page, `patient info`.  

![Clinicians Patient Dashboard Title](img/clinicians/dashboard_title.png)

## Patient Information

### Browse Information

This page displays all patients information including name, email, date of birth, age, gender, diagnostic conclusion, weight and treatment history.

Both clinicians and patients can check all treatment plans since the patient received medical care in the treatments history bit.

![Clinicians Patient Info Information](img/clinicians/info.png)

### Change Weight

On the `Patient Info` page, change weight is also allowed. Click on the `Change Weight` button, input a natural number, submit it.

![Clinicians Patient Info Changing Weight](img/clinicians/change_weight(1).png)

![Clinicians Patient Info Change Weight Result](img/clinicians/change_weight(2).png)