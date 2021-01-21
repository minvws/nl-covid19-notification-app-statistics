# CoronaMelder statistics

This repository holds statistics that are gathered for the CoronaMelder project.

## Data format

### CoronaMelder downloads

App download numbers can be found in [statistics/app_store_downloads.csv](https://github.com/minvws/nl-covid19-notification-app-statistics/blob/main/statistics/appstore_statistics.csv)

| Column name |Description | Format |
|---|---|---|
| Date | Date for this entry | YYYY-MM-DD|
| Downloads App Store (iOS) (daily) | CoronaMelder iOS downloads as reported by the App Store| Number|
|Downloads Play Store (Android) (daily)| CoronaMelder Android downloads reported by Google Play| Number|
|Downloads Huawei App Gallery (Android) (daily)| CoronaMelder Android downloads reported by Huawei App Gallery| Number|
|Total downloads (daily)| Total downloads for the specified date for all app stores| Number|
|Total downloads (cumulative)| Cumulative number of downloads up to and including the specified date| Number|

### GGD positive test authorisations

For a positive test result the GGD will ask the tested person whether they are using CoronaMelder and if they want to use the app to send a notification. If the user agrees, the code that is shown in the app is entered by the GGD and the user will then proceed to share their unique ids that allow other CoronaMelder apps to check whether they have been in contact with the user. A key can be authorised only once.

The numbers of times the GGD authorised the sharing of unique ids can be found in [statistics/ggd_positive_test_authorisations.csv](https://github.com/minvws/nl-covid19-notification-app-statistics/blob/main/statistics/ggd_positive_test_authorisations.csv)

| Column name |Description | Format |
|---|---|---|
| Date | Date for this entry | YYYY-MM-DD|
| Reported positive tests through app authorised by GGD (daily) | Number of times a GGD key was authorised for the specified date| Number|
|Reported positive test through app authorised by GGD (cumulative)| Cumulative number of positive tests that are authorised by the GGD up to and including the specified date| Number|

### GGD weekly test results following notification from CoronaMelder

Users of CoronaMelder who receive a notification that they may have been in contact with another user of CoronaMelder who has tested positive, are able to get tested for the coronavirus SARS-CoV-2 regardless of whether they are symptomatic or asymptomatic.

The number of tests taken, the number of positive test results, and the positivity rates of these tests can be found in [statistics/ggd_weekly_tests_following_notification_CM.csv](https://github.com/minvws/nl-covid19-notification-app-statistics/blob/main/statistics/ggd_weekly_tests_following_notification_CM.csv)

| Column name | Description | Format |
|---|---|---|
| Week | The week number for this entry | Number |
| Test Requests | The total number of tests requested | Number |
| Total Test Results | The total number of test results | Number |
| Total Positive | The total number of positive test results | Number |
| Total %Positive | The positivity rate of the total number of test results | Number |
| Asymptomatic Test Results | The number of test results for coronavirus cases that are asymptomatic | Number |
| Asymptomatic Positive | The number of positive test results for coronavirus cases that are asymptomatic | Number |
| Asymptomatic %Positive | The positivity rate of the test results for coronavirus cases that are asymptomatic | Number |
| Symptomatic Test Results | The number of test results for coronavirus cases that are symptomatic | Number |
| Symptomatic Positive | The number of positive test results for coronavirus cases that are symptomatic | Number |
| Symptomatic %Positive | The positivity rate of the test results for coronavirus cases that are symptomatic | Number |
