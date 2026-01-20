# AZ Cloud Storage - S3 Compatible Object Storage
**Source URL:** https://azdigi.com/en/az-cloud-storage/

Object Storage

# AZ Cloud Storage
Highly scalable and affordable Object Storage. S3 API compatible, 3x replication, free domestic bandwidth - transparent pricing with no hidden fees.

- S3 API Compatible

- 3x Replication

- Unlimited transfer

Get started  View features →

## What can you do with AZ Cloud Storage?
### Static Asset Hosting
Store and deliver images, CSS, JS for websites at high speed.

### Backup & Archive
Backup database, server logs, enterprise data at low cost.

### Software Delivery
Distribute software, artifacts, packages with high bandwidth.

### AI/ML Dataset
Store large datasets for AI/ML model training.

### n8n Workflow Storage
Store attachments and binary data from n8n workflows. Configure S3 as external storage for files from emails, form submissions, webhooks - reduce n8n database load and centralize file management with easy backup.

### Drive/Cloud Alternative
Combine with Nextcloud or FileRun to build your own storage system, replacing Google Drive, Dropbox. Full control over your data, privacy protection, no third-party dependency.

## Why choose AZ Cloud Storage?
Solve traditional cloud storage problems

### High Performance
Designed for high throughput, optimized read/write with 10Gbps network and enterprise-grade infrastructure.

### S3 API Compatible
Leverage existing ecosystem of tools, SDKs, plugins. No code changes needed.

### Data Safety
Data replicated 3 copies across independent nodes, ensuring 99.99% durability.

### Unlimited Scaling
Storage automatically scales with your needs. Support up to 100 buckets.

### Access Logging
Detailed access tracking for analytics, security and compliance.

### Transparent Pricing
No domestic egress fees, no hidden costs. Only pay for what you use.

## Performance & Infrastructure
Enterprise-grade Object Storage with High Availability.

### 3x Replication
Every data is stored in 3 copies across independent nodes.

### 99.99% Durability
Highest data durability commitment, no data loss.

### 10Gbps Network
High-speed network for upload/download.

### Encryption
Encryption at rest and in transit.

99.99%

Durability

3x

Replication

10Gbps

Network

Pricing

## Choose Storage Capacity
Drag the slider to select your storage capacity. Price based on usage.

100 GB

Storage

100 GB 10 TB

Unit Price

$0 /GB

Monthly Cost

$3 /month

[Register now](https://my.azdigi.com/cart.php?a=add&pid=427&configoption\[379\]=100)

Storage can be flexibly adjusted after registration.

#### All plans include
- Fully S3 API compatible

 __ Unlimited upload/download transfer

 __ Data replicated 3 copies

 __ 99.99% Durability

 __ Encryption at rest and in transit

Price excludes VAT. Payment via bank transfer, VNPay, Apple Pay, QR, MoMo.

Specs & Features

## AZ Cloud Storage Technical Specifications
S3-compatible Object Storage with enterprise features.

- Performance & Safety __ SDK & Tools

Specs may vary by plan. Details shown per your selected plan.

#### API
S3 Compatible

Fully S3 API compatible.

#### Replication
3x Replicas

Every data stored in 3 independent copies.

#### Durability
99.99%

High data durability commitment.

#### Network
10Gbps

High-speed upload/download.

S3 Compatible – 3x Replication – Unlimited Transfer

## Service Commitment
### 99.9% Uptime
Highest service uptime commitment, ensuring your website is always available.

### 24/7 Technical Support
Technical team monitors and supports continuously, even outside business hours.

### Fast Incident Response
Receive and handle incidents by priority, ensuring minimal disruption.

### Backup & Data Protection
Data is backed up regularly and protected on secure infrastructure.

## AZ Cloud Storage vs AWS S3
Compare to see pricing and location advantages.

Criteria  |  AWS S3  |  AZ Cloud Storage
---|---|---
S3 API  |  Native  |  __Compatible
Storage Price  |  ~$0.023/GB  |  __~$0.015/GB
Data Replication  |  Configuration-dependent  |  __3x copies
Durability  |  99.999999999%  |  __99.99%
Datacenter  |  Singapore  |  __Vietnam
Support  |  English  |  __Vietnamese 24/7

AZ Cloud Storage better pricing, datacenter in Vietnam, Vietnamese support.

## Frequently Asked Questions
Is AZ Cloud Storage S3 compatible? __

Yes. Fully S3 API compatible - you can use AWS SDK, AWS CLI, and S3 tools like rclone, s3cmd, Cyberduck without code changes.

How is data protected? __

Every data is replicated 3x across independent nodes and encrypted at rest and in transit. If one node fails, data remains safe and system auto-recovers. 99.99% durability guaranteed.

Is there a storage limit? __

No total storage limit. Each object max 5TB, max 100 buckets. Storage automatically scales with your needs.

Does AZ Cloud Storage support CDN? __

Currently AZDIGI does not provide built-in CDN to use AZ Cloud Storage with custom domain. However, you can use external CDN services like BunnyCDN, Cloudflare or KeyCDN to configure CDN for your S3 bucket. These services support S3-compatible storage and allow custom domain configuration for content delivery.

How to integrate S3 with WordPress? __

Use WP Offload Media or Media Cloud plugin to connect WordPress with AZ Cloud Storage. Just enter Access Key, Secret Key and Endpoint. Uploaded images and videos automatically store to S3, reducing server load and speeding up your website.

What are the benefits of using S3 for WordPress? __

Reduce hosting storage usage, faster image loading with high bandwidth, easy backup and migration, no server space worries. Website runs lighter as media is served directly from Object Storage.

How to configure n8n to use S3 storage? __

In n8n's .env file, configure N8N _EXTERNAL_ STORAGE _S3_ BUCKET, N8N _EXTERNAL_ STORAGE _S3_ ACCESS _KEY, N8N_ EXTERNAL _STORAGE_ S3 _SECRET_ KEY and Endpoint. Attachments from emails, forms, webhooks will be stored in S3 instead of database, making n8n run more stable.

Can I use Nextcloud with AZ Cloud Storage? __

Yes. Configure Primary Storage or External Storage in Nextcloud to use S3. Build your own cloud storage system like Google Drive but with full control over your data, no third-party dependency.

Does FileRun support S3? __

Yes. FileRun supports S3 as storage backend. Combine with AZ Cloud Storage to create a professional file management system, replacing Dropbox with user-friendly interface and high security.

How to backup MySQL/PostgreSQL database to S3? __

Use mysqldump or pg_dump combined with rclone or aws-cli to upload backup files to S3. Automate with cron jobs. Data replicated 3x, safer than storing on server.

Does rclone work with AZ Cloud Storage? __

Yes. Rclone fully supports S3-compatible storage. Configure with 'rclone config', enter Access Key, Secret Key and Endpoint. Use for sync, backup, mount as drive on your computer.

Can I use Restic to backup to S3? __

Yes. Restic supports S3 backend with end-to-end encryption. Configure RESTIC_REPOSITORY with s3:endpoint/bucket-name. Fast incremental backup, saves storage, easy version restoration.

Does Duplicati support AZ Cloud Storage? __

Yes. Duplicati supports S3-compatible storage with easy-to-use graphical interface. Set up automatic backup, AES-256 encryption, data compression and scheduled backups.

How to store AI/ML datasets on S3? __

Upload datasets using aws-cli, boto3 (Python) or rclone. S3 is suitable for large datasets with parallel read capability. Many ML frameworks like TensorFlow, PyTorch support reading directly from S3.

Can I mount S3 as a drive? __

Yes. Use rclone mount or s3fs to mount bucket as directory on Linux/macOS. Suitable for applications needing direct file read/write without code changes.

How to backup cPanel/DirectAdmin to S3? __

cPanel supports S3 destination in Backup Configuration. DirectAdmin uses script with rclone. Daily automatic backup, safe off-server storage, easy restoration when needed.

Can Laravel/PHP use S3? __

Yes. Laravel Filesystem has built-in S3 driver. Configure in config/filesystems.php with 's3' driver, enter credentials. Upload files with Storage::disk('s3')->put(). Flysystem PHP also supports S3.

How does Node.js connect to S3? __

Use AWS SDK for JavaScript (@aws-sdk/client-s3). Configure endpoint, credentials and call methods like PutObject, GetObject. Fully compatible, no code changes needed if already using AWS S3.

Does Python boto3 work with AZ Cloud Storage? __

Yes. boto3 supports S3-compatible storage. Add endpoint _url when initializing client. All operations like upload_ file, download _file, list_ objects work normally.

Is there an API to manage buckets? __

Yes. Use S3 API to create/delete buckets, upload/download objects, manage permissions. Full support for aws-cli, SDKs in all languages, and tools like Cyberduck, S3 Browser.

## What our customers say
Thousands of customers trust us to host their websites.

"This company offers high-quality services that are specifically tailored for Vietnamese customers. Whether you need help with hosting products or have any inquiries, they are always available to answer your questions and try to assist you."

Liem Tran

Google Review

"Quá hài lòng về dịch vụ của AZdigi. Hỗ trợ cực nhanh, chuyên nghiệp. Hệ thông tốt, thanh toán là có dịch vụ sẵn sàn để dùng ngay."

Kiet Tan Luu

Google Review

"Mình sử dụng rất nhiều hosting bên Azdigi ngon và ổn định, sài ở đâu ko bằng bên này. Đội ngũ kỹ thuật hỗ trợ chuyên môn cao như bạn Quân và team, ngoài ra họ hỗ trợ liên tục nên mình sài an tâm. Mình và bạn bè mình ủng hộ Azdigi lâu dài. Mong công ty phát triển hơn nữa."

Duc Phan Ba

Google Review

"Dùng dịch vụ của rất nhiều bên, nhưng AZDIGI là đơn vị mình thấy ổn nhất cho đến hiện tại. Support nhanh gọn, vào việc. Giá cả hợp lí. Rất recommend cho các bạn nha."

Phong Do

Google Review

"Mình đã gặp một số vấn đề và rất may mắn được anh Trung Kiên hỗ trợ rất nhiệt tình và nhanh chống. Cảm thấy team AZDIGI rất năng động và tận tâm vì vậy mình đã mua thêm gói hosting ở đây. Chúc team luôn mạnh khoẻ và tiếp tục hỗ trợ tốt cho các khách hàng khác. Cảm ơn rất nhiều!"

Hữu Nguyễn

Google Review

"Sau một thời gian sử dụng dịch vụ hosting tại AZDIGI, Trường Cao đẳng Công nghệ Sài Gòn xin gửi lời cảm ơn chân thành đến đội ngũ AZDIGI vì đã luôn đồng hành và hỗ trợ chúng tôi. Qua quá trình sử dụng, chúng tôi đánh giá cao AZDIGI ở các điểm sau: 1\. Hosting hoạt động ổn định, tốc độ truy cập tốt, đáp ứng nhu cầu 2\. Dịch vụ hỗ trợ chuyên nghiệp, đội ngũ kỹ thuật và kinh doanh phản hồi nhanh, xử lý vấn đề kịp thời và rõ ràng (có các video hướng dẫn), phù hợp với các đơn vị không chuyên sâu về kỹ thuật (Như tôi: một người không am hiểu nhiều về website như tôi cũng có thể dễ dàng thao tác được) 3\. Chính sách khuyến mại, ưu đãi hợp lý vào các dịp lễ, giúp tối ưu chi phí sử dụng dịch vụ lâu dài. Với những trải nghiệm tích cực trên, Trường Cao đẳng Công nghệ Sài Gòn hoàn toàn tin tưởng và sẵn sàng giới thiệu AZDIGI đến các đơn vị, doanh nghiệp đang tìm kiếm một giải pháp hosting ổn định và dịch vụ hỗ trợ tận tâm."

Trần Văn Huỳnh

Trường Cao đẳng Công nghệ Sài Gòn

"Tôi là Phú, hiện đang sử dụng dịch vụ tại AZDIGI. Trong suốt quá trình sử dụng, tôi cảm thấy rất hài lòng về chất lượng dịch vụ cũng như sự hỗ trợ từ đội ngũ kỹ thuật. Hệ thống hoạt động ổn định, tốc độ tốt, các vấn đề phát sinh (nếu có) đều được hỗ trợ nhanh chóng và rõ ràng."

Nguyễn Hoàng Phú

Công ty TNHH Giấy In Chợ Lớn

### Partners & featured customers
Trusted by over 80,000 customers

%20--%3e%3csvg%20version='1.1'%20id='Layer_1'%20xmlns='http://www.w3.org/2000/svg'%20xmlns:xlink='http://www.w3.org/1999/xlink'%20x='0px'%20y='0px'%20viewBox='0%200%20143%2028'%20style='enable-background:new%200%200%20143%2028;'%20xml:space='preserve'%3e%3cstyle%20type='text/css'%3e%20.st0{fill:%23231F20;}%20%3c/style%3e%3cg%3e%3cpath%20class='st0'%20d='M66.1,8.6v1.2C64.5,8.6,62.8,8,61,8c-2.5,0-4.7,0.8-6.6,2.5c-2.2,2-3.3,4.4-3.3,7.5c0,2.6,0.8,4.9,2.5,6.7%20c2,2.2,4.4,3.3,7.3,3.3c1.8,0,3.4-0.6,5-1.8v1.2h4.8V8.6H66.1z%20M65,21.7c-1,1.3-2.3,1.9-3.9,1.9c-1.4,0-2.6-0.5-3.6-1.5%20c-1-1-1.5-2.4-1.5-4.2c0-1.5,0.4-2.7,1.1-3.7c1-1.3,2.3-1.9,3.9-1.9c1.5,0,2.7,0.5,3.6,1.4c1,1,1.5,2.4,1.5,4.1%20C66.1,19.5,65.7,20.7,65,21.7'/%3e%3cpath%20class='st0'%20d='M89.4,10.5C88,8.9,85.8,8,83.6,8c-1.6,0-3,0.5-4.4,1.6v-1h-4.8v18.7h4.8V18c0-2.2,0.3-3.6,0.9-4.3%20c0.7-0.9,1.8-1.3,3.1-1.3c1.1,0,1.9,0.3,2.5,1c0.6,0.7,0.9,2.1,0.9,4.2v9.8l4.8,0V17.3C91.5,14.1,90.9,12.1,89.4,10.5'/%3e%3cpath%20class='st0'%20d='M108.3,8.6l0,1.2c-1.6-1.2-3.3-1.8-5-1.8c-2.5,0-4.7,0.8-6.6,2.5c-2.2,2-3.3,4.4-3.3,7.5%20c0,2.6,0.8,4.9,2.5,6.7c2,2.2,4.4,3.3,7.3,3.3c1.8,0,3.4-0.6,5-1.8v1.2l4.8,0V8.6H108.3z%20M107.3,21.7c-1,1.3-2.3,1.9-3.9,1.9%20c-1.4,0-2.6-0.5-3.6-1.5c-1-1-1.5-2.4-1.5-4.2c0-1.5,0.4-2.7,1.1-3.7c1-1.3,2.3-1.9,3.9-1.9c1.5,0,2.7,0.5,3.6,1.4%20c1,1,1.5,2.4,1.5,4.1C108.4,19.5,108,20.7,107.3,21.7'/%3e%3cpath%20class='st0'%20d='M126.4,11.8l-2.5-1c-1.6-0.6-2.6-1.4-2.9-2.2H116c0.3,2.8,2.3,4.9,5.8,6.3l2.4,0.9c1.2,0.5,2.1,0.9,2.7,1.4%20c0.7,0.6,1.1,1.3,1.1,2.2c0,1.1-0.4,2-1.1,2.8c-0.8,0.8-1.8,1.3-3,1.3c-2.2,0-3.6-1.3-4.3-3.9c-0.1-0.2-0.1-0.5-0.2-1l-4.6,1.2%20c0.2,0.8,0.3,1.3,0.4,1.5c0.5,1.8,1.4,3.3,2.8,4.5c1.7,1.4,3.6,2.1,6,2.1c2.4,0,4.4-0.7,6.1-2.1c2-1.7,3-3.8,3-6.4%20c0-1.8-0.6-3.3-1.7-4.6C130.2,13.7,128.6,12.7,126.4,11.8'/%3e%3cpath%20class='st0'%20d='M124.5,4.4c1.1,0,2,0.4,2.9,1.2c0.5,0.5,0.8,0.9,1.5,2l4.4-1.1c-0.2-0.4-0.3-0.8-0.5-1.2c0,0-0.7-1.5-1.9-2.8%20C129,0.8,127,0,124.5,0c0,0-92.3,0-92.3,0v4.4C32.2,4.4,124.4,4.4,124.5,4.4'/%3e%3cpath%20class='st0'%20d='M140.3,25.8h-0.9l-0.9-1.7c-0.1,0-0.2,0-0.3,0h-0.2v1.7h-0.8v-4.5h1c0.1,0,0.1,0,0.2,0c0.2,0,0.5,0,0.8,0%20c0.1,0,0.2,0,0.4,0.1c0.1,0,0.2,0.1,0.3,0.2c0.1,0.1,0.2,0.2,0.3,0.3c0.1,0.1,0.2,0.2,0.2,0.4c0.1,0.1,0.1,0.3,0.1,0.5%20c0,0.1,0,0.2-0.1,0.4c0,0.1-0.1,0.2-0.2,0.4c-0.1,0.1-0.2,0.2-0.3,0.3c-0.1,0.1-0.3,0.2-0.5,0.2L140.3,25.8z%20M137.9,23.4h0.3%20c0.1,0,0.2,0,0.3,0c0.1,0,0.2,0,0.3,0c0.1,0,0.2,0,0.3-0.1c0.1,0,0.2-0.1,0.2-0.1c0.1,0,0.1-0.1,0.2-0.2c0-0.1,0.1-0.2,0.1-0.3%20c0-0.1,0-0.2-0.1-0.3c-0.1-0.2-0.3-0.3-0.6-0.3c-0.2,0-0.4,0-0.7,0h-0.3V23.4z'/%3e%3cpath%20class='st0'%20d='M138.6,28c-2.4,0-4.4-2-4.4-4.4c0-2.4,2-4.4,4.4-4.4c2.4,0,4.4,2,4.4,4.4C143,26,141,28,138.6,28%20M138.6,20%20c-2,0-3.6,1.6-3.6,3.6s1.6,3.6,3.6,3.6c2,0,3.6-1.6,3.6-3.6S140.6,20,138.6,20'/%3e%3cpath%20class='st0'%20d='M49.3,27.4V17.3c0-3.2-0.6-5.2-2.1-6.8C45.8,9,43.6,8,41.4,8c-1.6,0-3,0.5-4.4,1.6l0-1h-4.8l0,13.8l-4.6-1.7%20V2.7V0h-7.1L0,26.3L4.6,28l6.5-8.3l21.1,7.7v0l4.8,0V18c0-2.2,0.3-3.6,0.9-4.3c0.7-0.9,1.8-1.3,3.1-1.3c1.1,0,1.9,0.3,2.5,1%20c0.6,0.7,0.9,2.1,0.9,4.2v9.8H49.3z%20M23,19.1l-8.9-3.2L23,4.5V19.1z'/%3e%3c/g%3e%3c/svg%3e)

Get Started

## Ready to use AZ Cloud Storage?
Start with S3-compatible Object Storage, 3x replication, free domestic bandwidth. AZDIGI team ready to support.

Register Storage now

Review pricing
