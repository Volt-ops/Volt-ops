**'''Cybersec Volt**


Cybersec Volt is a simple, Python-based cybersecurity tool that allows you to perform various security checks on web applications, including:

.WAF Detection: Detects if a Web Application Firewall (WAF) is protecting the target website.

.Basic SQL Injection (SQLi) Testing: Tests for SQL injection vulnerabilities.

.Cross-Site Scripting (XSS) Testing: Checks for potential XSS vulnerabilities.

.HTTP Header Analysis: Analyzes HTTP headers for important security configurations.

.This tool is designed for security enthusiasts and web developers to quickly test websites for common security flaws.





**Requirements**


Before you can use Cybersec Volt, you need to ensure the following:
1. **Python 3.x** installed on your system.
2. **pip** (Python package manager) to install dependencies.
3. An **Internet connection** to download required libraries.


**Usage**


After you run the tool, you’ll be presented with a simple menu where you can choose which security test you’d like to run:

1. **WAF Detection**: Check if a Web Application Firewall (WAF) is protecting the website.
2. **SQL Injection Test**: Test for SQL injection vulnerabilities on the website.
3. **XSS Test**: Check for potential Cross-Site Scripting (XSS) vulnerabilities.
4. **HTTP Header Analysis**: Analyze the HTTP headers of the website for security settings.


- **Clone the repository**:
```
git clone https://github.com/yourusername/cybersec-volt.git
```
- Set up the virtual environment (recommended) or use **pipx**.


- **Install the dependencies**:

```
pip install -r requirements.txt
```

- **Run the tool**:

```
python3 cybersec-volt.py
```


- **Example:**
```
$ python3 cybersec-volt.py

Welcome to Cybersec Volt!

Please choose a test:
1. WAF Detection
2. SQL Injection Test
3. XSS Test
4. HTTP Header Analysis

Enter the number of the test you'd like to run: 1
Enter the target URL: https://example.com
```
