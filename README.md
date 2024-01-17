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

<h3>I started this project by creating two different buckets in two different regions 
 (us-east-1)(us-west-2)</h3>

<p align="center">
Create rule name and confrim source bucket<br/>
<img src="https://i.imgur.com/5s7Gsp0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Choose destination and enable object versioning<br/>
<img src="https://i.imgur.com/YZWjo2s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Upload dog photos<br/>
<img src="https://i.imgur.com/X1ahqhM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Rename photos because my dogs deserve that<br/>
<img src="https://i.imgur.com/NNZ9bAa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe changes in second bucket(notice changes in names caused multiple versions) <br/>
<img src="https://i.imgur.com/qpaQPVY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 The Team<br/>
<img src="https://i.imgur.com/sjXnyJY.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
