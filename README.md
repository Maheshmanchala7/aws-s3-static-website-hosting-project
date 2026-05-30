# AWS S3 Static Website Hosting Project

## Project Overview

This project demonstrates hosting a static website using Amazon S3. A custom HTML webpage was uploaded to an S3 bucket and configured for public static website hosting.

The project simulates simple cloud-based website deployment using AWS storage services.

---

## Services Used

* AWS S3
* Static Website Hosting
* Bucket Policies
* HTML

---

## Architecture

User → Amazon S3 Bucket → Static Website

---

## Steps Performed

### 1. Created S3 Bucket

Created S3 bucket for static website hosting.

---

### 2. Disabled Public Access Block

Allowed public access to host the website publicly.

---

### 3. Created Custom HTML Page

Created:

```text id="jlwmp4"
index.html
```

Uploaded webpage content to S3 bucket.

---

### 4. Enabled Static Website Hosting

Enabled S3 static website hosting feature.

Configured index document:

```text id="jlwmt7"
index.html
```

---

### 5. Configured Bucket Policy

Added public read bucket policy for website access.

---

### 6. Accessed Static Website

Successfully accessed website using S3 website endpoint URL.

---

## Screenshots

* S3 Dashboard
* Bucket Creation
* Uploaded HTML File
* Static Website Hosting Enabled
* Bucket Policy
* Website Endpoint URL
* Live Website Output

---

## Challenges Faced

* Bucket policy configuration
* Public access troubleshooting
* Static website hosting setup

---

## Outcome

Successfully hosted a static website using Amazon S3 with public access and static website hosting configuration.
