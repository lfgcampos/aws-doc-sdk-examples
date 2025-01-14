<!--Generated by WRITEME on 2023-04-18 12:02:57.344163 (UTC)-->
# Amazon S3 code examples for the SDK for Java 2.x

## Overview

Shows how to use the AWS SDK for Java 2.x to work with Amazon Simple Storage Service (Amazon S3).

<!--custom.overview.start-->
<!--custom.overview.end-->

*Amazon S3 is storage for the internet. You can use Amazon S3 to store and retrieve any amount of data at any time, from anywhere on the web.*

## ⚠ Important

* Running this code might result in charges to your AWS account.
* Running the tests might result in charges to your AWS account.
* We recommend that you grant your code least privilege. At most, grant only the minimum permissions required to perform the task. For more information, see [Grant least privilege](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege).
* This code is not tested in every AWS Region. For more information, see [AWS Regional Services](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services).

<!--custom.important.start-->
<!--custom.important.end-->

## Code examples

### Prerequisites

For prerequisites, see the [README](../../README.md#Prerequisites) in the `javav2` folder.


<!--custom.prerequisites.start-->
<!--custom.prerequisites.end-->

### Single actions

Code excerpts that show you how to call individual service functions.

* [Add CORS rules to a bucket](src/main/java/com/example/s3/S3Cors.java#L66) (`PutBucketCors`)
* [Add a lifecycle configuration to a bucket](src/main/java/com/example/s3/LifecycleConfiguration.java#L70) (`PutBucketLifecycleConfiguration`)
* [Add a policy to a bucket](src/main/java/com/example/s3/SetBucketPolicy.java#L65) (`PutBucketPolicy`)
* [Copy an object from one bucket to another](src/main/java/com/example/s3/CopyObject.java#L61) (`CopyObject`)
* [Create a bucket](src/main/java/com/example/s3/CreateBucket.java#L61) (`CreateBucket`)
* [Delete a policy from a bucket](src/main/java/com/example/s3/DeleteBucketPolicy.java#L55) (`DeleteBucketPolicy`)
* [Delete an empty bucket](src/main/java/com/example/s3/S3BucketOps.java#L91) (`DeleteBucket`)
* [Delete multiple objects](src/main/java/com/example/s3/DeleteMultiObjects.java#L59) (`DeleteObjects`)
* [Delete the website configuration from a bucket](src/main/java/com/example/s3/DeleteWebsiteConfiguration.java#L56) (`DeleteBucketWebsite`)
* [Determine the existence and content type of an object](src/main/java/com/example/s3/GetObjectContentType.java#L59) (`HeadObject`)
* [Download objects to a local directory](src/main/java/com/example/s3/transfermanager/DownloadToDirectory.java#L11) (`DownloadDirectory`)
* [Get an object from a bucket](src/main/java/com/example/s3/GetObjectData.java#L66) (`GetObject`)
* [Get the ACL of a bucket](src/main/java/com/example/s3/GetAcl.java#L61) (`GetBucketAcl`)
* [Get the policy for a bucket](src/main/java/com/example/s3/GetBucketPolicy.java#L58) (`GetBucketPolicy`)
* [List in-progress multipart uploads](src/main/java/com/example/s3/ListMultipartUploads.java#L56) (`ListMultipartUploads`)
* [List objects in a bucket](src/main/java/com/example/s3/ListObjects.java#L56) (`ListObjects`)
* [Restore an archived copy of an object](src/main/java/com/example/s3/RestoreObject.java#L67) (`RestoreObject`)
* [Set a new ACL for a bucket](src/main/java/com/example/s3/SetAcl.java#L64) (`PutBucketAcl`)
* [Set the website configuration for a bucket](src/main/java/com/example/s3/SetWebsiteConfiguration.java#L59) (`PutBucketWebsite`)
* [Upload an object to a bucket](src/main/java/com/example/s3/PutObject.java#L68) (`PutObject`)
* [Upload directory to a bucket](src/main/java/com/example/s3/transfermanager/UploadADirectory.java#L11) (`UploadDirectory`)

### Scenarios

Code examples that show you how to accomplish a specific task by calling multiple
functions within the same service.

* [Create a presigned URL](src/main/java/com/example/s3/GeneratePresignedUrlAndUploadObject.java) 
* [Get started with buckets and objects](src/main/java/com/example/s3/S3Scenario.java) 

## Run the examples

### Instructions


<!--custom.instructions.start-->
<!--custom.instructions.end-->



#### Create a presigned URL

This example shows you how to create a presigned URL for Amazon S3 and upload an object.


<!--custom.scenario_prereqs.s3_Scenario_PresignedUrl.start-->
<!--custom.scenario_prereqs.s3_Scenario_PresignedUrl.end-->

<!--custom.scenarios.s3_Scenario_PresignedUrl.start-->
<!--custom.scenarios.s3_Scenario_PresignedUrl.end-->

#### Get started with buckets and objects

This example shows you how to do the following operations:

* Create a bucket and upload a file to it.
* Download an object from a bucket.
* Copy an object to a subfolder in a bucket.
* List the objects in a bucket.
* Delete the bucket objects and the bucket.

<!--custom.scenario_prereqs.s3_Scenario_GettingStarted.start-->
<!--custom.scenario_prereqs.s3_Scenario_GettingStarted.end-->

<!--custom.scenarios.s3_Scenario_GettingStarted.start-->
<!--custom.scenarios.s3_Scenario_GettingStarted.end-->

### Tests

⚠ Running tests might result in charges to your AWS account.


To find instructions for running these tests, see the [README](../../README.md#Tests)
in the `javav2` folder.



<!--custom.tests.start-->
<!--custom.tests.end-->

## Additional resources

* [Amazon S3 User Guide](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)
* [Amazon S3 API Reference](https://docs.aws.amazon.com/AmazonS3/latest/API/Welcome.html)
* [SDK for Java 2.x Amazon S3 reference](https://sdk.amazonaws.com/java/api/latest/software/amazon/awssdk/services/s3/package-summary.html)

<!--custom.resources.start-->
<!--custom.resources.end-->

---

Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.

SPDX-License-Identifier: Apache-2.0