
# Verifikasi dan Validasi Perangkat Lunak  2022/2023

Tugas Matakuliah Verifikasi dan Validasi Perangkat Lunak Semester 05 2022/2023


## What you need

- Browsers: Mozilla Firefox, Google Chrome, or Microsoft Internet Explorer
- Selenium browser drivers: Chrome Driver and InternetExplorerDriver
- Selenium tools: The Selenium WebDriver client driver (based on your preference of programming language) and Selenium Standalone Server
- IDE: Eclipse, IntelliJ IDEA, and Microsoft Visual Studio (for .NET)
- BDD framework tools: Cucumber-JVM, SpecFlow.NET (for .NET), and Capybara (for Ruby)
- Build and integration tools: Maven, ANT, and Jenkins
- Other GUI automations tools: AutoIt and Sikuli
- Mobile tools: Apple Xcode (for iOS mobile browser testing), Android SDK, Android Server APK, and Appium
- Language runtimes: JDK 1.7 or JDK 1.8 (for Java), Ruby 1.9+ (for Ruby), and Python 2.7+ (for Python)

## Download
- IDE :
```bash
Eclipse  : https://www.eclipse.org/downloads/
IntelliJ : https://www.jetbrains.com/idea/download/

*Chose One
```

- WebDriver
```bash
  https://chromedriver.chromium.org/downloads
```
- Selenium Clients and WebDriver Language Bindings 
```bash
Java    : https://github.com/SeleniumHQ/selenium/releases/download/selenium-4.5.0/selenium-java-4.5.2.zip
Python  : https://pypi.python.org/pypi/selenium
C#      : https://www.nuget.org/api/v2/package/Selenium.WebDriver
Other   : https://www.selenium.dev/downloads/
*Chose One
```
## Add To
- pom.xml
```bash
<project xmlns="http://maven.apache.org/POM/4.0.0"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xsi:schemaLocation="http://maven.apache.org/POM/4.0.0
http://maven.apache.org/xsd/maven-4.0.0.xsd">
 <modelVersion>4.0.0</modelVersion>
 <groupId>com.secookbook.examples</groupId>
 <artifactId>SeleniumCookbook</artifactId>
 <version>0.0.1-SNAPSHOT</version>
 <dependencies>

		<dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-java</artifactId>
            <version>4.4.0</version>
            <scope>test</scope>
        </dependency>
		
		<dependency>
			<groupId>junit</groupId>
			<artifactId>junit</artifactId>
			<version>4.12</version>
			<scope>test</scope>
		</dependency>
		
</dependencies>
</project>
```



## Authors

- [@dzayeate](https://github.com/dzayeate/)


## License

[MIT](https://choosealicense.com/licenses/mit/)

