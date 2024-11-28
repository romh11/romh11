graph TD;
    A[المستخدم] -->|يطلب توليد كلمة مرور| B(واجهة المستخدم - JavaScript, HTML, React);
    B -->|يرسل الطلب إلى| C(الواجهة الخلفية - Flask, Django);
    C -->|يتحقق من المدخلات باستخدام| D(أدوات الأمان - OpenSSL, JWT);
    C -->|يولد كلمة المرور باستخدام| E(نموذج تعلم الآلة - TensorFlow);
    E -->|يرسل كلمة المرور إلى| C;
    C -->|يحفظ البيانات في| F(قاعدة البيانات - MySQL, MongoDB);
    C -->|يرسل الرد إلى| B;
    B -->|يعرض كلمة المرور على| A;
    
    C -->|يراقب الأمان باستخدام| G(SIEM - CyberText);
    C -->|يقوم بالفحص الأمني باستخدام| H(أدوات التحقق من الأمان - OWASP ZAP, Burp Suite);
    
    subgraph CyberText
        G
<!---
romh11/romh11 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
