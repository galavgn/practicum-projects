
### Data


- `final_ab_new_users_upd_us.csv` — all users who signed up in the online store from December 7 to 21, 2020

- `final_ab_events_upd_us.csv` — all events of the new users within the period from December 7, 2020 through January 1, 2021

- `final_ab_participants_upd_us.csv` — table containing test participants

Structure of **ab_project__marketing_events_us.csv:**
- `name` — the name of the marketing event

- `regions` — regions where the ad campaign will be held

- `start_dt` — campaign start date

- `finish_dt` — campaign end date

Structure of **final_ab_new_users_upd_us.csv:**
- `user_id`

- `first_date` — sign-up date

- `region`

- `device` — device used to sign up

Structure of **final_ab_events_upd_us.csv:**
- `user_id`

- `event_dt` — event date and time

- `event_name` — event type name

- `details` — additional data on the event (for instance, the order total in USD for purchase events)

Structure of **final_ab_participants_upd_us.csv:**
- `user_id`

- `ab_test` — test name

- `group` — the test group the user belonged to

### Goal

  Purpose of the test:testing changes related to the introduction of an improved recommendation system
  
- Study the results of the experiment
- Test the hypothesis:

### Libraries
pandas, numpy, skipy, seaborn, matplotlib, plotly
