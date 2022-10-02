<p align="center">
<img alt="Logo" src="static/header_git.png"/ width="1000">
</p>

<h2 align="center">
 Data observability for analytics & data engineers
</h2>
<h4 align="center">
Monitor your data quality, operation and performance directly from your dbt project.
</h4>

<p align="center">
<a href="https://join.slack.com/t/elementary-community/shared_invite/zt-uehfrq2f-zXeVTtXrjYRbdE_V6xq4Rg"><img src="https://img.shields.io/badge/join-Slack-ff69b4"/></a>
<a href="https://docs.elementary-data.com/quickstart"><img src="https://img.shields.io/badge/docs-quickstart-orange"/></a>
<img alt="License" src="https://img.shields.io/badge/license-Apache--2.0-ff69b4"/>
<img alt="Downloads" src="https://static.pepy.tech/personalized-badge/elementary-lineage?period=total&units=international_system&left_color=grey&right_color=orange"&left_text=Downloads"/>

<div align="center">

⭐️ If you like it, star the repo <a href="https://github.com/elementary-data/elementary/stargazers"><img src="static/star_github.png" width="30"/></a> ⭐

[Demo »](https://bit.ly/3IAp9wf) | [Docs »](https://docs.elementary-data.com/) | [Slack »](https://join.slack.com/t/elementary-community/shared_invite/zt-uehfrq2f-zXeVTtXrjYRbdE_V6xq4Rg)

</div>

## Quick start

Step 1 - [Install Elementary dbt package](https://docs.elementary-data.com/quickstart) 

Step 2 - [Install Elementary CLI](https://docs.elementary-data.com/quickstart-cli)

   
## Features

<kbd align="center">
        <a href="https://storage.googleapis.com/elementary_static/elementary_demo.html"><img align="center" style="max-width:300px;" src="static/report_ui.gif"> </a>
</kbd>

<br>
<br>


 <img src="static/elementary_icon.ico" width="16"/> **Data observability report** - Generate a data observability report, host it or share with your team.

 <img src="static/elementary_icon.ico" width="16"/> **Anomaly detection dbt tests** - Collect data quality metrics and detect anomalies, as native dbt tests.

 <img src="static/elementary_icon.ico" width="16"/> **Test results** - Enriched with details for fast triage of issues.

 <img src="static/elementary_icon.ico" width="16"/> **Models performance** - Visibility of execution times, easy detection of degradation and bottlenecks.

 <img src="static/elementary_icon.ico" width="16"/> **Data lineage** - Enriched with test results, easy to navigate and filter.

 <img src="static/elementary_icon.ico" width="16"/> **dbt artifacts uploader** - Save metadata and run results as part of your dbt runs. 

 <img src="static/elementary_icon.ico" width="16"/> **Slack alerts** - Actionable alerts, including custom channels and tagging of owners and subscribers.


##
 
Join [Slack](https://join.slack.com/t/elementary-community/shared_invite/zt-uehfrq2f-zXeVTtXrjYRbdE_V6xq4Rg) to learn more on Elementary.

Our full documentation is [available here](https://docs.elementary-data.com/).


## How it works?

Elementary dbt package creates tables of metadata and test results in your data warehouse, as part of your dbt runs. The CLI tool reads the data from these tables, and is used to generate the UI and alerts. 

<img align="center" style="max-width:300px;" src="static/how_elementary_works.png">

## Community & Support

For additional information and help, you can use one of these channels:

* [Slack](https://join.slack.com/t/elementary-community/shared_invite/zt-uehfrq2f-zXeVTtXrjYRbdE_V6xq4Rg) \(Live chat with the team, support, discussions, etc.\)
* [GitHub issues](https://github.com/elementary-data/elementary/issues) \(Bug reports, feature requests)
* [Twitter](https://twitter.com/ElementaryData) \(Updates on new releases and stuff)


## **Integrations**

* [x] **dbt core (>=1.0.0)** ![](static/dbt-16.png)
* [x] **dbt cloud**  ![](static/dbt-16.png)

**Data warehouses:**
* [x] **Snowflake** ![](static/snowflake-16.png) 
* [x] **BigQuery**  ![](static/bigquery-16.svg) 
* [x] **Redshift**  ![](static/redshift-16.png)
* [x] **Databricks**  ![](static/databricks-16.png)

**Operations:**

* [x] **Slack** ![](static/slack-16.png)
* [x] **GitHub Actions**  ![](static/github-actions-16.png)
* [x] **S3**  ![](static/s3-16.svg)
* [x] **GSC**  ![](static/gcs-16.png)



Ask us for integrations on [Slack](https://join.slack.com/t/elementary-community/shared_invite/zt-uehfrq2f-zXeVTtXrjYRbdE_V6xq4Rg) or as a [GitHub issue](https://github.com/elementary-data/elementary-lineage/issues/new).


## **Contributions**

Thank you :orange_heart: Whether it’s a bug fix, new feature, or additional documentation - we greatly appreciate contributions!

Check out the [contributions guide](https://docs.elementary-data.com/general/contributions) and [open issues](https://github.com/elementary-data/elementary/issues). 


## **License**

Elementary is licensed under Apache License 2.0. See the [LICENSE](https://github.com/elementary-data/elementary/blob/master/LICENSE) file for licensing information.
