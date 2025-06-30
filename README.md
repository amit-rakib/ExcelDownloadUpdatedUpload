# ExcelDownloadUpdatedUpload

This project automates the process of downloading an Excel file from a [demo web page](https://rahulshettyacademy.com/upload-download-test/), updating it with Apache POI, and uploading it back using Selenium WebDriver. The update is verified through both a UI check and a success message assertion.

## 📌 Features

- Automates Excel file download and upload
- Modifies specific cell values dynamically using Apache POI
- Uses Selenium WebDriver for UI automation
- Includes validation of upload success
- Verifies data consistency post-upload

## 🧪 Test Workflow

1. Navigate to the website.
2. Download the Excel file.
3. Update the value for "Apple" in the "Price" column to **599**.
4. Upload the modified file back.
5. Verify the success toast message.
6. Check if the new price is correctly displayed in the table.

## 📁 Project Structure

```bash
ExcelDownloadUpdatedUpload/
├── src/
│   └── test/
│       └── UploadDownload.java
├── target/
├── pom.xml
└── README.md
```
## ⚙️ Setup Instructions

### Clone the repository

```bash
git clone https://github.com/amit-rakib/ExcelDownloadUpdatedUpload.git
cd ExcelDownloadUpdatedUpload
```

### Install dependencies
Make sure you have Maven and Java 17+ installed.

```bash
mvn clean install
```

Run the test
You can run the test using your IDE or via command line:

``` bash
mvn exec:java -Dexec.mainClass="UploadDownload" -Dexec.classpathScope=test

```
## 🔧 Prerequisites

- Google Chrome browser 
- ChromeDriver in your system PATH
- Java 17 or above
- Maven
- Internet connection
- Apache POI dependencies (included in pom.xml)

## ✍️ Author

Md. Amit Hasan Rakib

Email: mdamithasanrakib11@gmail.com

