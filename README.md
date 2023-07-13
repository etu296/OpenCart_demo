# OpenCart_demo
Performance test with 10 user, with blaze meter &amp; generate html report with apace Jmeter
# Generate HTML report
step-1 convert jmx file to jtl file with this command
# jmeter -n -t Opencart_demo_10.jmx -l Opencart_demo_10.jtl
step-2 Then generate html report with this command
# jmeter -g Opencart_demo_10.jtl -o report\Opencart_demo_10.html
