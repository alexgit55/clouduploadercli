# clouduploadercli
Use the cli to upload a file to a storage account in azure

2/8/2024 - research on how to upload a file to a storage account in azure. have to create a storage account, if you don't have one already, and then create a container in that storage account
         - the main resource for completing this basic functionality is from https://learn.microsoft.com/en-us/azure/storage/blobs/blob-cli
         - created a simple testfile.txt file to upload and confirmed i was able to upload the file to this new container
         - my script location to the PATH env variable so that the script can be run from any directory to upload a file
         - created a simple function that checks whether the file passed to the script exists and can be uploaded. if it doesn't exist, script stops and won't try to login