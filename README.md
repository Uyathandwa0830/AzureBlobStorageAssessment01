Prerequisites:
Before using the program, make sure you have the following prerequisites:
Visual Studio: Visual Studio with the.NET desktop development workload preloaded.
You'll need an Azure Storage Account with the Blob Storage feature activated.

Setup Your Environment.
Visual Studio version: [Visual Studio 2022].
.NET Core SDK Version: [Microsoft .Net SDK 8.0.204].
To create a new.NET Core Console application, first create a new project and open Visual Studio.
Choose "Create a New Project."
Select the "Console App (.NET Core)" template.
Create a project called "AzureBlobStorageAssessment" and click "Create."

a)To integrate Azure Blob Storage: 
Add the Azure Storage Blob Client Library.
Right-click the project in Solution Explorer.
Click "Manage NuGet Packages..."
Search for "Azure.Storage.Blobs" and install the most recent stable version.

b)Initialize. BlobServiceClient
Get the Azure Storage Account's connection string from the Azure portal:
Navigate to the Azure portal.
Navigate to your storage account.
Under "Settings," look for "Access keys."
Copy one of the connection strings listed.
2.Initialize the BlobServiceClient with the connection string from your code.

Implement Blob Operations

a) Upload the Blob
Implement a method for uploading a file to a given blob container. Handle arguments and errors correctly.
b) List the Blobs.
Create a method for listing all blobs in a specific container. Describe how your approach handles pagination when there are several blobs.
c)Download a Blob.
Implement a method for downloading a blob from a given container. Details on file overwrite and error handling.
d)Delete a Blob.
Implement a mechanism for deleting a specific blob. Explain how you confirm the existence of the blob before attempting to remove it.
