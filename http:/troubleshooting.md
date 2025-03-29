Troubleshooting
Missing Anomaly Detector
If you do not find any of the detector (lambda-invoke, ebs-create_volume, ec2-run_instances) check the cloudwatch logs for the opensearch anomaly detector config automation lambda function.
You can manually re-run the lambda function in case the detector creation fails for some reason.
No Data in EC2/EBS/Lambda Opensearch dashboards
Check the time window as there might be no events for the specific time window.
Generate custom data by triggering the events. You can do so by creating an ec2 instance or ebs volume or just invoking lambda functions.
