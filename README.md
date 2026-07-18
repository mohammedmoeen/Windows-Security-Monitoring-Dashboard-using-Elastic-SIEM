# Windows-Security-Monitoring-Dashboard-using-Elastic-SIEM
هذا المشروع من منصة  Hack The Box في موديول Security Monitoring & SIEM Fundamentals , عبارة عن Dashboard داخل Kibana / Elastic SIEM لمراقبة أحداث أمنية مهمة في Windows Logs.
الهدف هو بناء 4 Visualizations تساعد محلل SOC Tier 1 على مراقبة:

1. Failed Logon Attempts for all users
2. Failed Logon Attempts for disabled users
3. Successful RDP logons using service accounts
4. Users added or removed from local Administrators group

المشروع يعتمد على Windows Event Logs داخل Elastic باستخدام Data View:

- windows*
