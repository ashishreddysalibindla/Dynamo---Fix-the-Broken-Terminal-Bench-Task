Analyze the access log located at /app/access.log and create a JSON report at /app/report.json.

The report must contain the following fields:
- total_requests: the total number of requests in the access log
- unique_ips: the number of unique client IP addresses
- top_path: the URL path with the highest number of requests

Success criteria:

1. The file /app/report.json exists and contains valid JSON.
2. The JSON report contains total_requests with the correct number of requests from the log.
3. The JSON report contains unique_ips with the correct number of unique client IP addresses from the log.
4. The JSON report contains top_path with the most frequently requested URL path from the log.