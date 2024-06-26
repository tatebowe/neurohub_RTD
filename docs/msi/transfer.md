# Data Transfer and Sharing Tools

## Moving data around

**Overview**

1. Data acquired at the scanner is reconstructed into dicoms that show up in the Patient Browser. 
2. Push dicom data from the Patient Browser to Naxos. 
3. Transfer data from Naxos to MSI (Tier 1 or Tier 2). For more information on this step, please visit our [Transfering data from CMRR](../cmrr/transfer2.md){:target="_blank"} page.

### Tier 1 (disk) <--> Tier 2 (s3)

Data can be transferred between Tier 1 and Tier 2 via the s3cmd command - [details here.](https://www.msi.umn.edu/support/faq/how-do-i-use-second-tier-storage-command-line){:target="_blank"}

### Tier 1 (disk) <--> Local storage

Your UMN computer has a local storage space that you may want to use for working on specific files. You can transfer files between local and MSI Tier 1 systems via [winSCP](https://www.msi.umn.edu/support/faq/how-do-i-use-winscp-transfer-data){:target="_blank"} or [FileZilla](https://www.msi.umn.edu/support/faq/how-do-i-use-filezilla-transfer-data){:target="_blank"}

## Letting others have access to s3 buckets

See [this guide](https://www.msi.umn.edu/support/faq/how-do-i-use-s3-buckets-share-data-tier-2-storage-other-users){:target="_blank"}. More about buckets. 

# Globus

Globus is a file transfer service that has encrypted services for transmitting large-scale data between institutions. Checkout the [Globus How-to page](../resources/globussop.md){:target="_blank"} or visit UMN's [starting guide](https://www.msi.umn.edu/support/faq/how-do-i-use-globus-transfer-data-msi-0){:target="_blank"} for information on setting up Globus for transferring data to and from MSI servers.

# Box

Box is a secure storage that is HIPPA compliant and available across many institutions. UMN’s IT maintains a [set of guides](https://it.umn.edu/services-technologies/self-help-guides/box-secure-storage-work-files-folders){:target="_blank"} to learn how to use Box effectively. 