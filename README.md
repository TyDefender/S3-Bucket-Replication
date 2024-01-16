<h1>Cross-Region S3 Bucket with Replication</h1>

<h2>Description</h2>
During this lab, I explored the functionality of Amazon S3, focusing on the automatic replication of objects stored in our S3 bucket to a different region across the country. The purpose of this process is to ensure the accessibility of our files under various scenarios, particularly those involving potential data loss.

Throughout the lab, I successfully learned how to create S3 buckets and implement automatic replication, providing a secure backup for files in a geographically separate location. This hands-on experience has equipped me with the knowledge and skills to safeguard our data and maintain accessibility even in challenging circumstances.
<br />


<h2>Tools Used</h2>

- <b>S3</b> 
- <b>Replication</b>
- <b>Versioning</b>

<h2>Environments Used </h2>

- <b>AWS</b>

<h2>Project walk-through:</h2>

<p align="center">
Launch S3 Bucket (with unique name) : <br/>
<img src="https://i.imgur.com/3XJxeTP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Unblock Public Access:  <br/>
<img src="https://i.imgur.com/91yDfPq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Upload index and error files: <br/>
<img src="https://i.imgur.com/B1VJodj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enable Static Hosting:  <br/>
<img src="https://i.imgur.com/Meky0c4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Write Custom Bucket Policy:  <br/>
<img src="https://i.imgur.com/OLjVWL0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Publicly Accessible Static Website:  <br/>
<img src="https://i.imgur.com/G9O1gNw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
