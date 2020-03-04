### Google Cloud Storage Bugbounty


Tool to enumerate Google Storage Buckets and permissions: https://github.com/RhinoSecurityLabs/GCPBucketBrute

### Enumerate bucket permission
```
www.googleapis.com/storage/v1/b/{change_it_with_bucket_name}/iam/testPermissions?permissions=storage.buckets.delete&permissions=storage.buckets.get&permissions=storage.buckets.getIamPolicy&permissions=storage.buckets.setIamPolicy&permissions=storage.buckets.update&permissions=storage.objects.create&permissions=storage.objects.delete&permissions=storage.objects.get&permissions=storage.objects.list&permissions=storage.objects.update
```
