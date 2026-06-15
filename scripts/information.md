Bronze Bucket Name - yt-masterclass-data-pipeline-bronze-ap-south-1
Silver Bucket Name - yt-masterclass-data-pipeline-silver-ap-south-1
Gold Bucket Name - yt-masterclass-data-pipeline-gold-ap-south-1

Script Buclet Name - yt-masterclass-data-pipeline-script-ap-south-1

SNS ARN - arn:aws:sns:ap-south-1:107758683691:yt-sns-masterclass-data-pipeline-alerts-dev:e4ce8f1f-4c00-40f5-b8e2-195605e8726d

Youtube API Key - AIzaSyA8Ug4wrOt0pzA3LyTI6Om5qJYzc8YU5EU

-- Glue Job Parameters Bronze to Silver  --
--bronze_database yt-db-masterclass-data-pipeline-bronze-dev
--bronze_table raw_statistics
--silver_bucket yt-masterclass-data-pipeline-silver-ap-south-1
--silver_database yt-db-masterclass-data-pipeline-silver-dev
--silver_table clean_statistics


-- Glue Job Parameters Silver to Gold  --
--silver_database yt-db-masterclass-data-pipeline-silver-dev
--gold_bucket yt-masterclass-data-pipeline-gold-ap-south-1
--gold_database yt-db-masterclass-data-pipeline-gold-dev