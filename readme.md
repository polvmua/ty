Due to lack of information about necessary conditions and incomplete technical task
I can propose only PARTIAL solution.

* This microservices throughput increases at some time of the year
  according to it there is a cronjob for Kubernetes can be realised (hpa_up.yml, hpa_down.yml).
  The main action of it - ability to deploy additional pods with microservices in certain period of time and remove it when necessary (cron * * * )
* Create a flowchart to monitor 4-key metrics.
  There is a common flowchart how to reailise it:
  [4key_metric.jpg](4key_metric.jpg)
* Webhook can be realized with [test_webhook.yml](test_webhook.yml)

Please notice, ALL of these proposals can be optimized in case with detailed task.
