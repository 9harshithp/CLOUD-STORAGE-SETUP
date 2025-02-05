# CLOUD-STORAGE-SETUP

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: HARSHITH P

**INTERN ID**:CT08IJR

**DOMAIN**: Cloud Computing

**BATCH DURATION**: January 30th, 2025 to March 1st, 2025

**MENTOR NAME**: NEELA SANTHOSH

# ENTER DESCRIPTON OF TASK PERFORMED NOT LESS THAN 500 WORDS

1. Setting Up the S3 Bucket
The first step was logging into the AWS Management Console and navigating to the S3 service. I created a new bucket with the name my-cloud-storage-bucket914, ensuring the name was unique to avoid conflicts with existing buckets. The bucket was created in the Asia Pacific (Mumbai) region, chosen to provide optimal performance based on geographical proximity.

The following settings were configured during the bucket creation:

Object Ownership: I selected the ACLs disabled option, as recommended. This setting ensured that all objects stored in the bucket would be owned by the bucket's owner (the account creating the bucket), and access control would be managed through bucket policies instead of Access Control Lists (ACLs).
Block Public Access: The default setting to block all public access was left enabled to prevent unauthorized external access to the data stored within the bucket.
2. Uploading an Image File
To test the functionality of the bucket, I uploaded a sample image file named nature.jpg. This image was chosen to verify that non-text files, such as images, could be stored and accessed appropriately within the bucket. The upload process was straightforward using the S3 console, where I simply selected the file from my local machine and confirmed the upload.

3. Configuring Permissions
Since the task did not require making the bucket or files public, I opted to maintain the privacy settings:

The Block Public Access setting remained enabled by default, ensuring that only authorized users could access the files.
Permissions were controlled through the bucket’s settings without the need for any additional configurations for public access.
If public access had been required, the next step would have been to create a bucket policy to allow access to specific objects. However, for this setup, access control was managed simply through the default privacy settings.

4. Verification
To verify the setup, I navigated to the Objects tab of the bucket and located the nature.jpg file that had been uploaded. I copied the Object URL of the image file and attempted to open it in a web browser. Since the bucket was private, attempting to access the URL resulted in a "403 Forbidden" error, confirming that the file was protected as expected.

Conclusion
This task provided a hands-on introduction to setting up a cloud storage solution using AWS S3. It involved creating a unique bucket, uploading an image file, and configuring the necessary permissions to ensure the data was protected. The process demonstrated the simplicity and flexibility of AWS S3, allowing users to manage storage with ease while maintaining control over access. Through this setup, I gained practical experience with the core features of AWS S3 and its permissions model, which will be valuable for future cloud-based tasks.

**Output of the Task**:
