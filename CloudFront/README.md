## waf
for i in {1..40}; do    curl -o /dev/null -s -w "%{http_code}\n" https://d7hxygrbzgen3.cloudfront.net/ ; done
